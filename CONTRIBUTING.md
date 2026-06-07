# Contributing to OpenSDEPrep

Thank you for considering a contribution. OpenSDEPrep is an open-source SDE interview prep resource and every improvement — from fixing a typo to adding a complete case study — is welcome.

## How content is organized

Content lives in **topic repos** (`lld`, `dsa`, `hld`, `behavioral`, `cs-fundamentals`), each created from the **[topic-template](https://github.com/OpenSDEPrep/topic-template)**. The authoritative authoring contract is [`topic-template/CLAUDE.md`](https://github.com/OpenSDEPrep/topic-template/blob/main/CLAUDE.md). Read it before writing any content.

The **aggregator site** ([opensdeprep.github.io](https://github.com/OpenSDEPrep/opensdeprep.github.io)) syncs from topic repos at build time. Site-level bugs and features belong in that repo.

## Before you start

- Check the open issues in the relevant repo to avoid duplicate work.
- For significant additions (new subtopics, new articles), open an issue first to align on scope.
- Keep your change focused — one article or one fix per pull request is ideal.

## Writing an article

Articles are Markdown files (`.md`) with frontmatter. They must not be named `README.md` — use a meaningful slug matching the folder name when a folder is required (e.g. `parking-lot/parking-lot.md`).

Required frontmatter:

```yaml
---
title: "Descriptive title"
topic: lld                         # topic repo this lives in
subtopic: case-studies             # must be a valid subtopic for this topic
roles: [backend]                   # backend | frontend | devops | ai-engineer
experience: [mid, senior]          # junior | mid | senior | staff
difficulty: medium                 # easy | medium | hard
tags: [oop, parking-lot]
status: published                  # draft | published
# Include the following when the article embeds code:
languages: [kotlin]
primary_language: kotlin
---
```

No emojis in article text. The site provides icons where they are needed.

## Embedding code

Code lives on disk as real files, not in fenced code blocks:

- `examples/<lang>/<stem>.<ext>` for concept examples
- `solutions/<lang>/<stem>.<ext>` for case-study solutions

Reference code in Markdown using the `:::code` and `:::solution` directives (site feature). Each code file should be standalone-runnable where practical.

## Pull request checklist

- [ ] Article is a meaningfully-named `.md` file (not `README.md`)
- [ ] Frontmatter is complete and valid
- [ ] Code files are under `examples/<lang>/` or `solutions/<lang>/`
- [ ] No emojis in content
- [ ] Internal links point to real slugs
- [ ] PR targets `main`

## Code of conduct

This project follows the [Contributor Covenant Code of Conduct](CODE_OF_CONDUCT.md). By participating you agree to abide by its terms.

## Questions

Open a [discussion](https://github.com/orgs/OpenSDEPrep/discussions) or file an issue in the relevant repo. For cross-repo questions use the [`.github` repo issues](https://github.com/OpenSDEPrep/.github/issues).
