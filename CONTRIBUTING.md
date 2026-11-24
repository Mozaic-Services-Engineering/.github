# Contributing

## Source Of Truth

- SharePoint remains the business-facing intake layer.
- GitHub Issues and GitHub Projects are the engineering source of truth.
- Issue location, linking and format follow the
  [GitHub Issue and Project Operating Model](https://github.com/Mozaic-Services-Engineering/mozaic-platform-docs/blob/main/docs/engineering/operating-model/consultancy-on-tap/github-issue-and-project-operating-model.md)
  in `mozaic-platform-docs`. Where this page and that document differ, that
  document wins.

## Where To Create Work

Follow
[§5.1 Location Rules](https://github.com/Mozaic-Services-Engineering/mozaic-platform-docs/blob/main/docs/engineering/operating-model/consultancy-on-tap/github-issue-and-project-operating-model.md#51-location-rules)
and write the issue in the format for its Issue Type in
[§10 Issue Content Contracts](https://github.com/Mozaic-Services-Engineering/mozaic-platform-docs/blob/main/docs/engineering/operating-model/consultancy-on-tap/github-issue-and-project-operating-model.md#10-issue-content-contracts).

## Project Rules

- Add the issue to the GitHub Project that plans its work.
- Use the project's `Sprint` iteration field for sprint planning.
- Leave unscheduled items with no sprint instead of inventing a placeholder sprint.
- Use milestones for releases, go-live targets, and other delivery dates. Do not use milestones as sprint buckets.

## Linking Rules

- Use native parent, sub-issue and dependency links, as in
  [§7 Relationships And Dependencies](https://github.com/Mozaic-Services-Engineering/mozaic-platform-docs/blob/main/docs/engineering/operating-model/consultancy-on-tap/github-issue-and-project-operating-model.md#7-relationships-and-dependencies).
- PRs should link to the repo issue they implement.

## Codex Working Style

- Shape work clearly before marking it ready for execution.
- Keep acceptance criteria explicit and testable.
- Record risky follow-ons as new issues rather than expanding the active change without review.
