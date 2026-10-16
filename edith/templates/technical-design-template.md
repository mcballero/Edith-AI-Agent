# Technical Design Template

## Context and Constraints
- Project goals, non‑goals, and scope.
- Key requirements driving the design.
- Environmental constraints (budget, timeline, team size, regulatory).

## Candidate Approaches and Trade‑offs
- List of viable architectural or technical approaches.
- For each: benefits, drawbacks, costs, risks, and ideal use cases.
- Comparison table or summary.

## Proposed Architecture and Component Boundaries
- High‑level diagram description (or actual diagram if supported).
- Components/modules and their responsibilities.
- Data flow between components.
- Ownership of data (who creates, reads, updates, deletes).
- Interface contracts (APIs, events, shared storage).

## Data Model and Ownership
- Core entities and relationships.
- Data storage technologies chosen.
- Schema diagrams or descriptions.
- Data lifecycle (creation, retention, archival, deletion).

## API Contracts (when supported or explicitly proposed)
- Endpoint summary (method, path, purpose).
- Request/response schemas.
- Error handling.
- Versioning strategy.

## Authentication and Authorization
- User authentication methods.
- Role‑based or attribute‑based access control.
- Trust boundaries and data flow protections.

## Failure Modes and Recovery
- Expected failure scenarios (hardware, software, external service).
- Detection mechanisms.
- Recovery procedures (retries, fallbacks, circuit breakers).
- Data backup and restore plans.

## Security and Privacy Considerations
- Threat model summary (if separate).
- Data protection (encryption at rest/in transit).
- Input validation and output encoding.
- Secure defaults and least privilege.
- Privacy‑by‑design measures (data minimization, anonymization).

## Observability and Operations
- Logging strategy (levels, formats, destinations).
- Metrics to collect (latency, error rates, throughput).
- Health checks and alerting.
- Tracing (if applicable).
- Dashboard and reporting needs.

## Testing Strategy
- Unit, integration, contract, performance, security test plans.
- Test environments and data.
- Acceptance test alignment with requirements.

## Migration, Rollout, and Rollback
- Database migration approach.
- Feature flag or blue/green/canary rollout plan.
- Rollback procedures if issues arise.

## Open Decisions
- Items still under consideration.
- Needed information to resolve them.
- Impact of each option.

---
*Update this design as Edith guides you through the workflow. Keep diagrams and contracts consistent with the source evidence and approved decisions.*