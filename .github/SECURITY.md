# Security Policy

## Reporting Security Issues

**Please do not report security vulnerabilities through public GitHub issues.**

If you discover a security issue in Protocol Zero's content (such as recommending a compromised tool, insecure practice, or outdated security advice), please report it privately.

### How to Report

1. Open a private security advisory (GitHub repository → Security → Report a vulnerability).
2. If you cannot access advisories, open a GitHub issue titled "SECURITY" with minimal detail; we will follow up privately.

### What to Include

When reporting a security issue, please include:

- **Description** of the issue
- **Location** in the documentation (file, section, line number)
- **Impact**: Why is this a security concern?
- **Evidence**: Links to sources, CVEs, security advisories, or research
- **Suggested fix**: If you have recommendations

## Types of Security Issues

We consider the following as security issues that warrant immediate attention:

### Critical (Emergency Update)

- **Compromised tool**: A recommended tool has suffered a data breach or security incident
- **Insecure practice**: Content recommends a practice that is now known to be insecure
- **Dangerous advice**: Instructions that could lead to data loss or security compromise
- **Malicious tool**: A recommended tool is discovered to be malicious or hostile to privacy

### High Priority (Fast-Track Update)

- **Outdated security advice**: Security recommendations that no longer meet current best practices
- **Deprecated security feature**: Recommended security feature is being phased out
- **New attack vector**: New threats that affect recommended practices
- **Legal/compliance issue**: Content conflicts with new privacy laws or regulations

### Medium Priority (Regular Update)

- **Tool discontinued**: Recommended tool is no longer maintained
- **Better alternative**: Significantly better security option becomes available
- **Unclear security guidance**: Security instructions are ambiguous and could be misinterpreted

## Our Response Process

### Timeline

- **Critical issues**: We aim to respond within 24 hours and publish a fix within 72 hours
- **High priority issues**: Response within 3 days, fix within 1-2 weeks
- **Medium priority issues**: Response within 1 week, fix in next scheduled update

### Process

1. **Acknowledgment**: We'll confirm receipt of your report
2. **Assessment**: We'll evaluate the issue with subject matter experts if needed
3. **Fix development**: We'll prepare updated content and changelog
4. **Coordinated disclosure**: For critical issues, we may coordinate with affected parties
5. **Publication**: We'll publish the fix and update the changelog
6. **Credit**: We'll acknowledge your contribution (unless you prefer to remain anonymous)

## Supported Versions

We maintain the current version of Protocol Zero. When significant updates are published:

- **Current version** (latest): Fully supported, receives all updates
- **Previous version**: Security-critical updates only for 3 months after new version release
- **Older versions**: No longer supported

For contribution workflow and how updates are handled, see [CONTRIBUTING.md](../CONTRIBUTING.md).

## Security Best Practices for Contributors

If you're contributing to Protocol Zero, please:

- **Test tool recommendations** before suggesting them
- **Cite sources** for security claims
- **Flag uncertainty**: If you're not sure something is secure, say so
- **Consider threat models**: What works for one user may not work for another
- **Avoid security theater**: Recommend practices that actually improve security
- **Stay current**: Security is a moving target; what's secure today may not be tomorrow

## Out of Scope

The following are **not** security issues for this project:

- **Tool vulnerabilities**: If a third-party tool has a vulnerability, report it to that tool's maintainer, not to us (though we appreciate a heads-up so we can update our recommendations)
- **Philosophical disagreements**: Different opinions on security trade-offs (unless backed by evidence of insecurity)
- **Feature requests**: Suggestions for new content (use regular issues for these)
- **Implementation help**: Questions about how to implement security practices (use discussions or support channels)

## Thank You

We appreciate the security community's efforts to keep Protocol Zero accurate and safe. Your vigilance helps protect all users of this guide.

## Past Security Issues

We maintain a log of past security updates:

### 2025

- _No critical security updates yet_

(This section will be updated as security issues are addressed)
