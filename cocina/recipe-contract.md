---
type: decision
title: "Contrato mínimo de una página de receta"
created: "2026-09-14"
work_id: "2026-09-14-cocina-atlas-schema"
status: settled
kva: alive
reality: current
description: "Una receta exigirá nombre, descripción, raciones, ingredientes, pasos, tiempo, dificultad, utensilios y alérgenos."
origin: user
sensitivity: internal
relates_to:
  - path: cocina/existence-record-granularity.md
    kind: follows
  - path: cocina/recipe-method.md
    kind: related
  - path: autogenesis/work/2026-09-14-cocina-atlas-schema.md
    kind: implements
---

## Decision

Los campos obligatorios de una receta serán nombre, descripción, raciones,
ingredientes, pasos, tiempo, dificultad, utensilios y alérgenos.

## Consequence

Cada receta será suficientemente operativa para cocinarla, evaluarla contra la
despensa y filtrarla por restricciones de seguridad o preferencias.
