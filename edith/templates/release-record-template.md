# Release Record Template

## Release Identification
- **Version / Commit**: 
- **Date and Time** (UTC):
- **Release Name** (if applicable):
- **Target Environment**: (e.g., production, staging)

## Changes Included
- List of features, bug fixes, technical improvements.
- Associated requirement or ticket IDs.
- Links to pull requests or commits.

## Changes Excluded (if relevant)
- Deferred features or known omissions.

## Preconditions and Required Approvals
- Approvals from product, engineering, security, operations.
- Pre‑deployment checklist completed.

## Build / Test / Security Checks with Actual Results
- **Build**: Success/Failure, duration, artifact size.
- **Unit Tests**: Pass rate, coverage.
- **Integration Tests**: Pass rate.
- **Security Scan**: Vulnerability count, severity breakdown.
- **Performance Benchmark**: Results vs. baseline.
- **Accessibility Audit**: Score, issues.

## Data Migration and Backup / Restore Plan
- Migration scripts run.
- Backup taken before migration.
- Restore procedure tested.

## Configuration / Secrets Checklist (values only for internal use)
- Environment variables applied.
- Secrets injected (names only in shared copy).

## Deployment Steps and Responsible Actor
- Step‑by‑step commands executed.
- Who performed each step (or automation system).

## Health Checks and Success Criteria
- Results of post‑deployment verification.
- Any deviations and explanations.

## Rollback / Recovery Triggers and Steps
- Conditions that would trigger rollback.
- Steps taken (if any) and outcome.

## Monitoring / Alerts and Post‑Release Checks
- Alerts fired during release window.
- Post‑release metric trends.
- Incident reports.

## Known Risks, Unresolved Issues, and Explicit Risk Acceptances
- Risks that materialized.
- Issues discovered post‑release.
- Any risk acceptance recorded.

---
*Keep this record as the single source of truth for what was released, where, and how it went.*