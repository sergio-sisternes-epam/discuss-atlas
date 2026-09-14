---
type: decision
title: "Ubicaciones físicas de las existencias"
created: "2026-09-14"
work_id: "2026-09-14-cocina-atlas-schema"
status: settled
kva: alive
reality: current
description: "Las existencias conservarán su ubicación física y podrán dividirse entre varias ubicaciones."
origin: user
sensitivity: internal
relates_to:
  - path: cocina/purchase-records.md
    kind: follows
  - path: cocina/ingredient-inventory-separation.md
    kind: related
  - path: autogenesis/work/2026-09-14-cocina-atlas-schema.md
    kind: implements
---

## Decision

Cada existencia podrá registrar una o varias ubicaciones físicas, como
despensa, nevera, congelador o armario.

## Consequence

Las recomendaciones podrán considerar accesibilidad y ubicación, y el
inventario podrá representar un mismo producto repartido en varios lugares.
