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

## Recent updates worth watching (September 2026)

- **More ways to request and configure Copilot code reviews.** A new personal
  settings page (available on all plans) lets you control when Copilot
  auto-reviews your pull requests and pick a default review effort (Lite or
  Balanced); organization admins can also set org-wide defaults. Useful if
  you want Copilot reviews tuned to your team's pace instead of the default
  behavior. (Source: GitHub Changelog, Sept 23, 2026 —
  https://github.blog/changelog/2026-09-23-copilot-code-review-more-ways-to-request-and-configure-reviews)

- **The Copilot coding agent runtime was rewritten in Rust — using Copilot
  itself.** GitHub migrated the agent runtime from Node.js to Rust across 128
  AI-authored pull requests, cutting session startup time by up to 18x and
  memory use by 91%. A good real-world example of using Copilot for a
  large-scale refactor. (Source: GitHub Blog, Sept 16–17, 2026 —
  https://github.blog/ai-and-ml/generative-ai/migrating-the-github-copilot-runtime-to-rust-using-copilot/)

- **Node 20 is no longer available in GitHub Actions.** Actions runners now
  require Node 24, and the `ACTIONS_ALLOW_USE_UNSECURE_NODE_VERSION` opt-out
  has been removed. If you maintain custom JavaScript actions, update
  `runs.using` to `node24` to avoid broken workflows. (Source: GitHub
  Changelog, Sept 23, 2026 —
  https://github.blog/changelog/2026-09-23-node-20-is-no-longer-available-in-github-actions)

- **Workflow execution protections in GitHub Actions are now generally
  available.** New allowlist controls let you restrict who and what can
  trigger workflows, backed by an audit dashboard and API. Starting Nov 2,
  2026, `pull_request_target` will be auto-disabled on public repos by
  default to help prevent "pwn request" style attacks — worth reviewing your
  workflows now. (Source: GitHub Changelog, Sept 17, 2026 —
  https://github.blog/changelog/2026-09-17-workflow-execution-protections-in-github-actions-generally-available)

- **Refreshed repository pull requests page is now generally available.** The
  redesigned PR list adds advanced filtering and search, a collapsible
  sidebar, a compact view mode, bulk actions, and richer PR metadata —
  making it easier to triage large volumes of pull requests. (Source: GitHub
  Changelog, Sept 21, 2026 —
  https://github.blog/changelog/2026-09-21-refreshed-repository-pull-requests-page-generally-available)

- **Developers want more efficient software.** A GitHub survey of over 1,000
  developers found strong demand for energy-efficiency tooling, and
  highlights GitHub's open-source "Daily Efficiency Improver" agentic
  workflow as one approach to reducing compute waste in everyday development.
  (Source: GitHub Blog, Sept 23, 2026 —
  https://github.blog/news-insights/research/developers-want-more-efficient-software-heres-what-over-1000-github-users-told-us-they-need/)
