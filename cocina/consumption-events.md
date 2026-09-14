---
type: decision
title: "Cocinar y consumir como eventos de inventario"
created: "2026-09-14"
work_id: "2026-09-14-cocina-atlas-schema"
status: settled
kva: alive
reality: current
description: "Cocinar y consumir una receta generará eventos que actualizarán las existencias de la despensa."
origin: user
sensitivity: internal
relates_to:
  - path: cocina/household-profiles.md
    kind: follows
  - path: cocina/pantry-state.md
    kind: related
  - path: autogenesis/work/2026-09-14-cocina-atlas-schema.md
    kind: implements
---

## Decision

La ejecución y el consumo de una receta se registrarán como eventos de
inventario. Esos eventos descontarán las cantidades consumidas y conservarán
la relación con la receta y las existencias afectadas.

## Consequence

La despensa actual podrá reconstruirse desde su historial y las
recomendaciones podrán usar consumos previstos o confirmados sin perder
trazabilidad.
