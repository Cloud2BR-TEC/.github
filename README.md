# .github (TEC Org Profile + Community Health)

[![GitHub](https://img.shields.io/badge/--181717?logo=github&logoColor=ffffff)](https://github.com/)
[Cloud2BR](https://github.com/Cloud2BR)

Last updated: 2026-07-21

----------

> This repository contains the public GitHub organization profile for the Technology Education Center (TEC) by Cloud2BR, plus shared community health files used across repositories.

## What this repository is for

- Org profile hub: `profile/README.md` is shown on the Cloud2BR organization profile page.
- Community standards: issue templates, pull request templates, and policy files live here for organization-wide reuse.
- Visitor metrics automation (optional): a workflow refreshes the profile view badge and updates `metrics.json`.

## How to update content

- Update public organization messaging: edit `profile/README.md`.
- Update shared templates and policies: edit the related files in this repository.

## Visitor counter setup

- Add a repository secret named `TRAFFIC_TOKEN`.
  - The token must be able to read repository traffic insights for this repository.
- Run from GitHub: Actions -> Update view counter -> Run workflow.

> [!NOTE]
> - The workflow generates the badge and rewrites `metrics.json`.
> - Avoid manual edits to `metrics.json`; workflow runs will overwrite it.

<!-- START BADGE -->
<div align="center">
  <img src="https://img.shields.io/badge/Total%20views-10-0A66C2" alt="Total views">
  <p>Refresh Date: 2026-07-21</p>
</div>
<!-- END BADGE -->
