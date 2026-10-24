# Contributing

Keep changes focused, simple, and easy to review. Follow the repository's existing structure and instructions. Discuss larger changes with the maintainers before starting work.

## Issues

For bugs, include reproduction steps, expected and actual behavior, and relevant version or environment details. For feature requests, explain the problem and the result you need.

Keep credentials, personal data, and confidential client information out of issues, pull requests, logs, and screenshots. Report security vulnerabilities using [SECURITY.md](SECURITY.md).

## Pull requests

- Explain the problem and how the change addresses it.
- Avoid unrelated refactoring and new dependencies without a clear need.
- Describe the verification performed and any checks still needed.
- Highlight breaking changes, migrations, and deployment requirements when applicable.

For public repositories, check the project's contribution and licensing terms before submitting changes. For private repositories, follow the team's agreed review and delivery process.

## Commit messages

Write commit messages in English using Conventional Commits:

```text
feat(api): add project listing endpoint
fix(auth): handle expired sessions
docs(repo): update setup instructions
```

Mark breaking changes with `!` after the scope. Explain the impact and required adjustment in the commit body:

```text
feat(api)!: rename task assignees response field

BREAKING CHANGE: replace assigned_users with assignees in API clients.
```
