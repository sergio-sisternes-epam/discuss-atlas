---
type: decision
title: "Despensa como estado actual con historial"
created: "2026-09-14"
work_id: "2026-09-14-cocina-atlas-schema"
status: settled
kva: alive
reality: current
description: "La despensa conservará existencias actuales y un historial de entradas, consumos, desperdicios y caducidades."
origin: user
sensitivity: internal
relates_to:
  - path: cocina/quantity-model.md
    kind: follows
  - path: cocina/hub.md
    kind: related
  - path: autogenesis/work/2026-09-14-cocina-atlas-schema.md
    kind: implements
---

## Decision

La despensa tendrá un estado actual calculable y conservará el historial de
compras, consumos, desperdicios y fechas de caducidad.

## Consequence

Las recomendaciones podrán priorizar productos próximos a caducar y explicar
por qué un ingrediente está o no disponible. El diseño deberá separar los
eventos del inventario de la fotografía materializada de existencias.
