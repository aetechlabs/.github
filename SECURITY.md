# Security Policy — AETECH RESEARCH LABS LIMITED

## Our Commitment

AETECH RESEARCH LABS LIMITED takes the security of our software, research systems, and data seriously. We appreciate the efforts of security researchers and the broader community in helping us maintain a safe and secure environment.

If you believe you have found a security vulnerability in any repository owned by our organization, we encourage you to report it to us responsibly.

---

## Supported Versions

Security updates are applied to the following release types across our repositories:

| Version Type | Supported |
|---|---|
| Latest stable release | ✅ Yes |
| Previous major release (within 12 months) | ✅ Yes |
| Older major releases | ❌ No |
| Pre-release / alpha / beta | ⚠️ Best effort |
| Research prototypes / experimental branches | ❌ No (use at your own risk) |

> Individual repositories may define their own supported version matrix. Check the repository's `SECURITY.md` for specifics.

---

## Reporting a Vulnerability

> ⚠️ **Please do NOT report security vulnerabilities through public GitHub issues, discussions, or pull requests.**

### Preferred Method: Private Security Advisory

1. Navigate to the **affected repository** on GitHub
2. Click the **"Security"** tab
3. Select **"Report a vulnerability"**
4. Fill in the advisory form with as much detail as possible

### Alternative: Email

If you cannot use the GitHub advisory system, email us directly:

📧 **[security@aetechlabs.com](mailto:security@aetechlabs.com)**

Please use the subject line: `[SECURITY] <short description>`

Optionally, encrypt your message using our PGP key (available on request).

---

## What to Include in Your Report

To help us triage and respond quickly, please include:

- **Description**: A clear description of the vulnerability
- **Impact**: What an attacker could achieve by exploiting it
- **Affected component**: Repository name, file, function, or endpoint
- **Steps to reproduce**: A minimal, reliable reproduction case
- **Proof of concept**: Code, screenshots, or logs demonstrating the issue (if available)
- **Suggested fix**: If you have one (optional but appreciated)
- **Your contact details**: For follow-up communication

---

## Our Response Process

| Step | Timeframe |
|------|-----------|
| **Acknowledgement** — We confirm receipt of your report | Within **48 hours** |
| **Initial assessment** — We evaluate severity and scope | Within **5 business days** |
| **Status update** — We share our findings and plan | Within **10 business days** |
| **Fix & release** — We develop, test, and deploy a fix | Depends on severity (see below) |
| **Public disclosure** — We publish a security advisory | After fix is widely available |

### Fix timelines by severity

| Severity | Target fix time |
|----------|----------------|
| 🔴 Critical (CVSS 9.0–10.0) | 7 days |
| 🟠 High (CVSS 7.0–8.9) | 14 days |
| 🟡 Medium (CVSS 4.0–6.9) | 30 days |
| 🟢 Low (CVSS 0.1–3.9) | 90 days |

We will keep you informed throughout the process and notify you before any public disclosure.

---

## Responsible Disclosure Policy

We ask that you:

- ✅ Give us reasonable time to investigate and fix the issue before public disclosure
- ✅ Avoid accessing or modifying data belonging to others
- ✅ Act in good faith to avoid privacy violations, data destruction, or service disruption
- ✅ Only interact with accounts or systems you own or have explicit permission to test

We commit to:

- ✅ Not pursue legal action against researchers who follow this policy
- ✅ Acknowledge your contribution (with your permission) in our security advisories
- ✅ Communicate transparently throughout the process

---

## Scope

This policy covers all **production repositories** under the [@aetechlabs](https://github.com/aetechlabs) GitHub organization.

**Out of scope:**

- Repositories explicitly marked as `[ARCHIVED]` or `[EXPERIMENTAL]`
- Third-party dependencies (report these to the respective maintainers)
- Social engineering attacks
- Physical security issues
- Denial-of-service attacks

---

## Bug Bounty

We do not currently operate a formal bug bounty program. However, we deeply value the contributions of security researchers and will publicly acknowledge responsible disclosures (with your consent).

---

## Contact

| Purpose | Contact |
|---------|---------|
| Security vulnerabilities | [security@aetechlabs.com](mailto:security@aetechlabs.com) |
| Bug reports | [bugs@aetechlabs.com](mailto:bugs@aetechlabs.com) |
| Research inquiries | [research@aetechlabs.com](mailto:research@aetechlabs.com) |
| GitHub & open source | [github@aetechlabs.com](mailto:github@aetechlabs.com) |
| Contributing | [contributing@aetechlabs.com](mailto:contributing@aetechlabs.com) |
| General / enterprise | [contact@aetechlabs.com](mailto:contact@aetechlabs.com) |

---

*Last updated: March 2026 · AETECH RESEARCH LABS LIMITED*
