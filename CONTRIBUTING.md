# Contributing to AETECH RESEARCH LABS LIMITED

Thank you for your interest in contributing to our projects! 🎉

AETECH RESEARCH LABS LIMITED is a full-spectrum technology organization — we do research, build production-ready enterprise applications, develop open-source tools, and engineer systems across AI/ML, software engineering, data science, cybersecurity, cloud infrastructure, hardware/IoT, and more.

This document provides guidelines for contributing to **any repository** under our organization. Individual repositories may have additional contribution guidelines — always check the repo-level `CONTRIBUTING.md` if it exists.

---

## 📋 Table of Contents

1. [Code of Conduct](#code-of-conduct)
2. [Getting Started](#getting-started)
3. [How to Contribute](#how-to-contribute)
4. [Development Workflow](#development-workflow)
5. [Commit Message Standards](#commit-message-standards)
6. [Pull Request Guidelines](#pull-request-guidelines)
7. [Reporting Bugs](#reporting-bugs)
8. [Requesting Features](#requesting-features)
9. [Research Contributions](#research-contributions)
10. [Style Guides](#style-guides)
11. [Recognition](#recognition)

---

## Code of Conduct

By participating in any AETECH RESEARCH LABS project, you agree to abide by our [Code of Conduct](CODE_OF_CONDUCT.md). Please read it before contributing.

---

## Getting Started

### Prerequisites

Before you begin, ensure you have:
- A [GitHub account](https://github.com/join)
- `git` installed locally
- The relevant language runtime/SDK for the project (see individual repo README)
- Familiarity with [GitHub Flow](https://docs.github.com/en/get-started/quickstart/github-flow)

### First-time setup

1. **Fork** the repository to your GitHub account
2. **Clone** your fork locally:
   ```bash
   git clone https://github.com/aetechlabs/<repo-name>.git
   cd <repo-name>
   ```
3. **Add the upstream remote:**
   ```bash
   git remote add upstream https://github.com/aetechlabs/<repo-name>.git
   ```
4. **Install dependencies** as described in the repository's README
5. **Create a branch** for your work (see [Development Workflow](#development-workflow))

---

## How to Contribute

There are many ways to contribute:

| Type | Description |
|------|-------------|
| 🐛 **Bug Fixes** | Fix reported issues or ones you discover yourself |
| ✨ **Features** | Implement new features from open issues |
| 🏢 **Enterprise Integrations** | Contribute connectors, adapters, or enterprise-grade enhancements |
| 📖 **Documentation** | Improve or add documentation, READMEs, or guides |
| 🧪 **Tests** | Add or improve test coverage |
| 🔬 **Research** | Contribute findings, datasets, or experimental results |
| 🌐 **Translations** | Help localize documentation |
| 🎨 **Design** | UI/UX improvements and assets |

> 💡 **Good first issues** are labeled `good first issue` — these are ideal starting points.

---

## Development Workflow

We follow **GitHub Flow**:

```
main (protected)
  └── feature/your-feature-name
  └── fix/issue-number-short-description
  └── docs/what-youre-documenting
  └── research/experiment-name
```

### Branch naming conventions

| Prefix | Use case |
|--------|----------|
| `feature/` | New features |
| `fix/` | Bug fixes |
| `docs/` | Documentation only changes |
| `refactor/` | Code refactoring without functional change |
| `test/` | Adding or fixing tests |
| `research/` | Research experiments or analysis |
| `chore/` | Maintenance tasks (deps, config, etc.) |

### Steps

1. Sync your fork with upstream:
   ```bash
   git fetch upstream
   git checkout main
   git merge upstream/main
   ```
2. Create your branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Make your changes with clear, focused commits
4. Push to your fork and open a Pull Request

---

## Commit Message Standards

We follow the **Conventional Commits** specification:

```
<type>(<scope>): <short summary>

[optional body]

[optional footer(s)]
```

### Types

| Type | Description |
|------|-------------|
| `feat` | A new feature |
| `fix` | A bug fix |
| `docs` | Documentation changes |
| `style` | Formatting, missing semicolons, etc. |
| `refactor` | Code restructuring without feature change |
| `test` | Adding or updating tests |
| `chore` | Build process or tooling changes |
| `research` | Research additions or experiment results |
| `perf` | Performance improvements |
| `ci` | CI/CD configuration changes |

### Examples

```
feat(auth): add OAuth2 login support
fix(api): resolve null pointer in user endpoint (#42)
docs(readme): update installation instructions
research(nlp): add baseline benchmark results for tokenizer
```

---

## Pull Request Guidelines

### Before opening a PR

- [ ] Your branch is up-to-date with `main`
- [ ] All tests pass locally
- [ ] New code includes appropriate tests
- [ ] Documentation is updated if needed
- [ ] Your code follows the project's style guide
- [ ] Commit messages follow our conventions

### PR checklist

When you open a PR, our template will guide you. Please:

1. **Write a clear title** using the conventional commit format
2. **Fill out the PR template** completely
3. **Link related issues** using `Closes #<issue-number>`
4. **Request a review** from at least one maintainer
5. **Respond to review feedback** promptly and constructively

### Review process

- PRs require **at least 1 approving review** from a maintainer
- All CI checks must pass
- Maintainers may request changes — this is normal and constructive
- Once approved, a maintainer will merge your PR

---

## Reporting Bugs

Use the **Bug Report** issue template in the relevant repository. Include:

- A clear, descriptive title
- Steps to reproduce the problem
- Expected vs. actual behavior
- Environment details (OS, language version, etc.)
- Relevant logs, screenshots, or error messages

> 🔒 **Security vulnerabilities** should **NOT** be reported as public issues. Please email [security@aetechlabs.com](mailto:security@aetechlabs.com) instead. See our [Security Policy](SECURITY.md).

---

## Requesting Features

Use the **Feature Request** issue template. Include:

- The problem you're trying to solve
- Your proposed solution
- Any alternatives you've considered
- Context about why this would benefit the project

---

## Research Contributions

For research-focused repositories, additional guidelines apply:

- **Reproducibility**: All experiments should include scripts or notebooks to reproduce results
- **Data**: Reference publicly available datasets where possible; document any custom datasets
- **Citations**: Properly cite prior work using BibTeX or the project's citation format
- **Notebooks**: Keep Jupyter notebooks clean and well-documented; clear all outputs before committing
- **Results**: Include a results table or summary in your PR description

---

## Style Guides

Each repository specifies its own style guide in its README or a `STYLE_GUIDE.md`. General principles:

- **Clarity over cleverness** — write code that others can read and maintain
- **Document public APIs** — all public functions/classes should have docstrings or JSDoc
- **Test what you build** — aim for meaningful test coverage, not just high percentages
- **Keep PRs focused** — one feature or fix per PR

---

## Recognition

All contributors are recognized in our repositories. Significant contributors may be invited to join as **Organization Members** or **Repository Maintainers**.

We value every contribution, no matter how small. Thank you for helping AETECH RESEARCH LABS LIMITED grow! 🚀

---

## Questions?

If you have questions not answered here, open a [Discussion](https://github.com/aetechlabs) in the relevant repository or reach out via the appropriate channel:

| Topic | Contact |
|-------|---------|
| Contributing & PRs | [contributing@aetechlabs.com](mailto:contributing@aetechlabs.com) |
| Research & experiments | [research@aetechlabs.com](mailto:research@aetechlabs.com) |
| GitHub & open source | [github@aetechlabs.com](mailto:github@aetechlabs.com) |
| Security issues | [security@aetechlabs.com](mailto:security@aetechlabs.com) |
| Bug reports | [bugs@aetechlabs.com](mailto:bugs@aetechlabs.com) |
| General / enterprise | [contact@aetechlabs.com](mailto:contact@aetechlabs.com) |
| Social (all platforms) | [@aetechlabs](https://x.com/aetechlabs) |

---

*Last updated: March 2026 · AETECH RESEARCH LABS LIMITED*
