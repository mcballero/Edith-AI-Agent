# Engineering Review Rubric

## Criteria for a Sound Technical Design

### 1. Architecture & Components
- [ ] Component responsibilities are clear and cohesive.
- [ ] Data ownership and flow are well defined.
- [ ] Interface contracts (APIs, events) are specified.

### 2. Simplicity & Necessity
- [ ] Design avoids unnecessary complexity or over‑engineering.
- [ ] Each component or technology choice is justified by requirements.

### 3. Scalability & Performance
- [ ] Anticipated load and growth are considered.
- [ ] Bottlenecks are identified and mitigated where feasible.

### 4. Reliability & Fault Tolerance
- [ ] Failure modes are considered (hardware, software, external).
- [ ] Retry, circuit breaker, fallback, or redundancy strategies are present.

### 5. Security & Privacy
- [ ] Threat model or security considerations are addressed.
- [ ] Authentication, authorization, input validation, and output encoding are covered.
- [ ] Data protection (encryption at rest/in transit) is considered.

### 6. Observability & Operability
- [ ] Logging, metrics, tracing, and health‑checking strategies are defined.
- [ ] Alerting and dashboards are planned.

### 7. Testability
- [ ] Design facilitates unit, integration, and end‑to‑end testing.
- [ ] Mocks, stubs, or test doubles can be used where needed.

### 8. Maintainability
- [ ] Code organization and naming conventions are sensible.
- [ ] Documentation (comments, diagrams) is sufficient for future engineers.
- [ ] Technical debt is acknowledged and tracked.

### 9. Compliance & Standards
- [ ] Relevant regulatory, industry, or company standards are followed.
- [ ] Licensing and dependency implications are considered.

**Scoring**: Each criterion met = 1 point. Higher score indicates a stronger design.

---
*Use this rubric to review technical design documents, architecture diagrams, or API specifications.*