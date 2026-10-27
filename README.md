<!--
SEO: llm eval tracker
-->

<div align="center">

# LLM Eval Tracker

Live index of LLM evaluation tools and benchmarks, refreshed every 15 minutes from GitHub

[![Stars](https://img.shields.io/github/stars/linny006/llm-eval-tracker?style=for-the-badge&logo=github)](https://github.com/linny006/llm-eval-tracker/stargazers)
[![Last Commit](https://img.shields.io/github/last-commit/linny006/llm-eval-tracker?style=for-the-badge)](https://github.com/linny006/llm-eval-tracker/commits)
[![Items](https://img.shields.io/badge/Tracked_Items-12-brightgreen?style=for-the-badge)](#)
[![Updated](https://img.shields.io/badge/Updates-every_15min-blue?style=for-the-badge)](#)

**⭐ Star this repo to bookmark — fresh data every 15 minutes**

[English](./README.md) · [中文](./README_CN.md) · [日本語](./README_JA.md) · [한국어](./README_KO.md) · [Español](./README_ES.md) · [Português](./README_PT.md)

</div>

---

## 💡 What is this?

Automatically discovers and indexes new LLM evaluation frameworks, benchmarks, and harnesses as they appear on GitHub. Generates a structured, searchable catalog with metadata like stars, activity, and category tags. Designed for ML engineers who need to stay current without manually scanning repositories.

This list is **auto-updated every 15 minutes** by a GitHub Actions cron.
Each commit reflects a real change in the upstream data source — new items added,
expired items removed — so you can rely on what you see being current.

---

## 📋 Current Items

> ⏰ Last updated: 2026-10-27 12:30 UTC
>
> Data source: `GitHub Search API`
>
> The table below is rewritten on every cron tick. Star the repo to bookmark.

<!-- TRACKER_TABLE_START -->
| # | Name | ⭐ | Lang | Updated | Description |
|---|------|---|------|---------|-------------|
| 1 | [Sushant-Dagar/agent-eval-harness](https://github.com/Sushant-Dagar/agent-eval-harness) | 0 | Python | 2026-10-23 | CI-integrated eval harness for LLM agents — intent accuracy, retrieval precision/recall/MRR, and hallucination detection |
| 2 | [ChelseaKR/plumbline](https://github.com/ChelseaKR/plumbline) | 1 | Python | 2026-10-21 | v0.2.0. Fail-closed evaluation harness for government-facing chat systems: reproducible, provenance-stamped audit verdic |
| 3 | [multivon-ai/multivon-eval](https://github.com/multivon-ai/multivon-eval) | 26 | Python | 2026-09-21 | Practical LLM evaluation for teams that ship to production. Deterministic + LLM-as-judge evaluators, dataset support, CI |
| 4 | [valbaudo/awf](https://github.com/valbaudo/awf) | 1 | Go | 2026-09-21 | Run agents you don't babysit, and trust the result. awf runs agentic workflows with independent gates that check every s |
| 5 | [isatimur/mash-core](https://github.com/isatimur/mash-core) | 0 | Python | 2026-09-17 |  |
| 6 | [gmitt98/fieldtest](https://github.com/gmitt98/fieldtest) | 0 | Python | 2026-10-20 | LLM evaluation framework — define what correct, well-formed, and safe means before you measure |
| 7 | [camerontjs-dot/agent-eval-notes](https://github.com/camerontjs-dot/agent-eval-notes) | 0 | CSS | 2026-08-28 | Public-safe agent evaluation write-ups: harness gates, multi-path coding screens, task-family transfer, RAG routes, agen |
| 8 | [prompt-foundry/python-sdk](https://github.com/prompt-foundry/python-sdk) | 8 | Python | 2026-05-13 | The prompt engineering, prompt management, and prompt evaluation tool for Python |
| 9 | [SAY-5/eval-observability](https://github.com/SAY-5/eval-observability) | 0 | Python | 2026-05-10 | Python LLM eval framework with full OTel tracing, structured logs, and daily Welch's-t-test regression detection persist |
| 10 | [asarnaout/veritail](https://github.com/asarnaout/veritail) | 6 | Python | 2026-03-15 | LLM-as-a-Judge evaluation platform for ecommerce search. Scores relevance, computes IR metrics, and flags quality issues |
| 11 | [honeyhiveai/realign](https://github.com/honeyhiveai/realign) | 19 | Python | 2024-12-04 | Realign is a testing and simulation framework for AI applications. |
| 12 | [Re-Align/just-eval](https://github.com/Re-Align/just-eval) | 90 | Python | 2024-01-29 | A simple GPT-based evaluation tool for multi-aspect, interpretable assessment of LLMs. |
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

## 🔗 Related live trackers

If you find this useful, you might also like these other auto-updated
trackers from the same maintainer — same mechanism, different upstream:

- [trending-claude-skills](https://github.com/linny006/trending-claude-skills) — What's shipping in Claude Skills this week (`topic:claude-skills`)
- [mcp-servers-live](https://github.com/linny006/mcp-servers-live) — Live index of newest MCP servers (`topic:mcp-server`)
- [cursor-rules-live](https://github.com/linny006/cursor-rules-live) — Newest Cursor rules and .cursorrules patterns (`topic:cursor-rules`)
- [claude-code-plugin-tracker](https://github.com/linny006/claude-code-plugin-tracker) — Claude Code plugins and hook configs (`topic:claude-code`)
- [llm-agents-radar](https://github.com/linny006/llm-agents-radar) — Newest LLM agent frameworks (`topic:llm-agent`)
- [rag-radar](https://github.com/linny006/rag-radar) — Newest RAG implementations and tools (`topic:rag`)
- [agent-framework-radar](https://github.com/linny006/agent-framework-radar) — Newest agent frameworks shipping on GitHub (`topic:agent-framework`)
- [vector-db-live](https://github.com/linny006/vector-db-live) — Newest vector DB projects and integrations (`topic:vector-database`)
- [llmops-radar](https://github.com/linny006/llmops-radar) — Newest LLMOps tooling (observability, deployment) (`topic:llmops`)
- [prompt-tools-live](https://github.com/linny006/prompt-tools-live) — Newest prompt-engineering tools and prompt repos (`topic:prompt-engineering`)
- [agent-eval-harness](https://github.com/linny006/agent-eval-harness) — Live benchmark of AI coding agents (`topic:llm-eval`)
- [skills-tracker](https://github.com/linny006/skills-tracker) — Tracking new GitHub 'skills' repos (`topic:agent-skills`)
- [awesome-agent-skills](https://github.com/linny006/awesome-agent-skills) — Curated auto-updated awesome-list of AI agent skills (`topic:agent-skills`)

---

## 📜 License

MIT — see `LICENSE`.
