---
type: experience
title: "Proposal — KVA has three states: forming, active, terminated"
created: "2026-08-26"
work_id: "2026-08-26-kva-protostar-tighten"
status: in-discussion
kva: alive
reality: current
description: "User pin candidate. One KVA field. Three values. No delete. Termination carries a reason. Reactivation is a branch, not an erase."
tags: [kva, protostar]
origin: user
sensitivity: internal
stage: discussion
artifact: kva-tighten/three-state-kva.md
relates_to:
  - path: kva-tighten/looseness-inventory.md
    kind: derived_from
  - path: kva-tighten/looseness-inventory.md
    kind: follows
  - path: kva-tighten/hub.md
    kind: related
  - path: protostars/kva-statuses.md
    kind: related
  - path: kva-tighten/challenge-three-state-kva.md
    kind: counters
  - path: autogenesis/work/2026-08-26-kva-protostar-tighten.md
    kind: implements
---

## Context

User simplified the loose enum. Engaged batch items 1 and 2 from looseness-inventory.

## What happened

Proposed KVA values:

- **forming** — something new that is maturing
- **active** — matured; safe to use; may grow with forming nodes
- **terminated** — no longer of use; must not be actively used; never deleted; termination reason is required; may be reactivated later by a subtle new branch

Human analogue: build → evaluate → terminate for a reason. Keep the scar. Both what worked and what failed stay on the map.

Working mapping against current fields (not yet pinned):

| Proposed `kva` | Replaces today | Typical type |
|---|---|---|
| forming | `kva: expand` + `status: open` + `growth: true` | protostar |
| active | `kva: keep` + `status: settled` / in-discussion current reality | experience, decision, document, work |
| terminated | `kva: terminate` + stub kept | any, including former protostar |

Implication if pinned: one field owns lifecycle. `status` as a second overlapping enum is the defect to kill. `growth: true` becomes a derived view of `kva: forming` (or forming+active, to be pinned). `done` is rejected as a KVA value.

## Outcome

KVA expand. This is the candidate pin, not current reality yet. Challenge page is the next orbit: kva-tighten/challenge-three-state-kva.md
