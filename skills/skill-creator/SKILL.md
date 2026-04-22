---
name: skill-creator
description: "Packaging-layer comparison companion for the canonical skill-creator skill. Use /Users/slbb1995/.codex/skills/.system/skill-creator/SKILL.md as the provider of record; keep this copy only for eval, benchmark, and packaging resources."
license: Complete terms in LICENSE.txt
---

# skill-creator Packaging Layer

Runtime status: packaging-layer companion only.
Canonical owner: `/Users/slbb1995/.codex/skills/.system/skill-creator/SKILL.md`

Use the canonical owner when:
- creating or updating a skill for normal production use
- you need the maintained provider of record for skill-authoring workflows
- you want the `.system` trigger path and primary quick-validation flow

Keep this wrapper only for:
- comparison, eval, and benchmark companion workflows
- compatibility with older references to `anthropics-skills/skills/skill-creator`
- preserving package-local packaging and review assets that still have value beside the canonical owner

Companion resources kept in this directory:
- `agents/analyzer.md`, `agents/comparator.md`, `agents/grader.md`
- `assets/eval_review.html`
- `eval-viewer/generate_review.py`, `eval-viewer/viewer.html`
- `references/schemas.md`
- `scripts/aggregate_benchmark.py`, `scripts/generate_report.py`, `scripts/improve_description.py`
- `scripts/package_skill.py`, `scripts/quick_validate.py`, `scripts/run_eval.py`, `scripts/run_loop.py`, `scripts/utils.py`
- `LICENSE.txt`

Use this wrapper only when:
- you are explicitly reviewing historical Anthropic skill-creator behavior
- you are running eval or comparison tooling rooted in this directory
- you need the packaging helper flow that still lives beside these assets

Do not treat this file as an independent provider of record.
