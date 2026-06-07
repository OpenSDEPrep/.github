# OpenSDEPrep

A personal SDE interview prep tracker — notes, patterns, and worked examples across the topics that actually come up. Kept in the open in case it is useful to anyone else.

**Site:** [opensdeprep.github.io](https://opensdeprep.github.io)

---

## What is here

Notes are split into topic repos so each area stays focused. The site pulls them together into one place.

| Topic | Status | What is inside |
|-------|--------|----------------|
| [`lld`](https://github.com/OpenSDEPrep/lld) | Active | Low-level design — OOP, SOLID, design patterns, class diagrams, case studies |
| `dsa` | Planned | Algorithms and data structures — patterns, complexity, worked problems |
| `hld` | Planned | System design — distributed systems, databases, caching, messaging |
| `behavioral` | Planned | Behavioral — STAR stories, common themes |
| `cs-fundamentals` | Planned | OS, networking, concurrency, databases |

Each article carries metadata (`roles`, `experience`, `difficulty`) so you can filter down to what is relevant for the specific role and level you are targeting.

---

## Adding notes

Topic repos follow a shared structure (see [topic-template](https://github.com/OpenSDEPrep/topic-template)). The short version: add a Markdown file with frontmatter, put code under `examples/<lang>/` or `solutions/<lang>/`, push — the site rebuilds automatically.

See [CONTRIBUTING.md](https://github.com/OpenSDEPrep/.github/blob/main/CONTRIBUTING.md) for the full authoring guide.
