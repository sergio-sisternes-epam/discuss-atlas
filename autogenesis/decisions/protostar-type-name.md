---
type: decision
title: "Type name is protostar, not residual or leaf"
created: "2026-08-26"
status: accepted
work_id: "2026-08-26-discuss-sprout-leaves"
description: "Pinned naming. Pending growth nodes are protostars on the Atlas sky."
relates_to:
  - path: autogenesis/plans/2026-08-26-discuss-sprout-leaves.md
    kind: related
  - path: autogenesis/decisions/kva-inception.md
    kind: related
---

## Decision

The schema type for a pending growth node is **protostar**.

Not `residual` (sounds like scrap). Not `leaf` (tree, not sky).

A protostar is a forming idea: mass gathered from a conversation, not yet shining as current reality. It keeps an origin edge to the node that condensed it.

The path that creates them remains **sprout** until separately pinned. Kind of pending (refine, question, counter, probe, tension, action) is a field, not a second schema type.

## Rationale

Atlas/Cartograph language is a sky: star-map, galaxy, hyperspace. The founding conversation already called new ideas new stars after the Big Bang. Protostar is the young-star name for something still forming.

## Alternatives considered

- residual — accurate for leftovers, weak as a first-class growth role
- leaf — graph-theory accurate, wrong metaphor
- star — collides with settled nodes
- frontier / uncharted — cartograph-good, less “forming idea”

## Consequences

Implement of 2026-08-26-discuss-sprout-leaves must use `type: protostar`, migrate the eleven current residual pages, and search via `growth: true` plus the new type.
