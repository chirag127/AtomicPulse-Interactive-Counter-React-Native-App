# Security Policy

## Supported Versions

We are committed to maintaining the security of `AtomicPulse-Interactive-Counter-React-Native-App`. We actively monitor and address security vulnerabilities in the following versions:

| Version | Supported          |
| ------- | ------------------ |
| Main Branch (unreleased) | :white_check_mark: |
| Latest Release       | :white_check_mark: |

Older versions are not actively maintained and may not receive security updates.

## Reporting a Vulnerability

We take all security vulnerabilities seriously. If you discover a security issue, please follow these steps to report it:

1.  **DO NOT** open a public issue.
2.  Send a detailed email to our security team at `chirag.patel.dev@gmail.com` with the subject line: "Security Vulnerability Report - `AtomicPulse-Interactive-Counter-React-Native-App`".
3.  Please include as much information as possible, such as:
    *   The affected version(s) of the application.
    *   A clear description of the vulnerability.
    *   Steps to reproduce the vulnerability.
    *   Any affected components or dependencies.
    *   Your suggested mitigation or fix, if applicable.

We will acknowledge receipt of your email within 24-48 hours and will work diligently to assess and address the vulnerability. We appreciate your responsible disclosure.

## Security Practices

We aim to follow best practices to secure `AtomicPulse-Interactive-Counter-React-Native-App`:

*   **Dependency Management:** Regularly update and audit dependencies using automated tools to identify and patch known vulnerabilities. The CI pipeline (`ci.yml`) includes checks for vulnerable dependencies.
*   **Code Review:** All code changes undergo a review process to identify potential security flaws before merging.
*   **Linting and Formatting:** Tools like Ruff are used to enforce code quality and catch potential issues.
*   **Testing:** Comprehensive test suites (unit and E2E) help ensure the application behaves as expected and does not introduce regressions.
*   **Least Privilege:** Components and services operate with the minimum necessary permissions.
*   **Secure Defaults:** Where applicable, default configurations are set to secure values.

Thank you for helping us keep `AtomicPulse-Interactive-Counter-React-Native-App` secure!
