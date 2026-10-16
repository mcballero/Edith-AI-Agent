# Deployment Runbook Template

## Environment Configuration
- List of environments (local, dev, CI, staging, production).
- Variables, secrets, and configuration specific to each.
- Instructions for setting up each environment.

## Release Steps
1. **Pre‑release checks**
   - Verify branch/tag.
   - Run security scans.
   - Confirm test coverage.
   - Check dependencies for known vulnerabilities.
2. **Build**
   - Commands to compile, bundle, containerize.
   - Artifact versioning.
3. **Promotion**
   - Move artifact from build to staging.
   - Smoke test in staging.
4. **Deployment**
   - Commands to deploy to target environment.
   - Database migration steps (if any).
   - Feature flag toggles.
5. **Post‑deployment verification**
   - Health checks.
   - Key user journey validation.
   - Metrics and logs review.
6. **Rollback / Recovery**
   - Steps to revert to previous version.
   - Data migration reverse (if applicable).
   - Communication plan.

## Configuration / Secrets Checklist (names only)
- Environment variables required.
- Secret names (never values).
- Service dependencies.

## Health Checks and Success Criteria
- Endpoint responses.
- Latency thresholds.
- Error rate bounds.
- Business‑level metrics (sign‑ups, conversions).

## Monitoring / Alerts and Post‑Release Checks
- Dashboards to review.
- Alert routing.
- Post‑release validation window.

## Known Risks, Unresolved Issues, and Explicit Risk Acceptances
- Risks identified during planning.
- Issues deferred to future releases.
- Any material residual risk that the owner has accepted.

---
*Update this runbook as Edith refines the deployment strategy. Keep steps consistent with the chosen release process (rolling, blue/green, canary, etc.).*