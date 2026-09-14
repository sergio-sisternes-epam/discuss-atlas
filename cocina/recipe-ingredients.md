---
type: decision
title: "Líneas estructuradas de ingredientes en las recetas"
created: "2026-09-14"
work_id: "2026-09-14-cocina-atlas-schema"
status: settled
kva: alive
reality: current
description: "Cada receta expresará sus ingredientes como líneas estructuradas con cantidad, unidad, opcionalidad y sustituciones."
origin: user
sensitivity: internal
relates_to:
  - path: cocina/ingredient-inventory-separation.md
    kind: follows
  - path: cocina/quantity-model.md
    kind: related
  - path: autogenesis/work/2026-09-14-cocina-atlas-schema.md
    kind: implements
---

## Decision

Una receta tendrá líneas de ingredientes estructuradas. Cada línea podrá
referirse a un ingrediente conceptual y declarar cantidad, unidad, si es
opcional y qué sustituciones son aceptables.

## Consequence

El Atlas podrá distinguir requisitos obligatorios de preferencias y comparar
cada requisito con el inventario. Las sustituciones deberán modelarse como
alternativas explícitas, no ocultarse en una nota de texto.
