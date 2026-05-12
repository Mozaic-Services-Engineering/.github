# Issue Hierarchy And Linking

## Core Rule

Keep parent coordination work in `mozaic-release-tracker`. Keep implementation work in the repo where the code or operational change actually happens.

## Parent Issue Types

Use `mozaic-release-tracker` for:

- epics
- programmes
- governance work
- cross-repo initiatives
- unclear-ownership intake

## Child Issue Types

Use repo-local issues for:

- feature delivery
- bug fixes
- research or spikes
- technical debt
- repo-local operational tasks

## Linking Pattern

1. Create or identify the parent tracker issue when the work is cross-repo or programme-level.
2. Create child implementation issues in the owning repos.
3. Add the parent and child issues to `Mozaic Engineering Backlog`.
4. Link PRs to the repo issue.
5. Reference the parent tracker issue from the repo issue and PR where relevant.

## Migration Rule

If an existing tracker issue is actually active single-repo work:

1. Create the new repo issue.
2. Copy the useful summary, acceptance criteria, and links.
3. Add an evidence note explaining what was checked.
4. Close the tracker issue with a final link to the new repo issue.
