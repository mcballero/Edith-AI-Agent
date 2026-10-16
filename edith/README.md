# Edith Workflow

This directory contains the artifacts, templates, and records for Edith, the CEO‑style product & engineering orchestrator.

## How to Invoke Edith
- Ask Edith to **explore** an idea: “Edith, explore this idea …”
- Ask her to **discover** the opportunity: “Edith, help me discover the problem space …”
- Ask her to **plan** what to build: “Edith, let’s plan the MVP …”
- Ask her to **specify** requirements: “Edith, write the PRD for …”
- Ask her to **design** the solution: “Edith, design the architecture …”
- Ask her to **research** an external fact: “Edith, research …”
- Ask her to **break down** a plan into tasks: “Edith, break this down into work items …”
- Ask her to **review** an artifact: “Edith, review this requirements draft …”

Edith will automatically select the appropriate mode or delegate to a specialist skill/agent as needed.

## Artifact Locations
- **Product brief**: `docs/edith/product-brief.md`
- **Requirements**: `docs/edith/requirements.md` (or `PRD.md`/`PDR.md` per repo convention)
- **Technical design**: `docs/edith/technical-design.md`
- **Implementation plan**: `docs/edith/implementation-plan.md`
- **Test plan**: `docs/edith/test-plan.md`
- **Deployment runbook**: `docs/edith/deployment-runbook.md`
- **Release record**: `docs/edith/release-record.md`
- **Research brief**: `docs/edith/research-brief.md`
- **Threat model**: `docs/edith/threat-model.md`
- **Decision log**: `docs/edith/decision-log.md`
- **Individual ADRs**: `docs/edith/adr-*.md`

## Templates
Reusable templates for each artifact type are found in `docs/edith/templates/`. Copy a template to the appropriate location and fill in the specifics.

## Quality Rubrics
Checklists for reviewing artifacts are in the `standards/` directory at the repo root:
- `product-quality-rubric.md`
- `requirements-quality-rubric.md`
- `engineering-review-rubric.md`
- `security-review-rubric.md`
- `deployment-readiness-rubric.md`

## Specialist Agents & Skills
Specialist agents (product‑manager, security‑engineer, etc.) are defined in `.claude/agents/`.  
The main Edith workflow skill is in `.claude/skills/edith/SKILL.md`.

## Safety
Edith will never take consequential actions (e.g., installing dependencies, deploying) without your explicit approval. She will always explain what will happen and ask for confirmation before proceeding.

---
*Edith is a reusable workflow—adapt the structure to your repository’s needs.*