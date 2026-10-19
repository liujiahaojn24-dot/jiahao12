# Codex Cloud Curated Starter (repository-level, non-executable)

This is a curated subset of **CodexKit starter pack v0.10.0**, selected for codebase onboarding, planning, defect isolation, regression checks, review, decisions, delegation, and business-process mapping.

## Quick start
1. Download and extract this ZIP.
2. Copy `AGENTS.md`, `.agents/`, and `docs/` **into the root of an existing GitHub project** (do not overwrite existing files without reviewing differences). GitHub's web upload may hide dot-directories in some file picker views; use Git or another upload flow that preserves them.
3. Edit the **template** files in `docs/` to identify the real approved code version, assets, risks and tests.
4. Connect that GitHub repository to a Codex Cloud environment (GitHub authorization and environment setup are independent from this ZIP).
5. Start with a read-only task: inspect repository, detect relevant skills, describe run instructions and test availability; do not edit.

## Included skills
- codexkit-repo-onboarding
- codexkit-execution-planner
- codexkit-bug-hunt
- codexkit-test-hardening
- codexkit-high-signal-review
- codexkit-architecture-decision-writer
- codexkit-cloud-delegation
- codexkit-process-mapper

## Deliberately not included
- Windows installer, global configuration writer, auto-updaters, automation schedules, MCP servers, or external executables.
- Test-hardening's shell helper script was also excluded. The skill's markdown guidance remains usable.
- No project dependencies or CI config are installed. Tests depend on your real project.

## Security and provenance
The selected skill texts came from the user-provided archive `codexkit-starter-pack-v0.10.0.zip`. They are **community instructions**, not OpenAI-reviewed guarantees. Audit them before use. The `THIRD_PARTY_NOTICE.md` file identifies the origin and licensing reference.
