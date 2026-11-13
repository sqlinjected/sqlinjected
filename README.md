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

### Currently Building

- **[persist-diff](https://github.com/sqlinjected/persist-diff)**: snapshots Windows
  persistence points and diffs them between runs
- **[tornspector](https://github.com/sqlinjected/tornspector)**: ranked-war intel
  reports for Torn factions
- **[SQLab](https://github.com/sqlinjected/SQLab)88: discord server setup tool
- Discord optimization program
- A local web UI for evtx-triage: drop in logs, get a findings timeline

### Working in

`Python` `Lua` `SQL` `CSS`
