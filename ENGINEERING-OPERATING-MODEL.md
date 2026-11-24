# Engineering Operating Model

## Purpose

GitHub Issues and GitHub Projects are the engineering source of truth for
backlog management, sprint planning, implementation tracking, PR linkage and
delivery status.

SharePoint remains the business-facing intake layer. Engineering triage and
execution happen in GitHub.

## Canonical Rules

This repository holds organisation defaults only. Issue and project rules are
defined in the
[GitHub Issue and Project Operating Model](https://github.com/Mozaic-Services-Engineering/mozaic-platform-docs/blob/main/docs/engineering/operating-model/consultancy-on-tap/github-issue-and-project-operating-model.md)
in `mozaic-platform-docs`. Where this page and that document differ, that
document wins.

- Issue Types and hierarchy: §4 and §6.1.
- Where an issue lives:
  [§5.1 Location Rules](https://github.com/Mozaic-Services-Engineering/mozaic-platform-docs/blob/main/docs/engineering/operating-model/consultancy-on-tap/github-issue-and-project-operating-model.md#51-location-rules).
- Parent, child and dependency links:
  [§7 Relationships And Dependencies](https://github.com/Mozaic-Services-Engineering/mozaic-platform-docs/blob/main/docs/engineering/operating-model/consultancy-on-tap/github-issue-and-project-operating-model.md#7-relationships-and-dependencies).
- Title pattern, issue fields and ordered body headings:
  [§10 Issue Content Contracts](https://github.com/Mozaic-Services-Engineering/mozaic-platform-docs/blob/main/docs/engineering/operating-model/consultancy-on-tap/github-issue-and-project-operating-model.md#10-issue-content-contracts).

§10 is accepted and authoritative. The rest of that document, including the
project architecture in §8 and §9, is a target design; follow the live project
for the work until it is implemented.

## Projects

Add an issue to the GitHub Project that plans its work. The organisation's
projects are listed at
[github.com/orgs/Mozaic-Services-Engineering/projects](https://github.com/orgs/Mozaic-Services-Engineering/projects).

## Sprint And Release Rules

- Use the project's `Sprint` iteration field for sprint planning.
- Do not create fake sprint placeholders such as `TBC`.
- Leave unscheduled items blank.
- Use milestones for releases and go-live targets, not for sprint planning.
