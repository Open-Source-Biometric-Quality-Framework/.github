# Contributing to OpenBQ

Thank you for your interest in contributing to OpenBQ, the Open Source Biometric Quality Framework. This guide applies to all repositories in the [Open-Source-Biometric-Quality-Framework](https://github.com/Open-Source-Biometric-Quality-Framework) organisation, unless a repository has its own CONTRIBUTING.md.

## Ways to contribute

- Report bugs and request features through GitHub Issues
- Improve documentation at [docs.openbq.io](https://docs.openbq.io)
- Submit fixes and new features through pull requests
- Share feedback on quality metrics, modalities and integrations

## Reporting issues

Before opening an issue, search existing issues to avoid duplicates. Please include:

- The repository and version you are using
- Your operating system and environment (e.g. Python version, Docker)
- Steps to reproduce the problem
- Expected and actual behaviour, with logs or screenshots where helpful

**Security vulnerabilities:** do not open a public issue. Report them privately to [SECURITY CONTACT EMAIL].

## Making changes

1. Fork the repository and clone your fork.
2. Create a branch from `main` with a descriptive name, e.g. `fix/fingerprint-threshold` or `docs/install-guide`.
3. Make your changes, following the existing code style of the repository.
4. Add or update tests and documentation where relevant.
5. Commit with a sign-off (see below) and push to your fork.
6. Open a pull request against `main` and describe what changed and why. Link any related issues.

A maintainer will review your pull request. You may be asked to make changes before it is merged.

## Developer Certificate of Origin (DCO)

All contributions must be signed off under the [Developer Certificate of Origin 1.1](https://developercertificate.org/). By signing off, you confirm that you wrote the contribution or otherwise have the right to submit it under the project's open source licence.

Sign off each commit by adding the `-s` flag:

```bash
git commit -s -m "Describe your change"
```

This adds a line to your commit message:

```
Signed-off-by: Your Name <your.email@example.com>
```

The name and email must match your Git configuration. Pull requests containing commits without a sign-off cannot be merged.

To add a sign-off to your last commit:

```bash
git commit --amend -s
```

## Licensing

OpenBQ is licensed under the [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0) (SPDX: Apache-2.0). By contributing, you agree that your contributions are licensed under the same licence. You keep the copyright to your contributions.

Third-party components keep their own licences, as listed in each repository.

## Ownership

OpenBQ is developed and maintained by Biometix Pty Ltd (ABN 28 084 921 933). Maintainers from Biometix review and approve all changes.

## Questions

For questions, open a GitHub Discussion or Issue, or contact [CONTACT EMAIL].
