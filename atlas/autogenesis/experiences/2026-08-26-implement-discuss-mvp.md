---
type: experience
title: "Implement discuss MVP v0.1.0"
created: "2026-08-26"
work_id: "2026-08-26-discuss-mvp"
implements: "2026-08-26-discuss-mvp"
closes: "2026-08-26-discuss-mvp"
plan_path: autogenesis/plans/2026-08-26-discuss-mvp.md
construct_eval: deferred
status: settled
description: "Implement experience for the first discuss MVP. Construct full loop deferred pending agent-spec specify."
origin: internal
sensitivity: internal
relates_to:
  - path: autogenesis/work/2026-08-26-discuss-mvp.md
    kind: implements
  - path: autogenesis/plans/2026-08-26-discuss-mvp.md
    kind: follows
---

## Context

User approved implement of plan 2026-08-26-discuss-mvp after design stop-for-approval. Change-class new-skill. Behavioural Gherkin remains deferred to agent-spec specify.

## What happened

Rewrote SKILL.md from the pinned plan (P1–P13). Seeded thesis, residuals, and founding graph. Added KVA inception (already present). Materialised discuss-adversarial-v1.yaml from the design draft. Did not wire discuss into Autogenesis. Did not run a full construct loop because specify has not produced b- IDs yet.

## Outcome

discuss v0.1.0 MVP is on disk. Subject Atlas compile must be green. Construct evaluation deferred until agent-spec specify and a construct run can score the adversarial suite.

## Changed files

- `/home/workdir/.grok/skills/discuss/SKILL.md` — rewritten from approved plan
- `/home/workdir/.grok/skills/discuss/references/atlas/index.md`
- `/home/workdir/.grok/skills/discuss/references/atlas/thesis/index.md`
- `/home/workdir/.grok/skills/discuss/references/atlas/thesis/current-reality.md`
- `/home/workdir/.grok/skills/discuss/references/atlas/residuals/index.md`
- `/home/workdir/.grok/skills/discuss/references/atlas/residuals/open.md`
- `/home/workdir/.grok/skills/discuss/references/atlas/founding/index.md`
- `/home/workdir/.grok/skills/discuss/references/atlas/founding/hub.md`
- `/home/workdir/.grok/skills/discuss/references/scenarios/discuss-adversarial-v1.yaml`
- `/home/workdir/.grok/skills/discuss/references/atlas/autogenesis/experiences/2026-08-26-implement-discuss-mvp.md`
- `/home/workdir/.grok/skills/discuss/references/atlas/autogenesis/work/2026-08-26-discuss-mvp.md`
- `/home/workdir/.grok/skills/discuss/references/atlas/log.md`

## Follow-ups

- agent-spec specify for b- IDs
- construct run of discuss-adversarial-v1
- optional Autogenesis wire of discuss
