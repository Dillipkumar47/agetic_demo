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

## Recent updates worth watching

### GitHub Copilot

- **Ask Copilot to increase your usage budget.** When you hit your Copilot
  usage limit, you can now request more budget without leaving Copilot, and
  admins can approve, adjust, or deny the request in place. Handy for teams
  managing Copilot costs at scale.
  ([GitHub Changelog](https://github.blog/changelog/2026-09-16-copilot-budget-increase-requests-are-generally-available))
- **Tune cost vs. quality in Copilot's model picker.** Copilot's automatic
  model selection now offers efficiency, balanced, and intelligence tiers, so
  you can choose the right tradeoff per prompt instead of relying on a
  black-box default.
  ([GitHub Changelog](https://github.blog/changelog/2026-09-14-configure-cost-and-quality-in-copilot-auto-model-selection))
- **Copilot code review can now auto-resolve its own comments.** Once a
  suggestion is addressed, Copilot resolves the comment and writes clearer
  commit messages for applied fixes, cutting down on PR review back-and-forth.
  ([GitHub Changelog](https://github.blog/changelog/2026-09-11-auto-resolution-and-analysis-updates-in-copilot-code-review))
- **See VS Code agent activity in Copilot usage metrics.** Admins get better
  visibility into how AI agents are actually being used in the editor, right
  alongside other Copilot usage data.
  ([GitHub Changelog](https://github.blog/changelog/2026-09-11-add-vs-code-agents-to-copilot-usage-metrics))

### GitHub Actions

- **Lock down Actions cache access with `cache-mode`.** A new setting lets
  teams enforce least-privilege access to the Actions cache per workflow or
  job, reducing the risk of cache poisoning in CI pipelines.
  ([GitHub Changelog](https://github.blog/changelog/2026-09-10-control-github-actions-cache-access-with-cache-mode))

### Collaboration and general product

- **A refreshed pull requests page is in public preview.** The repo-level PR
  list has improved filtering and browsing, making it easier to triage open
  work — a good moment to revisit any "how pull requests work" guidance.
  ([GitHub Changelog](https://github.blog/changelog/2026-09-10-refreshed-repository-pull-requests-page-in-public-preview))
- **AI-driven vulnerability scanning for pull requests, via API.** GitHub
  Advanced Security's new "AI Scan" API support lets teams programmatically
  integrate AI-driven scanning into their PR checks.
  ([GitHub Changelog](https://github.blog/changelog/2026-09-10-ai-scan-for-pull-request-apis-in-public-preview))
