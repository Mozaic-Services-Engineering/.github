# Contributing

## Source Of Truth

- SharePoint remains the business-facing intake layer.
- GitHub Issues and GitHub Projects are the engineering source of truth.
- `mozaic-release-tracker` holds epics, programmes, governance work, cross-repo parent issues, and unclear-ownership intake.
- Repo-local issues hold single-repo implementation work.

## Where To Create Work

- Create the issue in the owning repo when the implementation repo is already clear.
- Create or use a parent issue in `mozaic-release-tracker` when the work is cross-repo, governance-focused, or ownership is unclear.
- Keep simple single-repo bugs in the owning repo unless they are part of a wider cross-repo incident.

## Project Rules

- Use `Mozaic Engineering Backlog` as the org-level engineering backlog and sprint-planning project.
- Use the `Sprint` iteration field for sprint planning.
- Leave unscheduled items with no sprint instead of inventing a placeholder sprint.
- Use milestones for releases, go-live targets, and other delivery dates. Do not use milestones as sprint buckets.

## Linking Rules

- Repo issues should reference the parent tracker issue when the work belongs to a broader initiative.
- PRs should link to the repo issue they implement.
- Where relevant, PRs should also reference the tracker parent for traceability.

## Codex Working Style

- Shape work clearly before marking it ready for execution.
- Keep acceptance criteria explicit and testable.
- Record risky follow-ons as new issues rather than expanding the active change without review.
