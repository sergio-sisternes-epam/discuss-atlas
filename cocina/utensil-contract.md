---
type: decision
title: "Contrato mínimo de un utensilio"
created: "2026-09-14"
work_id: "2026-09-14-cocina-atlas-schema"
status: settled
kva: alive
reality: current
description: "Un utensilio tendrá nombre, categoría, capacidades o límites, disponibilidad y sustitutos posibles."
origin: user
sensitivity: internal
relates_to:
  - path: cocina/ingredient-contract.md
    kind: follows
  - path: cocina/utensil-inventory.md
    kind: related
  - path: autogenesis/work/2026-09-14-cocina-atlas-schema.md
    kind: implements
---

## Decision

La página de utensilio declarará nombre, categoría, capacidades o límites,
estado de disponibilidad y posibles sustitutos.

## Consequence

La evaluación de una receta podrá detectar incompatibilidades de capacidad,
además de simples ausencias, y explicar alternativas de equipamiento.
