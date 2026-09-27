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

## Recent updates worth sharing

### GitHub Copilot

- **Local sandboxing in the GitHub Copilot app.** You can now restrict what an
  agent can touch during a local session — files, network calls, and stored
  credentials — so autonomous command execution carries less risk. It's
  configured per project inside the Copilot app, making it a quick safety net
  before letting Copilot run commands on your machine.
  Source: [GitHub Changelog, Sep 23, 2026](https://github.blog/changelog/2026-09-23-local-sandboxing-in-the-github-copilot-app)
- **Agentic autofix now uses Copilot Memory.** Security autofix for code
  scanning alerts now draws on prior Copilot Memory context, producing fixes
  that are more consistent with how your project is already structured. Worth
  knowing if your team relies on autofix suggestions to clear alerts faster.
  Source: [GitHub Changelog, Sep 25, 2026](https://github.blog/changelog/2026-09-25-agentic-autofix-now-uses-copilot-memory)
- **More ways to request and configure Copilot code reviews.** Personal and
  enterprise-default settings now give teams finer control over when and how
  Copilot reviews pull requests, which helps standardize AI-assisted review
  across an organization instead of leaving it ad hoc.
  Source: [GitHub Changelog, Sep 23, 2026](https://github.blog/changelog/2026-09-23-copilot-code-review-more-ways-to-request-and-configure-reviews)

### GitHub Actions

- **Workflow execution protections are now generally available.** Admins can
  allowlist who is allowed to trigger or modify workflow runs, which hardens
  CI/CD pipelines against malicious triggers — including from forked pull
  requests. A good check for any repo that runs Actions on external
  contributions.
  Source: [GitHub Changelog, Sep 17, 2026](https://github.blog/changelog/2026-09-17-workflow-execution-protections-in-github-actions-generally-available)
- **Control Actions cache access with `cache-mode`.** A new setting applies
  least-privilege scoping to cache read/write access per workflow or job,
  reducing the risk of cache-poisoning attacks in CI. Worth reviewing if your
  workflows rely heavily on shared caches.
  Source: [GitHub Changelog, Sep 10, 2026](https://github.blog/changelog/2026-09-10-control-github-actions-cache-access-with-cache-mode)

### Collaboration basics

- **Refreshed repository Pull Requests page (GA).** The pull request list view
  has been redesigned for easier filtering and triage, and it's now the
  default across all repos — handy for teams juggling many open PRs at once.
  Source: [GitHub Changelog, Sep 21, 2026](https://github.blog/changelog/2026-09-21-refreshed-repository-pull-requests-page-generally-available)
- **Block pull requests with exposed secrets from merging.** Repository
  rulesets can now hard-block a merge when a PR introduces a leaked secret,
  closing the gap between detecting a secret and actually stopping it from
  landing in the codebase.
  Source: [GitHub Changelog, Sep 9, 2026](https://github.blog/changelog/2026-09-09-block-pull-requests-with-exposed-secrets-from-merging)
- **Private saved views and "Relates to" issue linking (GA).** You can now save
  personal, persistent filter/sort views for repository issues, plus link
  related issues with a new non-hierarchical "Relates to" connection — useful
  for tracking related work without forcing a parent/child structure.
  Source: [GitHub Changelog, Sep 25, 2026](https://github.blog/changelog/2026-09-25-personal-saved-views-for-repository-issues-and-more)
