---
type: decision
title: "Recetas con entradas y salidas explícitas"
created: "2026-09-14"
work_id: "2026-09-14-cocina-atlas-schema"
status: settled
kva: alive
reality: current
description: "Una receta podrá consumir ingredientes o existencias y producir preparaciones o raciones."
origin: user
sensitivity: internal
relates_to:
  - path: cocina/core-entities.md
    kind: follows
  - path: cocina/prepared-foods.md
    kind: related
  - path: autogenesis/work/2026-09-14-cocina-atlas-schema.md
    kind: implements
---

## Decision

Una receta declarará entradas y salidas. Las entradas representan ingredientes
o existencias consumidas; las salidas representan preparaciones o raciones
producidas, con sus cantidades y fechas derivadas cuando proceda.

## Consequence

Una receta puede alimentar el inventario de productos preparados y otra receta
puede consumirlos posteriormente. El linaje entre compra, transformación y
consumo queda explícito.
