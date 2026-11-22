# Contributing

Thank you for your interest in Cyber ICE Box. This is the default guide for every repository of the organization. If a repository has its own `CONTRIBUTING.md`, that one wins.

## Report a bug

Open an issue in the repository the problem belongs to (see [SUPPORT.md](SUPPORT.md) for which repository is what) and fill in the bug report form: the version, what happened, what you expected, the steps to reproduce and the logs. Remove passwords, tokens and keys from logs before you paste them.

Do not report a vulnerability in a public issue. Follow [SECURITY.md](SECURITY.md).

## Propose a change

For a new feature or a larger change, open an issue first with the feature request form, so the idea can be discussed before you write code. Small fixes (typos, a clear bug) can go straight to a pull request.

## Branches and releases

Work goes into `develop` through a pull request, and the pull request merges when its checks are green. Releases are cut from the release lines by the maintainers; a contributor never tags or releases.

## Commits and pull requests

- Create a feature branch from `develop`; do not push to `develop` or `main`.
- Commit messages are plain English. Every commit must be signed.
- Everything in a repository (README, comments, docs, commit messages) is in English. User-facing text of the products goes through the i18n messages of the app.
- Run the checks of the repository before you open the pull request; the repository's `CONTRIBUTING.md` or `mise tasks` tell which ones.
- Never commit secrets: keys, tokens, passwords, `.env` files.

## Code of conduct

By taking part you agree to follow the [Code of Conduct](CODE_OF_CONDUCT.md). Licence: Apache-2.0.
