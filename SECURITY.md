# Security Policy

## Supported Versions

| Version | Supported |
|---------|-----------|
| Latest release | Yes |
| Older versions | No |

We recommend always running the latest version of VI2D PRO.

## Reporting a Vulnerability

If you discover a security vulnerability in VI2D PRO, **please do not open a public issue.**

Instead, report it privately via [GitHub Security Advisories](https://github.com/DvaKarma/vi2d-pro/security/advisories/new).

Please include:

- A description of the vulnerability
- Steps to reproduce
- Potential impact
- Suggested fix (if any)

We will acknowledge your report within 48 hours and aim to release a fix as quickly as possible. You will be credited in the release notes unless you prefer otherwise.

## Scope

This policy covers the VI2D PRO desktop application and its source code. It does not cover third-party dependencies — please report those to the respective maintainers.

## Security Design

VI2D PRO is a system cleaner that operates with elevated permissions. We take this responsibility seriously:

- **No telemetry** — VI2D PRO does not phone home or collect any user data.
- **No network requests** — Scans and cleaning operations are entirely local. Network access is only used for update checks and optional cloud features you explicitly enable.
- **Open source** — Every operation is auditable. We encourage security researchers to review our code.
- **VirusTotal scanned** — Every release binary is automatically submitted to VirusTotal and results are linked in the release notes.
- **Signed binaries** — Windows releases are code-signed.
