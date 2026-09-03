# GitHub Info

## Mona's editorial angle

Mona's website focuses on practical GitHub guidance backed by official references from:

- docs.github.com
- github.blog
- github.blog/changelog

## Current homepage themes

- GitHub collaboration basics: repositories, branches, pull requests, and merges.
- GitHub Copilot as an AI coding assistant across the IDE, CLI, and GitHub.
- GitHub Actions as the automation layer behind repository workflows.
- Recent GitHub Blog and Changelog stories worth watching.

## Agentic workflows: automate GitHub with Copilot (new)

GitHub's [`awesome-copilot`](https://github.com/github/awesome-copilot) repo now ships ready-made **agentic workflow** templates — Markdown files that combine GitHub Actions triggers with Copilot-driven instructions to autonomously read, summarize, and act on repository data. Notable examples from `awesome-copilot/workflows/`:

- **Daily Issues Report** — runs on a weekday schedule and opens a GitHub issue summarizing new, closed, and stale issues from the last 24 hours.
- **OSPO Stale Repository Report** — scans an organization on a monthly cron (or on demand), flags repos with no push/commit activity past a configurable threshold, and files or updates a Markdown report issue with a sortable staleness table.
- **OSPO Contributors Report / Org Health / Release Compliance Checker** — similar cron-driven agents that audit contributor activity, overall org health signals, and release process compliance.
- **Relevance Check / Relevance Summary / Weekly Comment Sync** — workflows that keep issue/discussion content current and synchronized across repos.

**Why it matters:** these workflows show a practical pattern for readers — define `on:` triggers, `permissions:`, and a `safe-outputs:` block (e.g., `create-issue`) in frontmatter, then write plain-language instructions for the agent. It's a low-code way to add recurring, AI-generated reports to any repo. Browse the full catalog at [awesome-copilot.github.com/workflows](https://awesome-copilot.github.com/workflows/).

*Source: [github.com/github/awesome-copilot](https://github.com/github/awesome-copilot), `workflows/` directory (accessed via GitHub repository contents).*

> Note: GitHub Blog (github.blog/latest) and GitHub Changelog (github.blog/changelog) were unreachable from this workflow run, so no new posts from those sources are summarized here this update. Once network access is available, add their latest headlines with source links per Mona's notes.
