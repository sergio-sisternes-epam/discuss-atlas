---
type: experience
title: "Implement discuss speak path 0.3.6"
created: 2026-08-31
work_id: 2026-08-31-discuss-speak-path
implements: 2026-08-31-discuss-speak-path
closes: 2026-08-31-discuss-speak-path
plan_path: autogenesis/plans/2026-08-31-discuss-speak-path.md
construct_eval: deferred
status: settled
kva: alive
origin: internal
sensitivity: internal
description: "Shipped the always-on speak prefix and human-turn sentence rules in the discuss package."
relates_to:
  - path: autogenesis/work/2026-08-31-discuss-speak-path.md
    kind: implements
  - path: autogenesis/plans/2026-08-31-discuss-speak-path.md
    kind: records
---

## Context

User approved a first-stage speak path after correcting sentence shape.

## What happened

Discuss 0.3.6. Speak is the always-on prefix. human-turn.md holds the sentence rules.

## Outcome

Path shipped in the discuss package. Construct deferred.

## Changed files

These live in the discuss skill package, not this store:

- `/home/workdir/.grok/skills/discuss/references/paths/speak.md`
- `/home/workdir/.grok/skills/discuss/references/human-turn.md`
- `/home/workdir/.grok/skills/discuss/SKILL.md`
