# Security policy

## Supported versions

MDK v0.2.0 is the current early SemVer release line. Security support is provided for:

- **v0.2.x** — the current release line (check out the latest `v0.2.*` tag or this repository's `main` branch)
- The latest commit on `main` for pre-release fixes not yet tagged

Older release lines (including v0.0.1 and pre-release `*-beta` / `*-rc` tags) may not receive security fixes.

| Version | Supported |
|---|---|
| 0.2.x | Yes |
| 0.0.x | No |
| `main` (unreleased) | Best-effort until the next tagged release |

Security updates for the 0.2.x line will be provided until v0.3.0 is released, after which 0.2.x enters a maintenance window of at least 90 days.

## Reporting a vulnerability

Please do **not** open public GitHub issues for security vulnerabilities.

Instead, report security issues privately via:

- GitHub Security Advisories: [Report a vulnerability](https://github.com/tetherto/mdk/security/advisories/new)

Include as much detail as possible:

- Affected component(s) and version/commit
- Steps to reproduce
- Impact assessment
- Any proof-of-concept or logs (if safe to share)
- Suggested mitigation, if known

## Disclosure process

After receiving a report, maintainers aim to:

1. Acknowledge receipt within 3 business days.
2. Confirm whether the issue is valid and in scope.
3. Prepare and release a fix as quickly as possible.
4. Coordinate disclosure timing with the reporter when appropriate.

## Scope notes

Security issues in first-party code under this repository are in scope.

Reports that depend exclusively on unsupported runtimes, modified third-party deployments, or issues already fixed on `main` may be considered out of scope.
