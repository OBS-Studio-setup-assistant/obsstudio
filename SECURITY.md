# Security Policy 🔒

## Supported Versions

We actively maintain security updates for the following versions of OBS Studio Setup Assistant:

| Version | Supported          | Status |
| ------- | ------------------ | ------ |
| 31.0.x  | ✅ Yes            | Current stable release |
| 30.x.x  | ✅ Yes            | Previous stable (until March 2025) |
| 29.x.x  | ⚠️ Limited        | Critical security fixes only |
| < 29.0  | ❌ No             | End of life |

## Security Features

### 🛡️ Built-in Security Measures

- **Offline Operation**: No internet connection required after initial setup
- **Zero Telemetry**: No data collection or tracking
- **Local Storage**: All configurations stored locally
- **Code Signing**: All releases are digitally signed
- **Checksum Verification**: SHA256 checksums provided for all downloads
- **Sandboxed Installation**: Minimal system permissions required
- **No Remote Execution**: No code executed from external sources

### 🔐 Privacy Protection

- **No Account Required**: Works without creating accounts or profiles
- **Local Processing**: All configuration happens on your device
- **Encrypted Storage**: Sensitive settings encrypted at rest
- **Clean Uninstall**: Complete removal leaves no traces

## Reporting a Vulnerability

### 🚨 How to Report

**For security vulnerabilities, please do NOT create a public GitHub issue.**

Instead, report security issues through one of these secure channels:

#### Email (Preferred)
- **Email**: [security@obs-setup-assistant.io](mailto:security@obs-setup-assistant.io)
- **Subject**: "Security Vulnerability Report - [Brief Description]"
- **Response Time**: Within 24 hours

#### GitHub Security Advisory (Alternative)
- Go to our [Security Advisories](https://github.com/OBS-Studio-setup-assistant/obsstudio/security/advisories)
- Click "Report a vulnerability"
- Fill out the private vulnerability report form

### 📝 What to Include

When reporting a security vulnerability, please provide:

#### Required Information
- **Description**: Clear description of the vulnerability
- **Impact**: What systems/data could be affected
- **Reproduction Steps**: Detailed steps to reproduce the issue
- **Environment**: OS, version, configuration details
- **Discovery Method**: How you discovered the vulnerability

#### Optional Information
- **Proof of Concept**: Non-destructive demonstration code
- **Suggested Fix**: If you have ideas for fixing the issue
- **CVE Information**: If already assigned a CVE number

### 📧 Report Template

```
Subject: Security Vulnerability Report - [Brief Description]

**Vulnerability Type**: [e.g., Code Execution, Information Disclosure, etc.]
**Severity**: [Critical/High/Medium/Low]
**Affected Versions**: [e.g., 31.0.0-31.0.3]
**Discovery Date**: [Date you discovered the issue]

**Description**:
[Clear description of the vulnerability]

**Impact**:
[Potential impact and affected systems]

**Steps to Reproduce**:
1. [Step 1]
2. [Step 2]
3. [Step 3]

**Environment**:
- OS: [Windows 11/macOS 13/Ubuntu 22.04]
- Version: [Setup Assistant version]
- OBS Version: [OBS Studio version]

**Additional Information**:
[Any other relevant details]
```

## Response Process

### 🕐 Timeline

| Stage | Timeframe | Description |
|-------|-----------|-------------|
| **Acknowledgment** | 24 hours | Confirm receipt of your report |
| **Initial Assessment** | 72 hours | Determine severity and impact |
| **Investigation** | 1-2 weeks | Thorough analysis and reproduction |
| **Fix Development** | 2-4 weeks | Develop and test the fix |
| **Release** | 1 week | Deploy fix and notify users |
| **Disclosure** | 30 days | Public disclosure (if applicable) |

### 🏆 Recognition

#### Security Hall of Fame
We maintain a [Security Hall of Fame](https://github.com/OBS-Studio-setup-assistant/obsstudio/security/hall-of-fame) to recognize responsible disclosure.

#### Criteria for Recognition
- Valid security vulnerability
- Responsible disclosure process followed
- Constructive communication
- Original discovery (not previously reported)

#### What We Don't Recognize
- Issues in third-party dependencies (report to them first)
- Social engineering attacks
- Physical access attacks
- Denial of service attacks
- Issues requiring user misconfiguration

## Security Best Practices

### 🔧 For Users

#### Installation Security
- Download only from official sources
- Verify checksums before installation
- Run with minimum required privileges
- Keep software updated

#### Usage Security
- Regular security updates
- Secure configuration management
- Monitor for unusual behavior
- Use official plugins only

### 👨‍💻 For Developers

#### Code Security
- Follow secure coding practices
- Regular dependency updates
- Code review all changes
- Static analysis tools
- Penetration testing

#### Build Security
- Secure build environment
- Signed releases
- Supply chain verification
- Minimal dependencies

## Vulnerability Classification

### Severity Levels

#### 🔴 Critical (CVSS 9.0-10.0)
- Remote code execution
- Privilege escalation to system level
- Complete system compromise

#### 🟠 High (CVSS 7.0-8.9)
- Local code execution
- Privilege escalation to user level
- Significant data exposure

#### 🟡 Medium (CVSS 4.0-6.9)
- Limited information disclosure
- Denial of service
- Minor privilege escalation

#### 🟢 Low (CVSS 0.1-3.9)
- Minimal information disclosure
- Low-impact denial of service
- Minor security bypass

## Security Updates

### 📦 Update Delivery

- **Critical**: Emergency release within 24-48 hours
- **High**: Hotfix release within 1 week
- **Medium**: Regular release cycle (monthly)
- **Low**: Next planned release

### 📢 Notification Channels

- **GitHub Releases**: Detailed changelog
- **Security Advisories**: Critical issues only
- **Email Newsletter**: For subscribers
- **Documentation**: Updated security notes

## Contact Information

### 📞 Security Team

- **Primary Contact**: [security@obs-setup-assistant.io](mailto:security@obs-setup-assistant.io)
- **Backup Contact**: [admin@obs-setup-assistant.io](mailto:admin@obs-setup-assistant.io)
- **GitHub**: [@obs-security-team](https://github.com/obs-security-team)

### 🌐 Public Keys

For encrypted communications:
- **GPG Key**: Available at [keyserver.ubuntu.com](https://keyserver.ubuntu.com)
- **Key ID**: 0x1234567890ABCDEF
- **Fingerprint**: 1234 5678 90AB CDEF 1234 5678 90AB CDEF 1234 5678

---

## Legal Notice

This security policy is subject to our [Terms of Service](https://obs-setup-assistant.io/terms) and [Privacy Policy](https://obs-setup-assistant.io/privacy). By participating in our security program, you agree to these terms.

---

*Last updated: December 2024 | Version: 31.0.3*

**Remember**: Security is a shared responsibility. Help us keep the community safe by reporting vulnerabilities responsibly. 🛡️ 