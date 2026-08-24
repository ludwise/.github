# Contributing

This file is the organisation-wide fallback. A repository with its own
`CONTRIBUTING.md` overrides it, and
[ludwise-web](https://github.com/ludwise/ludwise-web) does.

## Before you write code

Open an issue first for anything beyond a typo or an obvious fix. It is quicker
for both of us to agree on the approach than to review a branch built on a
different one.

## What a change needs

- A test that fails without it, for any change in behaviour.
- Conventional Commit messages — `feat:`, `fix:`, `docs:`, and so on.
- Green CI. Do not disable a check to get there.

## What is not accepted

Changes to the private backend, which is not public; and pull requests that add
a dependency without saying why the alternative was worse.
