# scorecard

Tiny eval harness: run prompt cases, score, compare

Side project, maintained when I have time.

## Examples

```bash
python evals.py
# edit cases.json, point run() at your agent
```

## Highlights

- Swap in any agent function via one line
- Keyword scoring + latency per case
- Cases defined in plain JSON
- Exit code usable as a CI gate

## Getting started

```bash
# stdlib only, nothing to install
```

## Project structure

```text
├── .github/
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── faq.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── .gitattributes
├── .gitignore
├── CHANGELOG.md
├── LICENSE
├── SECURITY.md
├── cases.json
└── evals.py
```

## License

MIT licensed, see LICENSE.
