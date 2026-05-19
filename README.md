<!--
SEO: llm eval tracker
-->

<div align="center">

# LLM Eval Tracker

Live index of LLM evaluation tools and benchmarks, refreshed every 15 minutes from GitHub

[![Stars](https://img.shields.io/github/stars/linny006/llm-eval-tracker?style=for-the-badge&logo=github)](https://github.com/linny006/llm-eval-tracker/stargazers)
[![Last Commit](https://img.shields.io/github/last-commit/linny006/llm-eval-tracker?style=for-the-badge)](https://github.com/linny006/llm-eval-tracker/commits)
[![Items](https://img.shields.io/badge/Tracked_Items-0-brightgreen?style=for-the-badge)](#)
[![Updated](https://img.shields.io/badge/Updates-every_15min-blue?style=for-the-badge)](#)

**⭐ Star this repo to bookmark — fresh data every 15 minutes**

</div>

---

## 💡 What is this?

Automatically discovers and indexes new LLM evaluation frameworks, benchmarks, and harnesses as they appear on GitHub. Generates a structured, searchable catalog with metadata like stars, activity, and category tags. Designed for ML engineers who need to stay current without manually scanning repositories.

This list is **auto-updated every 15 minutes** by a GitHub Actions cron.
Each commit reflects a real change in the upstream data source — new items added,
expired items removed — so you can rely on what you see being current.

---

## 📋 Current Items

> ⏰ Last updated: _pending first run_
>
> Data source: `GitHub Search API`
>
> The table below is rewritten on every cron tick. Star the repo to bookmark.

<!-- TRACKER_TABLE_START -->
_The first cron run will populate this section._
<!-- TRACKER_TABLE_END -->

---

## 🔍 How it works

Every 15 minutes, a GitHub Action runs `tracker.py`. That script:

1. Fetches the latest state from `GitHub Search API`.
2. Diffs against `data/items.json` (the previous snapshot).
3. Rewrites the table above between the `<!-- TRACKER_TABLE_* -->` markers.
4. Commits `feat: +N added, -M removed (timestamp)` if anything changed.

No external services. No paid APIs. Just a public data source and a free GitHub Action.

---

## 🤝 Contributing

See `CONTRIBUTING.md` — usually you don't need to: the tracker keeps itself current.
If you spot a data-source bug or want to suggest a new column for the table, open
an issue.

---

## 📜 License

MIT — see `LICENSE`.
