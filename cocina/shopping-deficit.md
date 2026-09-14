---
type: decision
title: "Lista de compra basada en déficit real"
created: "2026-09-14"
work_id: "2026-09-14-cocina-atlas-schema"
status: settled
kva: alive
reality: current
description: "La lista de compra calculará solo la cantidad faltante después de descontar las existencias actuales."
origin: user
sensitivity: internal
relates_to:
  - path: cocina/recipe-provenance.md
    kind: follows
  - path: cocina/pantry-state.md
    kind: related
  - path: autogenesis/work/2026-09-14-cocina-atlas-schema.md
    kind: implements
---

## Decision

Para una receta o menú, la lista de compra calculará el déficit entre los
ingredientes requeridos y las existencias disponibles.

## Consequence

La lista evitará duplicar compras y podrá explicar qué parte de cada producto
ya estaba en casa y qué cantidad falta para cocinar.
