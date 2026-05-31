# OpenSDEPrep

> Structured, open-source prep for software engineering interviews — from DSA to system design.

**OpenSDEPrep** is a curated, continuously-growing reference for SDE interview preparation. It started as a personal prep tracker and grew into a shareable, public resource. The goal is simple: one place that covers the full surface area of a modern SDE interview, organized so you can study by **topic**, **role**, **experience level**, and **difficulty**.

🔗 **Site:** [opensdeprep.github.io](https://opensdeprep.github.io) · built with [Astro](https://astro.build), hosted free on GitHub Pages.

---

## How it's organized

Content lives in **topic repos** — one per interview area. Each repo follows an identical structure (`content/` + `roadmaps/`) so the Astro site can sync and render everything automatically at build time.

| Topic | What's inside |
|-------|---------------|
| [`dsa`](https://github.com/OpenSDEPrep/dsa) | Data structures & algorithms — patterns, problems, complexity analysis |
| [`lld`](https://github.com/OpenSDEPrep/lld) | Low-level design — OOP principles, SOLID, design patterns, class diagrams, case studies |
| [`hld`](https://github.com/OpenSDEPrep/hld) | High-level design — distributed systems, databases, caching, messaging, API design |
| [`frontend`](https://github.com/OpenSDEPrep/frontend) | Frontend deep dives — JS/TS internals, browser internals, React internals, web performance |
| [`devops`](https://github.com/OpenSDEPrep/devops) | DevOps & SRE — CI/CD, containers, Kubernetes, cloud infra, observability |
| [`lang-runtime`](https://github.com/OpenSDEPrep/lang-runtime) | Language & runtime internals — Python, JVM, V8, memory models, concurrency, GC |
| [`site`](https://github.com/OpenSDEPrep/site) | The Astro site that renders, navigates, and filters all of the above |

## Study by what matters to you

Every article is tagged so you can filter the way you actually prepare:

- **Role** — backend · frontend · devops · ai-engineer
- **Experience** — junior · mid · senior · staff
- **Difficulty** — easy · medium · hard

**Roadmaps** then stitch these articles into ordered study paths — different cuts through the same content depending on your target role and level.

---

## Contributing

Each topic repo documents its own structure in a `CLAUDE.md` / `README.md` contract. The short version:

1. Pick the right topic repo and subtopic folder.
2. Add a Markdown article with the required frontmatter (`title`, `topic`, `subtopic`, `roles`, `experience`, `difficulty`, `tags`, `status`).
3. Optionally add it to a roadmap to place it in a study sequence.
4. Push to `main` — the site rebuilds and redeploys automatically.

---

<sub>Built and maintained in the open. If this helped you prep, ⭐ a repo and share it forward.</sub>
