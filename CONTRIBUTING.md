# Contributing to Veris

Thanks for your interest in contributing. This guide covers contributions to the community-maintained SDKs and example repositories.

## What you can contribute

- Bug fixes and error handling improvements
- Documentation improvements - clearer explanations, better examples, typo fixes
- New integration examples in `veris-examples`
- Platform-specific setup guides
- Translations of documentation

## Before you start

For non-trivial changes, open an issue first to discuss the approach. This avoids you spending time on a PR that won't be accepted.

For bug fixes, include a description of the bug and how your fix addresses it.

## Workflow

1. Fork the repository
2. Create a branch from `main`: `git checkout -b fix/your-description` or `feat/your-description`
3. Make your changes
4. Test against the example app
5. Commit with a clear message: `fix: correct nonce handling in startCapture`
6. Open a pull request against `main`

## Commit style

Follow [Conventional Commits](https://www.conventionalcommits.org/):

- `fix:` - bug fix
- `feat:` - new feature
- `docs:` - documentation only
- `chore:` - maintenance, dependency updates
- `refactor:` - code change that neither fixes a bug nor adds a feature

## Pull request checklist

- [ ] The change is tested and works against the example app
- [ ] Documentation is updated if public behaviour changed
- [ ] No new linting warnings

## Security issues

Do not open public issues for security vulnerabilities. See [SECURITY.md](SECURITY.md) for the responsible disclosure process.

## Questions

Open a GitHub Discussion if you have a question about the SDK or integration. For account or billing questions, contact hello@verisinfra.com.
