---
type: decision
title: "Prioridad inicial: cocinar con lo disponible y evitar caducidades"
created: "2026-09-14"
work_id: "2026-09-14-cocina-atlas-schema"
status: settled
kva: alive
reality: current
description: "La planificación inicial priorizará aprovechar productos próximos a caducar y responder qué se puede cocinar ahora."
origin: user
sensitivity: internal
relates_to:
  - path: cocina/pantry-state.md
    kind: follows
  - path: cocina/hub.md
    kind: related
  - path: autogenesis/work/2026-09-14-cocina-atlas-schema.md
    kind: implements
---

## Decision

La primera capacidad de planificación será identificar recetas cocinables con
lo disponible y dar prioridad a los productos próximos a caducar.

## Consequence

La generación de listas de compra y la planificación de menús de varios días
quedan como capacidades posteriores. El modelo inicial debe hacer fiable la
comparación entre requisitos de receta, existencias y fechas de caducidad.
