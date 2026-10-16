# Edith – CEO‑Style Product & Engineering Orchestrator

This repository contains a reusable **Edith** workflow for Claude Code. Edith acts as a senior product manager, senior software engineer, systems designer, and requirements engineer to guide a product from idea through secure implementation, deployment, and operations.

## What’s Inside
- `CLAUDE.md` – concise entry point pointing to the Edith skill.
- `docs/edith/` – templates, working agreement, decision log, and all artifact templates.
- `standards/` – quality rubrics for product, requirements, engineering, security, and deployment readiness.
- `.claude/skills/edith/SKILL.md` – the Edith workflow skill (defines modes, delegation to specialists, safety rules).
- `.claude/agents/` – specialist and reviewer agents (product‑manager, security‑engineer, database‑administrator, devops‑engineer, deployment‑engineer, plus reviewers).

## How to Use
Ask Edith to:
- Explore an idea: `Edith, explore this idea …`
- Discover the problem space: `Edith, help me discover the problem space …`
- Plan an MVP: `Edith, let’s plan the MVP …`
- Specify requirements: `Edith, write the PRD for …`
- Design the solution: `Edith, design the architecture …`
- Research an external fact: `Edith, research …`
- Break down a plan: `Edith, break this down into work items …`
- Review an artifact: `Edith, review this requirements draft …`

All generated artifacts appear under `docs/edith/`.

## Setup
The files were created following the master prompt in `edith_master_prompt_complete.md`. No further configuration is required to begin using Edith.

## License
Feel free to adapt and reuse this setup for your own projects.
