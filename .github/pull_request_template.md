## Summary

## Linked Repo Issue

## Linked Parent / Epic

## Verification

## Release / Rollback Notes

<!-- mozaic-independent-pr-reviewer-agent-policy -->
## Independent PR Review Policy

- [ ] Risk classified as `low`, `medium`, or `high`.
- [ ] High-risk areas checked against `.mozaic/pr-risk.yml` and the [Independent PR Reviewer Agent Policy](https://github.com/Mozaic-Services-Engineering/mozaic-platform-docs/blob/main/docs/engineering/governance/independent-pr-reviewer-agent-policy.md).
- [ ] If this is low/medium risk and in policy scope, an independent Pull Request Reviewer agent may provide merge-ready evidence for the current head SHA.
- [ ] If this is high risk, named human approval is required in addition to any reviewer-agent evidence.

Reviewer-agent evidence, when used, should be posted on the PR using the policy evidence block and must include the reviewed head SHA, risk level, checks/evidence, findings, and disposition.

The required `policy-audit / policy-audit` check validates this evidence against
the live PR. Re-run review after every material new commit; do not use admin
bypass for missing or stale evidence.
