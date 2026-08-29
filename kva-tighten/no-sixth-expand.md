---
type: experience
title: "Counter — do not add expand as a sixth KVA state"
created: "2026-08-26"
work_id: "2026-08-26-kva-protostar-tighten"
status: probed
kva: alive
reality: current
description: "expand on a mature branch is alive + forming children. A sixth value recreates the dual-field mess."
tags: [kva, probe]
origin: derived
sensitivity: internal
stage: discussion
artifact: kva-tighten/no-sixth-expand.md
relates_to:
  - path: kva-tighten/five-state-alive.md
    kind: counters
  - path: kva-tighten/five-state-alive.md
    kind: derived_from
  - path: kva-tighten/hub.md
    kind: related
  - path: autogenesis/work/2026-08-26-kva-protostar-tighten.md
    kind: implements
---

## Context

User: expand is a good signal that a branch is mature but needs more work. Maybe a sixth state. Or active already means expanding. Or rename active to alive.

## What happened

The original defect was two fields sharing keep / expand / terminate / open / settled. Adding `expand` next to `forming` and `alive` splits “not done” into two statuses that lint cannot tell apart.

- **forming** = this node is not fit for use yet
- **alive** = this node is fit for use, and living things grow
- “needs more work” = one or more **forming children** off an origin, not a parent status

If a mature thesis is still growing, the thesis stays `alive`. New questions sprout as `forming`. That is already the protostar model.

A sixth value would force every in-discussion hub to choose forming vs expand vs alive with no machine test. That is the looseness we opened this graph to kill.

Rename **active → alive** is the part to keep. It matches the sky metaphor (protostar → living star) and answers the growth question without another enum slot.

## Outcome

KVA expand on the *recommendation* (do not add a sixth). Recommendation is not a pin until the user accepts or overrides.
