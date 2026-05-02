# Security Policy

Veris provides identity verification infrastructure for financial applications and handles biometric workflows. We take security reports seriously and respond quickly.

## Supported versions

| Version | Supported |
|---------|-----------|
| 1.0.x   | Yes       |

Patches are applied to the latest release only. We do not backport fixes to older versions unless a critical vulnerability warrants it.

## Reporting a vulnerability

**Do not open a public GitHub issue for security vulnerabilities.**

Report privately by emailing **security@verisinfra.com** with:

- A description of the vulnerability and affected component (SDK platform, API endpoint, or dashboard)
- Steps to reproduce, including minimal code or a proof of concept where possible
- The potential impact - what an attacker could achieve
- Your name or handle if you want credit

For GitHub-tracked reports you can also open a [private security advisory](https://github.com/verisinfra/.github/security/advisories/new) directly.

## What to expect

| Milestone | Target |
|-----------|--------|
| Acknowledgement | Within 24 hours |
| Initial assessment | Within 72 hours |
| Fix or mitigation | Within 14 days for critical issues, 30 days for others |
| Public disclosure | After fix is shipped and users have had time to update |

We will keep you updated throughout. If you do not hear back within 48 hours, follow up at security@verisinfra.com.

## Scope - what we want to hear about

- Liveness detection bypass (passive or active)
- Signature forgery in the signed result payload (ECDSA)
- License key bypass or privilege escalation between plan tiers
- Nonce replay attacks or nonce store vulnerabilities
- Biometric data exfiltration from SDK or API
- Authentication vulnerabilities in the dashboard or backend API
- Injection vulnerabilities (SQL, command, SSRF, etc.)
- Sensitive data exposure in API responses, logs, or error messages
- Sandbox boundary violations (sandbox keys gaining production access)

## Out of scope

- Vulnerabilities in third-party dependencies that have no Veris-specific exploit path
- Social engineering attacks
- Physical access attacks
- Denial of service (rate limiting and availability are operational concerns, not security issues)
- Issues requiring a jailbroken or rooted device where the host app has explicitly enabled such access

## Responsible disclosure

We ask that you:

- Give us reasonable time to respond before any public disclosure
- Avoid testing against live customer data or production accounts you do not own
- Not disrupt or degrade the service for other users

We will not pursue legal action against researchers who follow these guidelines and act in good faith.

## Contact

security@verisinfra.com
