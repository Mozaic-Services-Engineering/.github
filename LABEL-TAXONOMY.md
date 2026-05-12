# Label Taxonomy

Project fields should carry most workflow state. Labels should stay small, stable, and useful for cross-repo search.

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

- `blocked`
- `needs-human-review`
- `needs-shaping`
- `good-first-codex-task`
- `not-suitable-for-codex`

## Tracker-Only Labels

`mozaic-release-tracker` may keep tracker-specific labels where they still help with intake or governance, such as:

- `severity:*`
- temporary triage labels

## Avoid

- Do not use repo-specific `status:*` labels as the main workflow system.
- Use the project `Status` field instead.
- Do not introduce app labels where the project `Product/App` field already carries that meaning.
