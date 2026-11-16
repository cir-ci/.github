<p align="center">
  <img src="assets/circi-logo.svg" width="96" height="96" alt="CirCI">
</p>

<h1 align="center">CirCI</h1>

<p align="center">
  Self-hosted visual regression testing: catch every unintended UI change before it ships.
</p>

<p align="center">
  <a href="https://circi.dev">Documentation</a> ·
  <a href="https://github.com/cir-ci/repo">Source</a> ·
  <a href="https://circi.dev/roadmap/">Roadmap</a> ·
  <a href="https://circi.dev/contributing/how-to-contribute/">Contributing</a>
</p>

---

CirCI takes the screenshots your tests already produce, compares them with the approved baselines,
and gives your team one place to review what changed: side by side, as a diff, or with a slider.
Approve or reject from the dashboard or right from the pull request, and CirCI reports the result
back as a status check.

- **Runs on your servers.** One Docker image, Postgres, and your own storage (local disk or S3).
- **Fits your CI.** A small CLI uploads from any CI; Vitest and Argos-compatible clients work too.
- **Built for reviewing.** An inbox, review requests, flaky-screenshot triage, comments on regions,
  keyboard shortcuts for everything, and live updates.
- **Talks to your tools.** GitHub, GitLab, Bitbucket, Slack, Linear, Jira and Figma.
- **Open source** under the [GNU GPL v3](https://github.com/cir-ci/repo/blob/main/LICENSE).

## Repositories

| Repository | What's in it |
| --- | --- |
| [`repo`](https://github.com/cir-ci/repo) | The server, worker, dashboard, CLI and test integrations |
| [`documentation`](https://github.com/cir-ci/documentation) | The documentation site at [circi.dev](https://circi.dev) |

## Made by Hilma

<p>
  <a href="https://www.hilma.tech">
    <img src="assets/hilma-logo-card.svg" width="264" alt="Hilma: tech for impact">
  </a>
</p>

CirCI is created by [Hilma](https://www.hilma.tech), tech for impact: high-tech built for the
good of society. We build it in the open: issues, ideas and pull requests are welcome. Start with the
[contributing guide](https://circi.dev/contributing/how-to-contribute/).
