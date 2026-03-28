# AETECH RESEARCH LABS LIMITED — `.github` Repository

This is the **organization-wide `.github` repository** for [@aetechlabs](https://github.com/aetechlabs). It provides default community health files, issue/PR templates, reusable workflow templates, and organization-level documentation that apply across **all repositories** in the organization.

---

## 📁 Repository Structure

```
.github/
├── profile/
│   └── README.md                    # 🏛️  Organization public profile (shown on GitHub org page)
│
├── ISSUE_TEMPLATE/
│   ├── config.yml                   # Template chooser configuration
│   ├── bug_report.yml               # 🐛  Bug report template
│   ├── feature_request.yml          # ✨  Feature request template
│   ├── research_proposal.yml        # 🔬  Research proposal template
│   └── documentation.yml           # 📖  Documentation issue template
│
├── workflow-templates/
│   ├── python-ci.yml                # 🐍  Python CI (lint, test, security)
│   ├── python-ci.properties.json
│   ├── node-ci.yml                  # 🟨  Node.js CI (lint, test, build)
│   ├── node-ci.properties.json
│   ├── release.yml                  # 🏷️   Semantic release workflow
│   ├── release.properties.json
│   ├── codeql.yml                   # 🔒  CodeQL security scanning
│   └── codeql.properties.json
│
├── PULL_REQUEST_TEMPLATE.md         # 🔀  Default PR template
├── CODE_OF_CONDUCT.md               # 📜  Community Code of Conduct
├── CONTRIBUTING.md                  # 🤝  Contribution guidelines
├── SECURITY.md                      # 🔐  Security policy & disclosure process
├── FUNDING.yml                      # 💰  Sponsorship configuration
├── dependabot.yml                   # 🤖  Default Dependabot configuration
└── README.md                        # 📄  This file
```

---

## 🌐 How GitHub Uses This Repository

GitHub automatically applies files from this repository as **defaults** for any repository in the organization that does **not** have its own version of that file:

| File | Effect |
|------|--------|
| `profile/README.md` | Displayed on the organization's GitHub profile page |
| `CODE_OF_CONDUCT.md` | Default code of conduct for all repos |
| `CONTRIBUTING.md` | Default contributing guide for all repos |
| `SECURITY.md` | Default security policy for all repos |
| `ISSUE_TEMPLATE/` | Default issue templates for all repos |
| `PULL_REQUEST_TEMPLATE.md` | Default PR template for all repos |
| `workflow-templates/` | Reusable workflows available to all repos in the org |
| `FUNDING.yml` | Sponsor button configuration |

> ⚠️ **Repository-level files take precedence.** If a repository has its own `CONTRIBUTING.md`, `SECURITY.md`, etc., those will be used instead of the defaults here.

---

## ✏️ Making Changes

Changes to this repository affect the entire organization. Please follow these guidelines:

1. **Open an issue** before making significant changes
2. **Create a branch** and open a PR — do not push directly to `main`
3. **Tag `@aetechlabs/maintainers`** for review
4. Changes to `SECURITY.md` or `CODE_OF_CONDUCT.md` require **maintainer approval**

---

## 🔗 Quick Links

| Resource | Link |
|----------|------|
| Organization Profile | [github.com/aetechlabs](https://github.com/aetechlabs) |
| Security Reports | [security@aetechlabs.com](mailto:security@aetechlabs.com) |
| Bug Reports | [bugs@aetechlabs.com](mailto:bugs@aetechlabs.com) |
| Research Inquiries | [research@aetechlabs.com](mailto:research@aetechlabs.com) |
| GitHub & Open Source | [github@aetechlabs.com](mailto:github@aetechlabs.com) |
| Contributing Help | [contributing@aetechlabs.com](mailto:contributing@aetechlabs.com) |
| Enterprise / Business | [contact@aetechlabs.com](mailto:contact@aetechlabs.com) |
| Org Discussions | [GitHub Discussions](https://github.com/orgs/aetechlabs/discussions) |
| Social (all platforms) | [@aetechlabs](https://x.com/aetechlabs) |

---

*Maintained by the AETECH RESEARCH LABS LIMITED core team · Last updated March 2026*
