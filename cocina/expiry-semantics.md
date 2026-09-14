---
type: decision
title: "Caducidad y consumo preferente como fechas distintas"
created: "2026-09-14"
work_id: "2026-09-14-cocina-atlas-schema"
status: settled
kva: alive
reality: current
description: "El inventario distinguirá fecha de caducidad y consumo preferente y las usará con distinta prioridad."
origin: user
sensitivity: internal
relates_to:
  - path: cocina/storage-locations.md
    kind: follows
  - path: cocina/planning-goal.md
    kind: related
  - path: autogenesis/work/2026-09-14-cocina-atlas-schema.md
    kind: implements
---

## Decision

Las existencias podrán tener fecha de caducidad y fecha de consumo preferente
como datos distintos. Las recomendaciones priorizarán los productos próximos a
caducar y tratarán el consumo preferente como una señal flexible.

## Consequence

El Atlas podrá separar advertencias de seguridad alimentaria de sugerencias de
aprovechamiento. Las recetas no deben recomendar automáticamente un producto
caducado.
