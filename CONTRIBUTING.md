# Contributing to Kongqr

## Commit messages

Kongqr repositories use concise, imperative commit messages in this format:

```text
<type>(<optional-scope>): <description>
```

The scope is optional, so both of these are valid:

```text
feat: add workflow approvals
feat(auth): add role-based access control
```

Use one of these types:

- `init` — initial scaffolding or foundational setup
- `feat` — a new user-facing capability
- `fix` — a bug fix
- `docs` — documentation only
- `refactor` — code changes without a feature or fix
- `test` — tests only
- `build` — dependencies or build tooling
- `ci` — continuous integration and deployment
- `chore` — routine maintenance
- `perf` — performance improvements
- `revert` — reverting an earlier commit

Keep the description lowercase, imperative, and without a trailing period. Add `!` before the colon and a `BREAKING CHANGE:` footer when a commit is incompatible with existing behavior.
