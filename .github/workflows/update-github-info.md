---
name: update-github-info
description: Draft website updates for Mona's GitHub Info site from official GitHub sources.
on:
  workflow_dispatch:
  schedule:
    - cron: '17 9 * * *'
safe-outputs:
  create-pull-request:
    title-prefix: "[mona] "
    draft: true
    fallback-as-issue: false
tools:
  edit:
  web-fetch:
network:
  allowed:
    - github.com
    - github.blog
---

# Update Mona's GitHub Info website

Read `notes/mona-notes.md` before making changes.

Review these official sources:

- GitHub Blog: https://github.blog/latest/
- GitHub Changelog: https://github.blog/changelog/

Identify recent updates that are relevant to Mona's GitHub Info website. Draft
concise, practical changes for developers and include source context whenever an
update comes from the GitHub Blog or GitHub Changelog.

Only modify `site/content/github-info.md`. Do not change other website files,
workflow files, configuration, or generated assets.

Open a draft pull request for Mona to review using `safe-outputs` with
`create-pull-request`. The pull request should include a clear summary of the
sources reviewed, the updates proposed, and the reason each update is relevant.
Do not write directly to `main`; all proposed website changes must remain
available for human review before merging.