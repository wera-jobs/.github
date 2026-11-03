# Contributing to Wera

Thanks for helping. This is the guide for all Wera repositories. A repository's own `CONTRIBUTING.md` adds its setup steps and takes priority where the two differ.

## Before you start

- For anything bigger than a small fix, open an issue first so we can agree on the approach.
- Report security problems privately. See the [security policy](SECURITY.md).

## How changes land

1. Branch from `dev`.
2. Make one change per pull request, split into atomic commits.
3. Open the pull request against `dev`. Merging to `main` and releases are done by maintainers.
4. Every check must pass before merging.

## Commits

Commits follow [Conventional Commits](https://www.conventionalcommits.org): `type(scope): subject`, with a lowercase imperative subject and no trailing period. The body says why the change was made.

```text
fix(fetch): retry boards that answer 429
```

Types: `feat`, `fix`, `perf`, `refactor`, `docs`, `test`, `ci`, `build`, `chore`.

## Quality

Run the repository's lint, type and test commands before you commit. Add a test with any behavior change. New user-facing text should be plain and specific: say what happens and what to do next.

## Data

Never use real user data in tests, fixtures, screenshots or issues. Use invented names and companies, and never put secrets in a commit.
