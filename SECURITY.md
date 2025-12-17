# Security Policy

## Supported Versions

| Version | Supported          |
| ------- | ------------------ |
| 0.1.x   | :white_check_mark: |

## Reporting a Vulnerability

We take security vulnerabilities seriously. If you discover a security issue, please report it responsibly.

### How to Report

1. **Do NOT** open a public GitHub issue for security vulnerabilities
2. Email security concerns to the project maintainers via GitHub's private vulnerability reporting feature
3. Or contact the maintainer directly through their GitHub profile

### What to Include

- Description of the vulnerability
- Steps to reproduce the issue
- Potential impact assessment
- Any suggested fixes (optional)

### Response Timeline

- **Initial Response**: Within 48 hours
- **Status Update**: Within 7 days
- **Resolution Target**: Within 90 days for critical issues

### Security Measures in This Project

This project follows security best practices including:

- **SAST Scanning**: Automated Semgrep security analysis on all PRs
- **Dependency Management**: Dependabot monitors for vulnerable dependencies
- **SHA-Pinned Actions**: All GitHub Actions use commit SHA pins, not version tags
- **Least Privilege**: CI/CD workflows use minimal required permissions
- **Secrets Management**: No hardcoded credentials; all secrets via GitHub Secrets

### Acknowledgments

We appreciate responsible disclosure and will acknowledge security researchers who help improve this project's security (with their permission).
