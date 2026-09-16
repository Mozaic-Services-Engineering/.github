# AGENTS.md

## Pull Request Review Governance

- Follow the [Independent PR Reviewer Agent Trial](https://github.com/Mozaic-Services-Engineering/mozaic-platform-docs/blob/main/docs/engineering/governance/independent-pr-reviewer-agent-trial.md) where this repository is in trial scope.
- Low and medium risk PRs may use an independent Pull Request Reviewer agent loop as merge evidence when the required evidence block is posted for the current head SHA.
- High-risk PRs still require named human approval. Treat auth, tenant isolation, secrets, IAM, workflow/policy, irreversible data, production release, evidence custody, and governed mutation/apply paths as high risk unless the policy says otherwise.
- Reviewer-agent sessions must use the [Pull Request Reviewer role](https://github.com/Mozaic-Services-Engineering/mozaic-platform-docs/blob/main/docs/engineering/roles/pr-reviewer.md) and review the actual current PR diff, not only the author summary.
