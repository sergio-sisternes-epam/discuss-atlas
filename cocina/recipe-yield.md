---
type: decision
title: "Rendimiento esperado de recetas y preparaciones"
created: "2026-09-14"
work_id: "2026-09-14-cocina-atlas-schema"
status: settled
kva: alive
reality: current
description: "Las recetas y preparaciones conservarán el rendimiento esperado además de cantidades y raciones."
origin: user
sensitivity: internal
relates_to:
  - path: cocina/recipe-input-output.md
    kind: follows
  - path: cocina/recipe-scaling.md
    kind: related
  - path: autogenesis/work/2026-09-14-cocina-atlas-schema.md
    kind: implements
---

## Decision

Las recetas podrán declarar rendimiento esperado, como número de raciones,
masa, volumen o unidades producidas, además de sus cantidades de entrada.

## Consequence

Las preparaciones resultantes podrán convertirse en existencias cuantificables
y usarse como entradas de otras recetas.
