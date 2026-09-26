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

- **Refreshed repository Pull Requests page is now GA.** The redesigned PR list view (better filtering and search for finding and acting on pull requests) has moved from preview to general availability. Practical takeaway: use the new filters to triage large PR backlogs faster.
  Source: [GitHub Changelog, Sept 21, 2026](https://github.blog/changelog/2026-09-21-refreshed-repository-pull-requests-page-generally-available)

- **Workflow execution protections in GitHub Actions are GA.** Organizations and repositories can now set allowlists controlling who or what can trigger workflows, and a new default rule disables `pull_request_target` on public repos to help prevent secret-exfiltration ("Pwn Request") attacks. Practical takeaway: review your workflow triggers, especially any using `pull_request_target`.
  Source: [GitHub Changelog, Sept 17, 2026](https://github.blog/changelog/2026-09-17-workflow-execution-protections-in-github-actions-generally-available)

- **More ways to request and configure Copilot code reviews.** Copilot code review settings are now available on all plans, including Business and Enterprise, with new controls for draft PRs, review effort level, and org-wide defaults. Practical takeaway: teams on any plan can now standardize how Copilot reviews PRs.
  Source: [GitHub Changelog, Sept 23, 2026](https://github.blog/changelog/2026-09-23-copilot-code-review-more-ways-to-request-and-configure-reviews)

- **GitHub Actions: early September 2026 updates.** A batch of smaller Actions improvements: an API to check for runner deprecations, a new least-privilege `vulnerability-alerts` token permission, and more job-context info for reusable workflows. Practical takeaway: tighten workflow token permissions using the new scoped `vulnerability-alerts` permission.
  Source: [GitHub Changelog, Sept 3, 2026](https://github.blog/changelog/2026-09-03-github-actions-early-september-2026-updates)

- **Local sandboxing in the GitHub Copilot app.** A new setting sandboxes Copilot's local agentic sessions, limiting file, network, and credential access. Practical takeaway: enable sandboxing when running Copilot agent sessions locally for an extra layer of safety.
  Source: [GitHub Changelog, Sept 23, 2026](https://github.blog/changelog/2026-09-23-local-sandboxing-in-the-github-copilot-app)

- **Rendering huge pull requests in the GitHub Copilot app.** An engineering deep-dive on how the Copilot app efficiently renders very large diffs, offering useful behind-the-scenes context for developers curious about Copilot's PR tooling internals.
  Source: [GitHub Blog (Engineering), Sept 23, 2026](https://github.blog/engineering/user-experience/rendering-huge-pull-requests-in-the-github-copilot-app/)
