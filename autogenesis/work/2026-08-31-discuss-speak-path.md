---
type: work
title: "Always-on discuss speak path"
created: 2026-08-31
work_id: 2026-08-31-discuss-speak-path
status: done
kva: alive
description: "Mandatory speak path so discuss loads sentence-shape rules before any human reply."
origin: user
sensitivity: internal
relates_to:
  - path: autogenesis/plans/2026-08-31-discuss-speak-path.md
    kind: related
  - path: autogenesis/plans/2026-08-29-discuss-human-narration.md
    kind: follows
---

## Scope

New discuss path `speak`. Always loaded on Enter.

## Status

done — discuss 0.3.6 first stage. Construct deferred.

## Outcomes

- Path `speak` exists in the discuss package.
- Enter is incomplete without `speak_loaded: yes` on the activation card.
- Sentence-shape rules live in `human-turn.md`.
