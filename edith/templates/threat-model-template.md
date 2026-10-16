# Threat Model Template

## Assets and Sensitive Data
- List of assets (data, components, services) that need protection.
- Classification of data sensitivity (public, internal, confidential, regulated).

## Trust Boundaries and Data Flows
- Diagram or description of trust boundaries.
- Data flows across boundaries (entry points, exits).

## Threats (using STRIDE or similar)
- **Spoofing**: How an attacker could pretend to be something else.
- **Tampering**: How data or code could be altered.
- **Repudiation**: How actions could be denied.
- **Information Disclosure**: How data could be exposed.
- **Denial of Service**: How service availability could be disrupted.
- **Elevation of Privilege**: How an attacker could gain higher access.

For each threat:
- **Asset(s) affected**.
- **Attack vector**.
- **Potential impact**.
- **Existing controls**.
- **Proposed mitigations**.
- **Residual risk** (after mitigations).
- **Verification steps** (how to test the mitigation).

## Attack Scenarios
- Narrative walk‑throughs of plausible attack paths.
- Steps an attacker might take.
- Expected defender actions.

## Risk Acceptance
- Any residual risk that must be accepted by the product owner.
- Rationale for acceptance.
- Conditions or monitoring required.

---
*Keep the threat model focused on the feature or system under consideration. Update as design evolves.*