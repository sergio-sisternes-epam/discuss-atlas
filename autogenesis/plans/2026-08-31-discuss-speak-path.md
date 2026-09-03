---
type: plan
title: "Design — always-on discuss speak path"
created: "2026-08-31"
work_id: "2026-08-31-discuss-speak-path"
status: done
change_class: new-surface
subject: discuss
kva: alive
description: "Add a mandatory speak path so discuss cannot talk to a human without loading sentence-shape rules."
plan_path: autogenesis/plans/2026-08-31-discuss-speak-path.md
catalogue_review: in-scope
behavioural_contract: deferred: direction first; specify after approval
relates_to:
  - path: autogenesis/work/2026-08-31-discuss-speak-path.md
    kind: implements
  - path: autogenesis/plans/2026-08-29-discuss-human-narration.md
    kind: follows
  - path: autogenesis/experiences/2026-08-29-feedback-discuss-hard-to-read.md
    kind: related
---

## Intent + scope

Add an always-on speak path. Load it on every discuss Enter, before any user-facing text. Sentence-shape rules live in human-turn.md.

## Pins

- Problem is sentence structure, not jargon.
- speak is a mandatory prefix, not a third public mode.
- Enforce the load in Enter and in the path receipt.

## Acceptance

Discuss Enter without speak is incomplete. Rules name sentence shape, with a good/bad pair.
