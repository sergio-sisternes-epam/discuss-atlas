---
type: decision
title: "Separar ingredientes conceptuales de existencias concretas"
created: "2026-09-14"
work_id: "2026-09-14-cocina-atlas-schema"
status: settled
kva: alive
reality: current
description: "Un ingrediente reutilizable se separará de sus lotes o existencias concretas con cantidad, origen y caducidad."
origin: user
sensitivity: internal
relates_to:
  - path: cocina/planning-goal.md
    kind: follows
  - path: cocina/quantity-model.md
    kind: related
  - path: autogenesis/work/2026-09-14-cocina-atlas-schema.md
    kind: implements
---

## Decision

El Atlas tendrá una definición conceptual de ingrediente y registros separados
para las existencias concretas de la despensa. Una existencia podrá conservar
cantidad, unidad, lote, fecha de compra, caducidad y ubicación.

## Consequence

Las recetas podrán referirse al mismo ingrediente sin duplicar información,
mientras que la disponibilidad se calculará sobre existencias reales y
consumibles.
