---
type: decision
title: "Sustituciones explícitas y condicionadas"
created: "2026-09-14"
work_id: "2026-09-14-cocina-atlas-schema"
status: settled
kva: alive
reality: current
description: "Las sustituciones se modelarán como alternativas explícitas con condiciones y posibles efectos culinarios."
origin: user
sensitivity: internal
relates_to:
  - path: cocina/recipe-ingredients.md
    kind: follows
  - path: cocina/utensil-inventory.md
    kind: related
  - path: autogenesis/work/2026-09-14-cocina-atlas-schema.md
    kind: implements
---

## Decision

Una sustitución relacionará un ingrediente requerido con una alternativa y
podrá declarar condiciones, proporción, limitaciones y efecto esperado en el
resultado.

## Consequence

El motor de recomendaciones podrá distinguir entre una receta plenamente
disponible y otra posible solo mediante una sustitución con consecuencias.
