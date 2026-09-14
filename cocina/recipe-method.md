---
type: decision
title: "Método de receta estructurado por pasos"
created: "2026-09-14"
work_id: "2026-09-14-cocina-atlas-schema"
status: settled
kva: alive
reality: current
description: "Cada receta tendrá pasos ordenados con tiempos, temperaturas, técnicas y utensilios asociados."
origin: user
sensitivity: internal
relates_to:
  - path: cocina/recipe-scaling.md
    kind: follows
  - path: cocina/hub.md
    kind: related
  - path: autogenesis/work/2026-09-14-cocina-atlas-schema.md
    kind: implements
---

## Decision

El método de preparación se compondrá de pasos ordenados. Cada paso podrá
declarar técnica, duración, temperatura y utensilios requeridos.

## Consequence

Las recetas serán consultables por técnica o tiempo y podrán advertir de
requisitos concretos antes de cocinar. El texto explicativo seguirá siendo
posible como apoyo, pero no será la única representación del procedimiento.
