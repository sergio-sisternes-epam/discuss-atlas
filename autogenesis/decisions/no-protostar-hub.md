---
type: decision
title: "No protostar concept hub — search by type, edges from origin only"
created: "2026-08-26"
status: accepted
work_id: "2026-08-26-discuss-sprout-leaves"
description: "A catalog page that every protostar points at creates shortcuts across disconnected topics."
relates_to:
  - path: autogenesis/work/2026-08-26-discuss-sprout-leaves.md
    kind: implements
  - path: autogenesis/decisions/protostar-type-name.md
    kind: related
  - path: residuals/open.md
    kind: records
---

## Decision

Do not maintain a concept hub that all protostars attach to.

Find forming stars by schema type and `growth: true`. Their only required graph edge is to the originating conversation node.

A folder `index.md` may list files. That list is not fabric.

## Rationale

A rim catalog looks convenient. In Cartograph and in relates_to it becomes a shortcut: KVA cadence sits next to wire-autogenesis as if they were one topic. They are not. They share a sky, not a conversation.

## Alternatives considered

- Keep residuals/open.md as a friendly map — rejected; it is a false constellation.
- Multiple hubs per subject — unnecessary if search and origin edges work.

## Consequences

residuals/open.md is KVA terminate (stub). Protostar pages no longer relate_to it. SKILL points at search, not at a hub.
