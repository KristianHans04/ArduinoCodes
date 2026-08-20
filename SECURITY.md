# Security Policy

## Supported Versions

| Version | Supported |
| ------- | --------- |
| Latest  | Yes       |

Only the latest release is actively supported with security updates. Older versions should be upgraded as soon as possible.

## Reporting a Vulnerability

We take the security of this project seriously. If you believe you have found a security vulnerability, please report it to us as described below.

**Please do not report security vulnerabilities through public GitHub issues, pull requests, or discussions.**

### Preferred: Private Vulnerability Reporting

Use GitHub's private vulnerability reporting feature to confidentially disclose the issue:

1. Navigate to the repository's **Security** tab.
2. Select **Report a vulnerability**.
3. Provide a detailed description, including:
   - The affected version(s) and environment
   - Steps to reproduce the issue
   - A proof of concept, if available
   - The potential impact

### Alternative: Email

Alternatively, email the details to [hello@kristianhans.com](mailto:hello@kristianhans.com). If the report is highly sensitive, mention that in the subject line so we can arrange a secure channel.

### What to Include in a Report

- Affected repository and version
- Description of the vulnerability and its potential impact
- Steps to reproduce
- Suggested fix, if known

## Response Timeline

| Timeframe   | Expected Action                       |
| ----------- | ------------------------------------- |
| 48 hours    | Acknowledgment of the report          |
| 7 days      | Initial triage and severity assessment |
| 30 days     | Fix, mitigation, or a detailed plan   |

We ask that you refrain from public disclosure until we have had the opportunity to address the issue. We will coordinate responsible disclosure with you.

## Security Best Practices for Contributors

- Keep dependencies up to date and respond to Dependabot alerts promptly.
- Never commit secrets, API keys, or credentials to the repository. If you do, rotate them immediately.
- Review code scanning alerts and address findings before merging.
- Enable branch protection on the default branch and require reviews for changes.
- Use two-factor authentication on all accounts with write access.