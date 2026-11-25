## sqlinjected

DFIR and Windows internals. I build small tools that read what a Windows machine
is actually doing: event logs, services, registry. I'm interested in what holds up
under testing, not what sounds good.

### Projects

<p align="center">
  <a href="https://github.com/sqlinjected/evtx"><img alt="EVTX Triage" src="https://img.shields.io/badge/EVTX%20Triage-30363D?logo=github&logoColor=white"></a>
  <a href="https://github.com/sqlinjected/persist-diff"><img alt="persist-diff" src="https://img.shields.io/badge/persist--diff-30363D?logo=github&logoColor=white"></a>
  <a href="https://github.com/sqlinjected/tornspector"><img alt="tornspector" src="https://img.shields.io/badge/tornspector-30363D?logo=github&logoColor=white"></a>
  <a href="https://github.com/sqlinjected/glock"><img alt="glock" src="https://img.shields.io/badge/glock-30363D?logo=github&logoColor=white"></a>
</p>

**[evtx](https://github.com/sqlinjected/evtx)**
Offline Windows event log triage. Parses `.evtx` files and flags brute force, password
spraying, suspicious service installs, and log clearing. Each finding is explained in
plain English. Uses a 22M-parameter MiniLM model running locally through ONNX Runtime
to score service installs that keyword rules miss. Includes a leave-one-out eval and an
ablation showing where the model helps and where it doesn't.

`Python` `ONNX Runtime` `pytest`

### Merged Upstream

<img alt="PRs merged upstream" src="https://img.shields.io/github/issues-search?query=author%3Asqlinjected%20is%3Apr%20is%3Amerged%20-user%3Asqlinjected&label=PRs%20merged%20upstream&color=8957E5">

**[ChrisTitusTech/winutil](https://github.com/ChrisTitusTech/winutil)** <img alt="stars" src="https://img.shields.io/github/stars/ChrisTitusTech/winutil?style=flat&label=%E2%98%85&color=30363D">
- [#5251](https://github.com/ChrisTitusTech/winutil/pull/5251) fix: prevent FOSS badges from clipping
- [#5253](https://github.com/ChrisTitusTech/winutil/pull/5253) fix(tweaks): update classic context menu registry workaround

**[wbp318/github-leaderboard](https://github.com/wbp318/github-leaderboard)** <img alt="stars" src="https://img.shields.io/github/stars/wbp318/github-leaderboard?style=flat&label=%E2%98%85&color=30363D">
- [#11](https://github.com/wbp318/github-leaderboard/pull/11) fix: support shareable leaderboard view URLs
- [#14](https://github.com/wbp318/github-leaderboard/pull/14) Recognize more US state-code formats

### Currently Building

- **[persist-diff](https://github.com/sqlinjected/persist-diff)**: snapshots Windows
  persistence points and diffs them between runs
- **[SQLab](https://github.com/sqlinjected/SQLab)**: discord server setup tool
- **[tornspector](https://github.com/sqlinjected/tornspector)**: ranked-war intel
  tool
- **[tornotifier](https://github.com/sqlinjected/tornotifier)**: Torn userscript that
  plays sound alerts for in-game events, using only the Torn API
- **[torninja](https://github.com/sqlinjected/torninja)**: draggable ninja war partner
  for Torn with chain, hospital and travel timer alerts
- **[tct](https://github.com/sqlinjected/tct)**: Torn City Time conversion clock widget
- **[sat2x](https://github.com/sqlinjected/sat2x)**: Arduino Pro Micro firmware that
  turns a Sega Saturn racing wheel into an XInput controller
- **[glock](https://github.com/sqlinjected/glock)**: keeps the mouse on the game
  screen in dual-monitor setups
- Discord optimization program
- seed Discord server setup automator
- A local web UI for evtx-triage: drop in logs, get a findings timeline

### Working in

`Python` `Lua` `SQL` `CSS` `JS` `C#`

### Stats

![Metrics](https://raw.githubusercontent.com/sqlinjected/sqlinjected/main/github-metrics.svg)

![Star history across my public repos](assets/stars.svg)
