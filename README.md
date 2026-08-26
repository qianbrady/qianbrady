# qianbrady

![Repos](https://img.shields.io/badge/public%20repos-28-blue)
![Focus](https://img.shields.io/badge/focus-offline%20dev%20tools-green)

I build small, honest, fully offline developer tools - deterministic output, zero telemetry.

## Web tools

| Tool | What it does | Try it |
|---|---|---|
| **ReadmeScore** | Paste a README, get a 0-100 newcomer score + fix per check | [readmescore](https://qianbrady.github.io/readmescore/) |
| **PromptDriftCheck** | Did your new system prompt change the answers? Score the drift | [promptdriftcheck](https://qianbrady.github.io/promptdriftcheck/) |
| **WeeklyChangelog** | `git log` in, publish-ready weekly changelog out | [weeklychangelog](https://qianbrady.github.io/weeklychangelog/) |
| **LLMCostBoard** | Paste LLM usage JSONL → per-model/per-day API costs + budget alerts | [llmcostboard](https://qianbrady.github.io/llmcostboard/) |
| **TermTideWeb** | Paste numbers → gradient SVG charts (sparkline/heatmap/bars) | [termtideweb](https://qianbrady.github.io/termtideweb/) |

Each web tool is a faithful, test-verified port of its CLI sibling.

## CLI tools

- **Git & repo intelligence** - [commit-chronicle](https://github.com/qianbrady/commit-chronicle) · [gitscape](https://github.com/qianbrady/gitscape) · [gitflick](https://github.com/qianbrady/gitflick) · [repopitch](https://github.com/qianbrady/repopitch) · [repo-vital](https://github.com/qianbrady/repo-vital) · [maintainer-pulse](https://github.com/qianbrady/maintainer-pulse)
- **Code & review** - [stylecodex](https://github.com/qianbrady/stylecodex) · [undertest](https://github.com/qianbrady/undertest) · [blamewhen](https://github.com/qianbrady/blamewhen) · [callquake](https://github.com/qianbrady/callquake) · [dotenvelope](https://github.com/qianbrady/dotenvelope) · [jsonlcensus](https://github.com/qianbrady/jsonlcensus)
- **Terminal & sessions** - [termemory](https://github.com/qianbrady/termemory) · [termtide](https://github.com/qianbrady/termtide) · [termquill](https://github.com/qianbrady/termquill) · [timesink](https://github.com/qianbrady/timesink) · [gitgrave](https://github.com/qianbrady/gitgrave)
- **Prompts & LLM ops** - [promptwake](https://github.com/qianbrady/promptwake) · [promgit](https://github.com/qianbrady/promgit) · [tokenlattice](https://github.com/qianbrady/tokenlattice)
- **Docs & quality** - [readme-gauntlet](https://github.com/qianbrady/readme-gauntlet) (scores every README on this page) · [devstorymatrix](https://github.com/qianbrady/devstorymatrix)

## Install

```bash
git clone https://github.com/qianbrady/<repo>
cd <repo>
pip install -e .
```

## Quickstart

1. Pick any repo from the lists above
2. Clone and install (two commands)
3. Run `<tool> --help` - every CLI ships a help screen

## Usage

```bash
$ readme-gauntlet README.md
总分: 100/100  等级: A
```

## Contributing

Issues and PRs welcome in any repo - zero-dependency codebases, small surface areas.

## License

[MIT](https://opensource.org/licenses/MIT) © 2025 Brady
