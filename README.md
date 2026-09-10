# scorecard

Minimal regression tests for my prompts

Started as a weekend hack, grew on me.

## Usage

```bash
python evals.py
# edit cases.json, point run() at your agent
```

## Features

- Keyword scoring + latency per case
- Cases defined in plain JSON
- Exit code usable as a CI gate
- Swap in any agent function via one line

## Install

```bash
# stdlib only, nothing to install
```

## Project structure

```text
├── .github/
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── configuration.md
│   ├── faq.md
│   └── usage.md
├── .gitignore
├── CONTRIBUTING.md
├── LICENSE
├── cases.json
└── evals.py
```

## Development

```bash
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
```

## Notes

- mostly stable, edge cases remain

## License

MIT. Do whatever you want.
