# Security Review Rubric

## Criteria for Security‑Friendly Design & Implementation

### 1. Least Privilege
- [ ] Users, services, agents, and tools run with only the permissions they need.
- [ ] Privilege separation is applied where possible.

### 2. Authentication & Authorization
- [ ] Identity is verified before granting access (server‑side or trusted boundary).
- [ ] Access checks are performed for each protected operation.
- [ ] Role‑based or attribute‑based controls are defined and enforced.

### 3. Trust Boundaries & Data Flow
- [ ] Trust boundaries are clearly identified.
- [ ] Data crossing boundaries is validated and sanitized.
- [ ] Input validation and output encoding are applied at trust boundaries.

### 4. Secure Defaults
- [ ] Default configurations are secure (e.g., deny‑by‑default for inbound traffic).
- [ ] Unused services, ports, and features are disabled.

### 5. Confidentiality, Integrity, Availability (CIA)
- [ ] Sensitive data is encrypted at rest and in transit where appropriate.
- [ ] Integrity checks (hashes, signatures) are used for critical data.
- [ ] Redundancy and backup strategies mitigate availability risks.

### 6. Privacy
- [ ] Personal data is minimized, pseudonymized, or anonymized when possible.
- [ ] Consent and purpose limitation are respected.
- [ ] Data retention and deletion policies are defined.

### 7. Dependency & Supply Chain Safety
- [ ] Third‑party libraries and services are vetted for known vulnerabilities.
- [ ] Versions are locked or monitored for security advisories.
- [ ] Untrusted code is not executed without approval.

### 8. Logging & Monitoring
- [ ] Security‑relevant events (login attempts, access denials, config changes) are logged.
- [ ] Logs are protected from tampering and unauthorized access.
- [ ] Alerting is set up for suspicious activities.

### 9. Incident Response
- [ ] A plan exists for detecting, containing, and recovering from security incidents.
- [ ] Roles and responsibilities are defined.
- [ ] Forensic data collection is facilitated.

**Scoring**: Each criterion met = 1 point. Higher score indicates stronger security posture.

---
*Use this rubric to review threat models, security requirements, architecture, or implementation plans.*