# Security Policy

## Supported Versions

We actively support and patch the latest stable version of PyCraft-Utility-Automation-Python-Framework. Please ensure you are using the most recent release.

| Version | Supported          |
|---------|--------------------|
| Latest  | :white_check_mark: |
| Earlier | :x:                |

## Reporting a Vulnerability

We take security vulnerabilities very seriously. If you discover a security issue with PyCraft-Utility-Automation-Python-Framework, please report it to us promptly using one of the methods below.

**We will NOT pursue or report you to the authorities if you follow this policy in good faith.**

### How to Report

1.  **Email:** Send an encrypted email to `security@chirag127.dev` (subject: `Security Vulnerability Report`). Please encrypt your findings using our PGP key, which can be found at [https://github.com/chirag127/PyCraft-Utility-Automation-Python-Framework/raw/main/SECURITY.asc](https://github.com/chirag127/PyCraft-Utility-Automation-Python-Framework/raw/main/SECURITY.asc).
2.  **GitHub Security Advisory:** Create a private security vulnerability report directly through GitHub's advisory system: [https://github.com/chirag127/PyCraft-Utility-Automation-Python-Framework/security/advisories/new](https://github.com/chirag127/PyCraft-Utility-Automation-Python-Framework/security/advisories/new).

### Information to Include

Please provide as much of the following information as possible to help us understand and resolve the vulnerability:

*   The exact location of the vulnerability (e.g., file path, function name, URL).
*   A brief description of the vulnerability.
*   Detailed steps to reproduce the vulnerability.
*   The impact of the vulnerability.
*   Any mitigation or remediation recommendations.

### What Happens Next?

*   We will acknowledge receipt of your report within **48 hours**. 
*   We will triage and investigate the vulnerability based on its severity and impact.
*   We will provide regular updates on our progress in resolving the issue.
*   Once a fix is developed and deployed, we will credit the reporter in our release notes and potentially on our security advisories page.

We appreciate your efforts to help us improve the security of PyCraft-Utility-Automation-Python-Framework.

----

## Security Practices

PyCraft-Utility-Automation-Python-Framework is built with security in mind. We adhere to the following practices:

*   **Dependency Management:** All dependencies are managed via `uv` and are regularly scanned for known vulnerabilities. We aim to use the latest secure versions.
*   **Code Review:** All code changes undergo rigorous peer review, with a specific focus on security implications.
*   **Linting and Static Analysis:** `Ruff` is used to enforce strict coding standards and catch potential security anti-patterns.
*   **Testing:** Comprehensive test suites (unit and integration using `Pytest`) are in place to verify correct functionality and detect regressions.
*   **CI/CD Pipeline:** Automated checks, including security scans, are integrated into our GitHub Actions CI/CD pipeline to ensure code quality and security before deployment.
*   **Principle of Least Privilege:** Where applicable, components operate with the minimum necessary permissions.
*   **Input Validation:** All external inputs are strictly validated to prevent injection attacks and other common vulnerabilities.

--- 

*This security policy was last updated on December 2025.*