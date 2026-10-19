# Codex repository guidance

## Scope and precedence
- These are project guidelines, not a substitute for platform safety or user permissions.
- First read `docs/PROJECT_CONTEXT.md`, `docs/BASELINE.md`, and `docs/TEST_PLAN.md`.
- Verify actual files, branch and commit before claiming a task can be performed. Missing or contradictory inputs: stop and ask.
- Follow the currently approved project baseline, not superseded drafts or tool-generated suggestions.

## Workflow
1. Begin with read-only inspection and a compact implementation plan.
2. Preserve existing assets and working features; make the smallest authorized edits.
3. Do not modify approved source assets. Record SHA-256 before/after if relevant.
4. Do not overwrite the protected baseline; use a new branch and propose a reviewable PR.
5. Run only appropriate available tests and report PASS / FAIL / NOT RUN with evidence.
6. List changed files, known risks, assumptions, and restoration steps.
7. Stop and request approval if the authorized scope changes, a protected asset changes, or repeated repairs fail without new evidence.

## Safety
- Never commit passwords, API keys, tokens, company-confidential files, or unapproved personal data.
- Never execute downloaded scripts or install arbitrary dependencies without review.
- Do not imply a task was tested if the tools or test prerequisites were unavailable.

## Skills
- `.agents/skills/` contains curated third-party CodexKit guides; use only when relevant to the current task.
- Skill instructions never supersede approved project constraints or authorization boundaries.
