## sqlinjected

DFIR and Windows internals. I build small tools that read what a Windows machine
is actually doing: event logs, services, registry. I'm interested in what holds up
under testing, not what sounds good.

### Projects

**[evtx-triage](https://github.com/sqlinjected/evtx)**
Offline Windows event log triage. Parses `.evtx` files and flags brute force, password
spraying, suspicious service installs, and log clearing. Each finding is explained in
plain English. Uses a 22M-parameter MiniLM model running locally through ONNX Runtime
to score service installs that keyword rules miss. Includes a leave-one-out eval and an
ablation showing where the model helps and where it doesn't.
`Python` `ONNX Runtime` `pytest`

### Currently building

- A local web UI for evtx-triage where you can drop in logs and view a findings timeline
- A larger held-out set of real 7045 service-install events to test whether the model
  generalizes better than hand-written rules
- Windows 11 general optimization suite
- Discord server setup tool
- Discord custom rich presence suite
- Persist diff Windows project first build
