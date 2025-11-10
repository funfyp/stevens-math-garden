# Security Policy

## 🔒 Supported Versions

We provide security updates for the following versions:

| Version | Supported          |
| ------- | ------------------ |
| 1.0.x   | :white_check_mark: |
| < 1.0   | :x:                |

## 🚨 Reporting a Vulnerability

### How to Report

If you discover a security vulnerability in Stevens Math Garden, please:

1. **DO NOT** open a public issue
2. **DO** email the maintainers privately (contact through GitHub)
3. **DO** use GitHub Security Advisories if available
4. **DO** provide detailed information:
   - Type of vulnerability
   - Location (file, line, function)
   - Potential impact
   - Suggested fix (if any)
   - Steps to reproduce

### What to Expect

- **Acknowledgment**: Within 48 hours
- **Initial Assessment**: Within 5 business days
- **Status Updates**: Every 7 days until resolution
- **Fix Timeline**: Depends on severity
  - Critical: 1-7 days
  - High: 7-14 days
  - Medium: 14-30 days
  - Low: 30-90 days

### Disclosure Policy

- We follow responsible disclosure practices
- Security patches released before public disclosure
- Credit given to reporters (if desired)
- CVE numbers assigned for significant vulnerabilities

## 🔐 Security Best Practices

### For Users

1. **Keep Updated**: Use the latest version
2. **Verify Downloads**: Check repository authenticity
3. **Review Dependencies**: Audit your supply chain
4. **Report Issues**: If you find something, report it
5. **Use Virtual Environments**: Isolate dependencies

### For Contributors

1. **Code Review**: All PRs reviewed for security
2. **Dependencies**: Keep requirements.txt updated
3. **Secrets**: Never commit API keys, passwords, or tokens
4. **Input Validation**: Validate all user inputs
5. **Error Handling**: Don't leak sensitive info in errors

## 🛡️ Security Considerations

### Code Execution

This is a mathematical research library and includes:
- ✅ Safe: Mathematical computations
- ✅ Safe: Data analysis on provided datasets
- ⚠️ Caution: Dynamic code evaluation (eval, exec) is NOT used
- ⚠️ Caution: File I/O is limited and sandboxed

### Data Privacy

We respect privacy:
- ❌ No telemetry or tracking
- ❌ No data sent to external servers
- ✅ All computations local
- ✅ User data stays with user

### Dependencies

We monitor dependencies for:
- Known vulnerabilities (using Dependabot)
- License compatibility
- Active maintenance

### Formal Verification

Mathematical proofs:
- Lean 4 proofs provide formal verification
- Coq proofs offer additional validation
- Human-readable proofs available for review

## 🐛 Known Issues

Currently no known security vulnerabilities.

See [GitHub Security Advisories](../../security/advisories) for historical issues.

## 🎖️ Hall of Thanks

We recognize security researchers who help us:

(No vulnerabilities reported yet)

## 📞 Contact

- **Security Issues**: Use GitHub Security Advisories or contact maintainers
- **General Questions**: Use GitHub Issues or Discussions
- **Collaboration**: See CONTRIBUTING.md

## 📜 Resources

- [OWASP Top 10](https://owasp.org/www-project-top-ten/)
- [Python Security Best Practices](https://python.readthedocs.io/en/stable/library/security_warnings.html)
- [GitHub Security Features](https://docs.github.com/en/code-security)

---

**Security is everyone's responsibility!** 🔒

*We are all dirt that thinks, protecting our garden together!* 🌱💛

Last updated: November 10, 2025