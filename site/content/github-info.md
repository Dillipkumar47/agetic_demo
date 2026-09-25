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

## Recent updates worth adding

- **Copilot code review has a clearer review experience.** The review timeline is
  easier to follow, stale suggestions auto-resolve, and Copilot can draft a commit
  message when you accept its edits. (GitHub Changelog, Sep 18, 2026:
  https://github.blog/changelog/2026-09-18-copilot-code-review-an-improved-review-experience)
- **More control over Copilot code review requests.** Personal configuration
  options are now available on more Copilot plans, and enterprises can set an
  org-wide default for review behavior. (GitHub Changelog, Sep 23, 2026:
  https://github.blog/changelog/2026-09-23-copilot-code-review-more-ways-to-request-and-configure-reviews)
- **The refreshed repository pull requests page is generally available.** The
  redesigned per-repo PR list makes it faster to find, filter, and act on open
  pull requests — worth a mention in the collaboration basics section. (GitHub
  Changelog, Sep 21, 2026:
  https://github.blog/changelog/2026-09-21-refreshed-repository-pull-requests-page-generally-available)
- **Workflow execution protections in GitHub Actions are GA.** Admins can set an
  allowlist controlling who is allowed to trigger workflow runs, cutting down
  CI/CD supply-chain risk. (GitHub Changelog, Sep 17, 2026:
  https://github.blog/changelog/2026-09-17-workflow-execution-protections-in-github-actions-generally-available)
- **Node 20 is no longer available in GitHub Actions.** JS actions now require
  Node 24 and the Node 20 opt-out flag no longer works, so update any pinned
  custom actions before they break. (GitHub Changelog, Sep 23, 2026:
  https://github.blog/changelog/2026-09-23-node-20-is-no-longer-available-in-github-actions)
- **Local sandboxing landed in the GitHub Copilot app.** A new per-project
  setting restricts Copilot's agent access to files, network, and credentials
  during local sessions — a good safety note for anyone trying agentic coding.
  (GitHub Changelog, Sep 23, 2026:
  https://github.blog/changelog/2026-09-23-local-sandboxing-in-the-github-copilot-app)
- **Rendering huge pull requests in the GitHub Copilot app.** An engineering
  deep dive on how GitHub reengineered diff rendering so the Copilot app can
  smoothly open million-line PRs with hundreds of comments. (GitHub Blog, Sep
  23, 2026:
  https://github.blog/engineering/user-experience/rendering-huge-pull-requests-in-the-github-copilot-app/)
