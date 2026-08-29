---
type: plan
title: "Design — discuss human narration (British English, shared picture)"
created: "2026-08-29"
work_id: "2026-08-29-discuss-human-narration"
status: implementing
change_class: hardening
subject: discuss
kva: alive
description: "Chat must narrate the graph in reasonably elaborated British English so mental pictures match. Not a jargon glossary."
plan_path: autogenesis/plans/2026-08-29-discuss-human-narration.md
catalogue_review: in-scope
behavioural_contract: deferred: prose-contract
relates_to:
  - path: autogenesis/experiences/2026-08-29-feedback-discuss-hard-to-read.md
    kind: derived_from
  - path: autogenesis/work/2026-08-29-discuss-human-narration.md
    kind: implements
---

## Intent + scope

Harden discuss chat output. The human already knows the terms. Turns were too short, so the picture in their head diverged from the Atlas. Fix: plain British English, reasonably elaborated sentences, enough graph context to share one picture.

Out of scope: new-user glossary mode; changing KVA or path registry; implement of Atlas product.

## Pinned decisions

- P1 Narration defect, not jargon defect.
- P2 Length: complete sentences; not telegraphic; not an essay.
- P3 Each turn states where we are, what is live, what was set aside and why, then the ask.
- P4 Process cards may exist; they must not replace the prose.

## Acceptance

A discuss turn on an open lean can be restated by the user in their own words and match the stored node.

## Stop

User asked to fix in this side quest, then resume Atlas to test.
---
