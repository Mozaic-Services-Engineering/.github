# Engineering Operating Model

## Purpose

This organisation uses GitHub Issues plus the `Mozaic Engineering Backlog` project as the engineering source of truth for backlog management, sprint planning, implementation tracking, PR linkage, and delivery status.

SharePoint remains the business-facing intake layer. Engineering triage and execution happen in GitHub.

## Repo Roles

### `mozaic-release-tracker`

Use `mozaic-release-tracker` for:

- epics and programme work
- cross-repo initiatives
- governance and operating-model work
- parent issues
- intake where repo ownership is not yet clear

Do not use it as the default home for straightforward single-repo implementation work.

### Implementation repos

Use repo-local issues for:

- features
- bugs
- spikes
- technical debt
- repo-local operational work

These are the issues PRs should normally close.

## Project Rules

Use the org-level `Mozaic Engineering Backlog` project for:

- backlog visibility across the organisation
- sprint planning
- status tracking
- Codex-ready work selection

Project field expectations:

- `Status` tracks delivery stage.
- `Product/App` tracks the affected product or platform slice.
- `Sprint` is the sprint-planning field.
- `Priority` captures urgency.
- `Work Type` captures the main class of work.
- `Codex Ready` shows shaping and handoff readiness.
- `Source` records where the work originated.

## Sprint And Release Rules

- Use the `Sprint` iteration field for two-week sprint planning.
- Do not create fake sprint placeholders such as `TBC`.
- Leave unscheduled items blank.
- Use milestones for releases and go-live targets, not for sprint planning.

## Workflow

1. Capture or triage work.
2. Decide whether the work belongs in `mozaic-release-tracker` or an owning repo.
3. Link child repo issues to their tracker parent when applicable.
4. Add or keep the issue in `Mozaic Engineering Backlog`.
5. Track sprint, status, priority, and readiness in the project.
6. Link PRs back to the repo issue and relevant parent issue.

## Phase 0 Hygiene Rule

Before seeding large slices of historical work into the engineering backlog, review open tracker items for:

- already-delivered work
- stale or superseded work
- single-repo work that should be migrated
- genuine parent or cross-repo work that should remain in the tracker

Use PR evidence, comments, release history, and code evidence when issue state alone is unreliable.
