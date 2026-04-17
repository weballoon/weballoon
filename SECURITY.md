# Security Policy

weballoon takes security seriously, especially around local privacy boundaries, account linking,
billing state, cloud sync, and desktop release delivery.

## How To Report A Vulnerability

Please report vulnerabilities privately to:

- `security@weballoon.app`

Do not open a public issue for suspected security problems.

## What To Include

Please include:

- a clear description of the issue
- affected version or environment
- reproduction steps
- impact assessment
- proof of concept if available
- whether exploitation requires prior access or user action

Helpful areas of detail:

- auth and account-linking flow
- billing and plan refresh behavior
- cloud sync authorization
- diagnostics ingestion
- update delivery and package trust
- session isolation between apps

## Supported Versions

Security fixes are prioritized for:

- the latest stable release
- the current production API and dashboard environment

Older builds may be asked to upgrade before a fix can be verified.

## Coordinated Disclosure

Please allow time for validation, remediation, and release coordination before public disclosure.
If the issue affects packaged desktop builds, we may need time to prepare signed replacement
releases across platforms.
