---
type: experience
title: "Q6 — Fail-fast if discussion does not load discuss"
created: "2026-08-26"
work_id: "2026-08-26-autogenesis-discuss-activation"
status: settled
kva: alive
reality: current
description: "Pinned: discussion-mode Enter without loading discuss is incomplete."
tags: [wire, fail-fast, q6]
origin: derived
sensitivity: internal
relates_to:
  - path: wire/q5-wire-tension.md
    kind: follows
  - path: wire/orbit-activation-path.md
    kind: derived_from
  - path: autogenesis/work/2026-08-26-autogenesis-discuss-activation.md
    kind: implements
  - path: wire/scope-planned-deferred.md
    kind: follows
---

## Context

Last batch item. Pins already require Autogenesis path discuss to substrate-load catalog discuss and follow the full body.

## What happened

**A — Incomplete Enter.** `mode: discussion` without loading discuss (and without discuss fields: discussion_root, current_branch, objective, atlas_root) is incomplete. Same family as missing path_module read. Fail closed.

**B — Soft warn.** Agent may talk, then load discuss later. Drift back to the old mechanism.

**C — Defer the gate.** Put the fail-closed rule in the design plan as a protostar / later hardening. Path exists first; G0/G1 tightness later.

## Outcome

User pinned **A**. KVA keep.

Pin: Autogenesis `mode: discussion` without substrate-loading catalog discuss, or without discuss fields (`discussion_root`, `current_branch`, `objective`, `atlas_root`), is incomplete Enter. Fail closed.

Next orbit: wire/scope-planned-deferred.md.
