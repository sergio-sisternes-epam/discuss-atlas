---
type: experience
title: "Q1 — Autogenesis activation shape for discuss"
created: "2026-08-26"
work_id: "2026-08-26-autogenesis-discuss-activation"
status: settled
kva: alive
reality: current
description: "Pinned: Autogenesis gains path_id discuss. Path module substrate-loads catalog skill discuss."
tags: [wire, activation-shape, q1]
origin: user
sensitivity: internal
relates_to:
  - path: wire/orbit-activation-path.md
    kind: derived_from
  - path: wire/hub.md
    kind: follows
  - path: autogenesis/work/2026-08-26-autogenesis-discuss-activation.md
    kind: implements
  - path: wire/q2-graph-home.md
    kind: follows
---

## Context

User asked for one question at a time. Fork 1 is now current_branch.

## What happened

Two shapes are on the table. Only this fork is open.

**A — New Autogenesis path_id `discuss`.**  
Registry row, `references/paths/discuss.md`, Enter `path: discuss`. Discussion mode selects that path (default when mode is discussion). The path module’s only job is substrate-load discuss and follow it. Matches how design/implement are loaded. Extra path to keep in sync.

**B — Mode-triggered must-load, no new path_id.**  
`mode: discussion` itself requires loading discuss before any talk. Card gains discuss fields. Existing path (often design) stays on the card as the *eventual* Run path but has zero discussion-mode authority. Fewer moving parts; risk of mixing “we are discussing a design” with “we are on path design.”

**C — Out of scope this node.** Defaulting Autogenesis Run path to discuss, or auto-wiring files, is not this question.

## Outcome

User pinned **A**. KVA keep.

Pin: Autogenesis adds `path_id: discuss` at `references/paths/discuss.md`. When discussing, Enter is `mode: discussion`, `path: discuss`. That path’s job is the substrate contract on catalog skill `discuss`, then full discuss discipline. No thin shim.

Consequence left on this page, not a new fork: path name and catalog skill name collide in speech (“discuss”). The registry must say path vs skill. Default Autogenesis Run path stays `design`.

Next orbit: wire/q2-graph-home.md.
