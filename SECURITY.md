# ZenYukti Security Policy

## Reporting a Vulnerability

At ZenYukti, we take security seriously. We appreciate your efforts to responsibly disclose your findings and will make every effort to acknowledge your contributions.

### Reporting Process

1. **Submit Report**: Send details of the vulnerability to [support@zenyukti.in](mailto:support@zenyukti.in) with the subject line "[SECURITY] Vulnerability Report".

2. **Encryption**: For sensitive reports, you can encrypt your message using our PGP key (available upon request).

3. **Information to Include**:
   - Description of the vulnerability
   - Steps to reproduce
   - Affected versions/components
   - Potential impact
   - Any suggested mitigation or fix (if available)
   - Your contact information for follow-up (optional)

### What to Expect

- **Acknowledgment**: We'll acknowledge receipt of your report within 48 hours.
- **Updates**: We'll provide regular updates about our progress in addressing the issue.
- **Resolution**: Once resolved, we'll notify you and discuss appropriate disclosure timing.
- **Recognition**: With your permission, we'll acknowledge your contribution in our release notes and security advisories.

## Security Update Policy

### Supported Versions

| Project | Version | Supported          |
| ------- | ------- | ------------------ |
| Core    | 1.x     | :white_check_mark: |
|         | < 1.0   | :x:                |
| Web App | 2.x     | :white_check_mark: |
|         | 1.x     | :white_check_mark: |
|         | < 1.0   | :x:                |

### Update Process

1. Security issues are prioritized over feature development.
2. Critical vulnerabilities receive patches for all supported versions.
3. Security updates are clearly marked in release notes.
4. We aim to release security patches within:
   - Critical: 7 days
   - High: 14 days
   - Medium/Low: Next scheduled release

## Best Practices for Contributors

1. **Dependency Management**: Regularly update dependencies and check for security advisories.
2. **Code Reviews**: Security-focused code reviews are required for authentication, authorization, and data handling.
3. **Secure Development**: Follow OWASP guidelines for secure coding practices.
4. **Testing**: Include security-focused tests when applicable.

## Security Measures

ZenYukti implements several security measures across our projects:

- Regular dependency scanning and updates
- Static code analysis in our CI/CD pipeline
- Input validation and output encoding
- Content Security Policy implementation
- Regular security training for core contributors

## Disclosure Policy

We believe in responsible disclosure:

1. Security issues are disclosed after a patch is available
2. We provide users adequate time to update before full details are published
3. Proof-of-concept code is never released if it could harm users
4. We coordinate disclosure with affected dependency maintainers when applicable

## Acknowledgments

We'd like to thank the following individuals for responsibly reporting security issues:

*(This section will be updated as contributions are received)*

---

Thank you for helping keep **ZenYukti** and our community safe!

**Contact**: [support@zenyukti.in](mailto:support@zenyukti.in)  
**Discord**: [ZenYukti Community](https://go.zenyukti.in/discord)  
**Website**: [https://zenyukti.in](https://zenyukti.in)  
**X (Twitter)**: [https://x.com/zenyukti](https://x.com/zenyukti)  
**LinkedIn**: [https://linkedin.com/company/zenyukti](https://linkedin.com/company/zenyukti)
