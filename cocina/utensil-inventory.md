---
type: decision
title: "Inventario de utensilios disponibles"
created: "2026-09-14"
work_id: "2026-09-14-cocina-atlas-schema"
status: settled
kva: alive
reality: current
description: "El Atlas registrará los utensilios disponibles y los comparará con los requisitos de cada receta."
origin: user
sensitivity: internal
relates_to:
  - path: cocina/recipe-method.md
    kind: follows
  - path: cocina/hub.md
    kind: related
  - path: autogenesis/work/2026-09-14-cocina-atlas-schema.md
    kind: implements
---

## Decision

Los utensilios serán entidades del dominio. El inventario doméstico indicará
cuáles están disponibles y cada paso de receta podrá declarar qué utensilios
requiere.

## Consequence

La evaluación de una receta podrá informar por separado de ingredientes
faltantes y utensilios faltantes, y podrá sugerir recetas alternativas que sí
sean ejecutables.
