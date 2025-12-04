# Security Policy

## Supported Versions

We are committed to maintaining a secure project. As the original repository is a Hugo Theme website template, we focus on the security of the theme's implementation and its integration into a static site generator context. We do not handle sensitive runtime data in this theme directly.

| Version | Supported          |
|---------|--------------------|
| Latest  | :white_check_mark: |

## Reporting a Vulnerability

We take security vulnerabilities very seriously. If you discover any security issues, please report them to us immediately. We will investigate and address the issue promptly.

### Responsible Disclosure Program

We follow a responsible disclosure process:

1.  **Discovery:** You discover a security vulnerability.
2.  **Reporting:** You report the vulnerability to us privately via email at [security@example.com](mailto:security@example.com) or by opening a **private** security advisory in this repository's "Security" tab.
    *   **DO NOT** create a public issue for security vulnerabilities.
    *   Please provide as much detail as possible, including:
        *   A clear description of the vulnerability.
        *   The affected version(s) (e.g., theme version, Hugo version).
        *   Steps to reproduce the vulnerability.
        *   Any proof-of-concept code or screenshots.
        *   Your recommended mitigation or fix (if any).
3.  **Acknowledgement:** We will acknowledge your report within **72 hours** and aim to respond within **7 business days**.
4.  **Investigation & Remediation:** We will investigate the reported vulnerability and work on a fix. This may involve updating the theme's HTML, CSS, JavaScript, or Hugo templates.
5.  **Disclosure:** Once a fix is available and deployed (e.g., a new theme release), we will publicly disclose the vulnerability along with the fix, crediting you as the discoverer (if you wish).

### How to Report

*   **Email:** Send an email to `security@example.com`. Please use a descriptive subject line like "Security Vulnerability Report for PaperMod-Responsive-Hugo-Theme-Website-Template".
*   **GitHub Security Advisory:** If you have the necessary permissions, you can also report via GitHub's private security advisory feature: [https://github.com/chirag127/PaperMod-Responsive-Hugo-Theme-Website-Template/security/advisories/new](https://github.com/chirag127/PaperMod-Responsive-Hugo-Theme-Website-Template/security/advisories/new)

## Security Best Practices

For users integrating this theme into their Hugo projects, please adhere to the following best practices:

*   **Keep Hugo Updated:** Always use the latest stable version of Hugo. Check the [Hugo releases page](https://github.com/gohugoio/hugo/releases) for updates.
*   **Review Theme Changes:** If you fork or heavily customize the theme, carefully review all changes for potential security implications.
*   **Sanitize User Input:** If you extend the theme to accept any form of user input, ensure it is properly sanitized to prevent Cross-Site Scripting (XSS) or other injection attacks.
*   **Third-Party Integrations:** Be cautious when integrating third-party scripts or services. Ensure they are from trusted sources and are kept up-to-date.

Thank you for helping to keep the `PaperMod-Responsive-Hugo-Theme-Website-Template` project secure!
