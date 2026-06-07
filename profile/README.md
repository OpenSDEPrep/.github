# OpenSDEPrep

> Structured, open-source prep for software engineering interviews — from DSA to system design.

**OpenSDEPrep** is a curated, continuously-growing reference for SDE interview preparation. It started as a personal prep tracker and grew into a shareable, public resource. The goal is one place that covers the full surface area of a modern SDE interview, organized so you can study by topic, role, experience level, and difficulty.

**Site:** [opensdeprep.github.io](https://opensdeprep.github.io) — built with [Astro](https://astro.build), hosted on GitHub Pages.

---

## How it is organized

Content lives in **topic repos** — one per interview area. Each repo follows an identical structure (`content/` + `roadmaps/`) so the site can sync and render everything automatically at build time.

| Topic | Status | What is inside |
|-------|--------|----------------|
| [`lld`](https://github.com/OpenSDEPrep/lld) | Live | Low-level design — OOP principles, SOLID, design patterns, class diagrams, case studies |
| `dsa` | Planned | Data structures and algorithms — patterns, problems, complexity analysis |
| `hld` | Planned | High-level design — distributed systems, databases, caching, messaging, API design |
| `behavioral` | Planned | Behavioral interviews — STAR method, common themes, frameworks |
| `cs-fundamentals` | Planned | CS fundamentals — OS, networking, concurrency, databases |

---

## Study by what matters to you

Every article is tagged so you can filter the way you actually prepare:

- **Role** — backend, frontend, devops, ai-engineer
- **Experience** — junior, mid, senior, staff
- **Difficulty** — easy, medium, hard

Roadmaps stitch these articles into ordered study paths — different cuts through the same content depending on your target role and level.

---

## Contributing

Content lives in topic repos, each created from the **[topic-template](https://github.com/OpenSDEPrep/topic-template)**. The authoring contract is documented in [`topic-template/CLAUDE.md`](https://github.com/OpenSDEPrep/topic-template/blob/main/CLAUDE.md).

The short version:

1. Pick (or request) the right topic repo.
2. Add a meaningfully-named Markdown article (not `README.md`) with the required frontmatter — `title`, `topic`, `subtopic`, `roles`, `experience`, `difficulty`, `tags`, `status`, and `languages`/`primary_language` when the article embeds code.
3. Place code under `examples/<lang>/` or `solutions/<lang>/` next to the article.
4. Push to `main` — the site rebuilds and redeploys automatically.

See [CONTRIBUTING.md](https://github.com/OpenSDEPrep/.github/blob/main/CONTRIBUTING.md) for full guidelines.

---

<sub>Built and maintained in the open. If this helped you prep, star a repo and share it forward.</sub>
