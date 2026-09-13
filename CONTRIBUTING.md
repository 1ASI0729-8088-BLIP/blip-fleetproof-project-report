# Contribution Guide

## Branches

- `main`: initial report template and approved delivery versions.
- `develop`: integrated work for next delivery.
- `feature/sprint1-<scope>`: report contribution for AV1, created from `develop`.
- `feature/usXXX-<short-name>`: software feature linked to one User Story.
- `release/vX.Y.Z`: release stabilization; create only when preparing a delivery.
- `hotfix/<short-name>`: urgent correction over released version.

## Commit Messages

Use Conventional Commits:

- `docs: add lean ux problem statement`
- `docs: update competitive analysis`
- `feat: implement landing page hero`
- `fix: correct landing page accessibility labels`
- `chore: organize report assets`

## Pull Requests

Report contributions target `develop`. For example, `feature/sprint1-capitulo-2`
contains the Chapter II contribution. Create branches when work starts, not merely
to list participants. A published branch is visible to anyone with repository read
access. A branch name does not create Sprint Planning or a Sprint Backlog.

Each Pull Request must include:

- Related section or User Story.
- Screenshots or evidence when applicable.
- Checklist against rubric criteria.
- Reviewer approval before merge.

## Markdown Rules

- Use English for product UI terms when required by the course.
- Use correct Spanish engineering terms: requisito, aplicación, despliegue, pruebas.
- Review the official terminology from Annex E before every Pull Request.
- Keep chapter evidence in `docs/assets/chapter-<n>/` and use relative Markdown links.

## Rubric Review Before Merge

Before merging any Pull Request, the reviewer must verify:

- The edited content follows the official report structure.
- The text uses correct software engineering terminology.
- The evidence is traceable through branch, commit, Pull Request and merge.
- Screenshots and links match the section where they are cited.
- The content includes no informal class slang in formal report sections.
