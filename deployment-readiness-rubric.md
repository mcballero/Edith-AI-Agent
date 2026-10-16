# Deployment Readiness Rubric

## Criteria for a Releasable System

### 1. Build & Artifact Production
- [ ] Build process is automated, repeatable, and versioned.
- [ ] Artifacts (binaries, containers, packages) are produced and stored immutably.
- [ ] Build logs and checksums are retained for traceability.

### 2. Automated Testing
- [ ] Unit, integration, and acceptance tests run on every commit (CI).
- [ ] Test results are recorded and visible.
- [ ] Test coverage meets agreed thresholds.

### 3. Security Scanning
- [ ] Dependency vulnerability scans are performed (e.g., npm audit, Snyk, Dependabot).
- [ ] Static analysis (SAST) and dynamic analysis (DAST) are run where applicable.
- [ ] Container images are scanned for known vulnerabilities and misconfigurations.

### 4. Configuration Management
- [ ] Environment‑specific configurations are stored outside of source control (or templated).
- [ ] Secrets are never stored in plain text; they are injected via a secrets manager or environment variables at runtime.
- [ ] Configuration drift is monitored.

### 5. Database & Data Handling
- [ ] Migration scripts are versioned, tested, and reversible where possible.
- [ ] Backup and restore procedures are documented and tested.
- [ ] Data validation and sanitization are applied at ingestion points.

### 6. Observability
- [ ] Application logs, metrics, traces, and health checks are instrumented.
- [ ] Log aggregation and retention policies are defined.
- [ ] Alerting thresholds are set for key performance and error metrics.

### 7. Release Process
- [ ] A clear release plan exists (steps, approvals, rollback).
- [ ] Deployment is automated or scripted with minimal manual steps.
- [ ] Blue/green, canary, or rolling release strategies are considered and documented.

### 8. Post‑Deployment Validation
- [ ] Smoke tests or synthetic transactions run after deployment.
- [ ] Key user journeys are verified in the target environment.
- [ ] Rollback procedures are tested and known to work.

### 9. Documentation & Knowledge Transfer
- [ ] Deployment runbook is up‑to‑date and accessible.
- [ ] Operators and on‑call engineers are trained.
- [ ] Known issues and workarounds are communicated.

**Scoring**: Each criterion met = 1 point. Higher score indicates higher deployment readiness.

---
*Use this rubric to review deployment plans, release checklists, or operational documentation.*