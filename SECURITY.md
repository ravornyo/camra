# Security Policy

## Supported Versions

Camra is early-stage — only one version has been released so far. Only the most recent release receives security updates.

| Version | Supported          |
| ------- | ------------------ |
| 0.1.0   | :white_check_mark: |

This table will expand as more versions are released.

## Reporting a Vulnerability

Please **do not** open a public GitHub issue for security vulnerabilities — this could put users at risk before a fix is available.

Instead, use GitHub's private vulnerability reporting:

1. Go to the **Security** tab of this repository.
2. Click **Report a vulnerability**.

This submits the report privately, visible only to the maintainer, rather than publicly.

### What to expect

- **Acknowledgment**: best effort, typically within a few days. This is currently a solo-maintained project, not a team with a formal SLA — please be patient.
- **If accepted**: a fix will be developed and released as a new version. Existing installations can pick it up via **Help → Check for Updates** from within the app once it's published, without needing to manually download a new build.
- **If declined**: you'll receive an explanation of why the report isn't considered a security issue (for example, it's a general bug rather than a vulnerability, already known, or out of scope).

### Scope

This covers the Camra application itself. Vulnerabilities in dependencies (Eclipse RCP/e4, vlcj/libvlc, ONVIF-related libraries, etc.) should generally be reported to those projects directly, unless Camra's own use of them is what introduces the issue.

Camra is provided under the GNU General Public License v3.0, which includes no warranty (see `LICENSE`) — security fixes, like all maintenance here, are provided on a best-effort basis.
