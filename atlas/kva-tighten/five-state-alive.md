---
type: experience
title: "Pin candidate — five KVA states, alive not active, exit-reason node"
created: "2026-08-26"
work_id: "2026-08-26-kva-protostar-tighten"
status: in-discussion
kva: alive
reality: current
description: "forming, alive, deprecated, superseded, terminated. Exit ramps share a final reason node. No sixth expand state."
tags: [kva]
origin: user
sensitivity: internal
stage: discussion
artifact: kva-tighten/five-state-alive.md
relates_to:
  - path: kva-tighten/four-state-reason-edges.md
    kind: follows
  - path: kva-tighten/four-state-reason-edges.md
    kind: derived_from
  - path: kva-tighten/no-sixth-expand.md
    kind: counters
  - path: kva-tighten/hub.md
    kind: related
  - path: autogenesis/work/2026-08-26-kva-protostar-tighten.md
    kind: implements
---

## Context

User took the three hanging tensions: grow superseded to a fifth state; keep a final node that holds exit context; ask whether expand is a sixth state or whether alive already grows.

## What happened

### Five values of `kva`

| `kva` | Test | Use |
|---|---|---|
| forming | not yet fit for use | protostars; immature branches |
| alive | fit for use now | current reality; may grow forming children |
| deprecated | was alive; no longer; no successor | do not use; keep scar |
| superseded | was alive; replaced by a later node | do not use; keep scar; point at successor |
| terminated | never fit, failed, or out of scope | do not use; keep scar |

Rename: **alive** replaces **active**. Alive things grow. Growth is not a sibling status.

### Three exit ramps, one kind of final node

Deprecated, superseded, and terminated each require a **final node** (exit-reason page). That page holds the context you need to revisit or recover the kill.

- Never embed the reason on the subject.
- Subject → final node with exactly one of: `kva_deprecate` | `kva_supersede` | `kva_terminate`.
- Final node `kva` is **alive** (the explanation stays usable).
- Same-event fan-in allowed. Generic catalog reason forbidden (L1).
- Superseded also needs a successor pointer (subject `follows` or later `kva_successor` — not pinned this turn). The final node recovers *why*; the successor edge recovers *what replaced it*.

Reactivation remains a new forming page `derived_from` the stub. Stub stays on its exit state.

### Expand is not a sixth state

See kva-tighten/no-sixth-expand.md. Mature-but-still-growing is `alive` plus forming children.

## Outcome

KVA expand (legacy field on this page until design lands). Candidate pin is five states + alive + required final node. Not current reality until user accepts the no-sixth recommendation.
