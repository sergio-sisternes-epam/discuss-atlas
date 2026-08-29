---
type: experience
title: "Implement discuss lint path L1"
created: "2026-08-26"
work_id: "2026-08-26-discuss-lint"
implements: "2026-08-26-discuss-lint"
closes: "2026-08-26-discuss-lint"
plan_path: autogenesis/plans/2026-08-26-discuss-lint.md
construct_eval: deferred
status: settled
description: "Captured no-hub as an operable lint path."
origin: internal
sensitivity: internal
relates_to:
  - path: autogenesis/work/2026-08-26-discuss-lint.md
    kind: implements
  - path: autogenesis/decisions/no-protostar-hub.md
    kind: derived_from
---

## Context

User asked Autogenesis to capture the no-hub concern as a discuss linting action path. First rule: no hub files.

## What happened

Added path lint, scripts/lint.py, SKILL registry. Autogenesis record lives under discuss Atlas autogenesis/.

## Outcome

Lint is part of discuss discipline. More rules need their own design.

## Changed files

- `/home/workdir/.grok/skills/discuss/SKILL.md`
- `/home/workdir/.grok/skills/discuss/references/paths/lint.md`
- `/home/workdir/.grok/skills/discuss/scripts/lint.py`
- `/home/workdir/.grok/skills/discuss/references/atlas/autogenesis/plans/2026-08-26-discuss-lint.md`
- `/home/workdir/.grok/skills/discuss/references/atlas/autogenesis/work/2026-08-26-discuss-lint.md`
- `/home/workdir/.grok/skills/discuss/references/atlas/autogenesis/experiences/2026-08-26-implement-lint.md`
