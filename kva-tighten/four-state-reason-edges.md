---
type: experience
title: "Pin candidate — four KVA states and reason-as-node"
created: "2026-08-26"
work_id: "2026-08-26-kva-protostar-tighten"
status: in-discussion
kva: alive
reality: current
description: "Adds deprecated. Termination and deprecation reasons live as graph nodes. Subjects point at them with kva_terminate or kva_deprecate. No reason string on the subject."
tags: [kva, edges]
origin: user
sensitivity: internal
stage: discussion
artifact: kva-tighten/four-state-reason-edges.md
relates_to:
  - path: kva-tighten/challenge-three-state-kva.md
    kind: follows
  - path: kva-tighten/three-state-kva.md
    kind: derived_from
  - path: kva-tighten/hub.md
    kind: related
  - path: autogenesis/work/2026-08-26-kva-protostar-tighten.md
    kind: implements
---

## Context

User accepted the three-state grain, then added a fourth state and moved the reason off the subject page onto the graph.

## What happened

### Four KVA values

- **forming** — new, maturing
- **active** — matured; safe to use; may grow forming children off an origin
- **deprecated** — was useful; no longer is; do not use for new work; do not delete
- **terminated** — not useful as current work (failed, out of scope, never matured); do not use; do not delete

Crisp test: **was this node ever active and fit for use?** Yes → deprecate. No → terminate.

Do not name the fourth state `obsolete`. That word collides with IETF Obsoletes (replaced text) and with software "removed / errors if called". Status name is `deprecated`.

### Reason is a node, not a field

Never embed a reason string on the subject (`kva_reason` on the KVA son is forbidden).

The justification is its own Atlas page. Subjects point at it:

```yaml
relates_to:
  - path: <reason-page>
    kind: kva_terminate   # if subject kva is terminated
  - path: <reason-page>
    kind: kva_deprecate   # if subject kva is deprecated
```

Direction: subject → reason. Many subjects may share one reason page when they share one event.

The reason page is not implement authority. It is a leaf in the conversation: claim-bearing body that states why. Its own `kva` is **active** while it grounds kills. If the reason itself dies, write a new reason page; do not unmute subjects in place.

### Still inherited

- Reactivation = new forming page `derived_from` the stub. Stub stays terminated or deprecated.
- Terminated and deprecated drop out of default growth search.
- `type` and `star_kind` stay off the KVA enum.

## Outcome

KVA expand. Candidate pin now four states + two new edge kinds. Open tensions stay as batch on this page, not yet separate stars.

## Batch (not yet pages)

1. Is **superseded** a fifth KVA value, or only a successor edge (`follows` / new kind `kva_supersede`) on a deprecated node?
2. L1 — when does a shared reason page become a forbidden hub? Same-event fan-in allowed; generic "out of scope" catalog forbidden?
3. Reason page type — experience, document, or protostar?
4. Cadence / value sentence / SCHEMA-required still hanging from the inventory.
