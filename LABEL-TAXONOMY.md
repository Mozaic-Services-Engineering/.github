# Label Taxonomy

Project fields should carry most workflow state. Labels should stay small, stable, and useful for cross-repo search.

The native Issue Type is the authority for an issue's type, and the title follows the pattern in
[§10.2](https://github.com/Mozaic-Services-Engineering/mozaic-platform-docs/blob/main/docs/engineering/operating-model/consultancy-on-tap/github-issue-and-project-operating-model.md#102-title-pattern).
`type:*` labels are optional search aids and never replace the Issue Type.

The Priority Issue Field is the authority for priority, including Bug severity
([§6.2](https://github.com/Mozaic-Services-Engineering/mozaic-platform-docs/blob/main/docs/engineering/operating-model/consultancy-on-tap/github-issue-and-project-operating-model.md#62-canonical-issue-fields), [§10.7](https://github.com/Mozaic-Services-Engineering/mozaic-platform-docs/blob/main/docs/engineering/operating-model/consultancy-on-tap/github-issue-and-project-operating-model.md#107-bug)).
`priority:*` and `severity:*` labels are transitional: they may be applied for
search, but they are never the source of priority or severity.

## Org-Wide Baseline

### Type

- `type:bug`
- `type:feature`
- `type:tech-debt`
- `type:security`
- `type:infra`
- `type:ux`
- `type:governance`
- `type:documentation`
- `type:testing`
- `type:research`

### Priority

Transitional search aids only; the Priority Issue Field is the authority.

- `priority:p1`
- `priority:p2`
- `priority:p3`
- `priority:p4`

### Area

- `area:frontend`
- `area:backend`
- `area:database`
- `area:auth`
- `area:ai`
- `area:cicd`
- `area:reporting`
- `area:observability`
- `area:sharepoint`
- `area:powerbi`
- `area:docs`

### Coordination

These are search aids only. Native blocked-by links are the authority for
dependencies ([§7](https://github.com/Mozaic-Services-Engineering/mozaic-platform-docs/blob/main/docs/engineering/operating-model/consultancy-on-tap/github-issue-and-project-operating-model.md#7-relationships-and-dependencies)),
and the Delivery readiness Issue Field is the authority for readiness. The
`*-codex-*` labels are legacy and runtime-specific; do not apply them to new issues.

- `blocked`
- `needs-human-review`
- `needs-shaping`
- `good-first-codex-task`
- `not-suitable-for-codex`

## Tracker-Only Labels

`mozaic-release-tracker` may keep tracker-specific labels where they still help with intake or governance, such as:

- `severity:*` (transitional; see the Priority note above)
- temporary triage labels

## Avoid

- Do not use repo-specific `status:*` labels as the main workflow system.
- Use the project `Status` field instead.
- Do not introduce app labels where a project field already carries that meaning.
