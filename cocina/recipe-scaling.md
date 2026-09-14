---
type: decision
title: "Recetas con raciones y escalado proporcional"
created: "2026-09-14"
work_id: "2026-09-14-cocina-atlas-schema"
status: settled
kva: alive
reality: current
description: "Las recetas declararán raciones y permitirán escalar proporcionalmente sus cantidades."
origin: user
sensitivity: internal
relates_to:
  - path: cocina/recipe-ingredients.md
    kind: follows
  - path: cocina/quantity-model.md
    kind: related
  - path: autogenesis/work/2026-09-14-cocina-atlas-schema.md
    kind: implements
---

## Decision

Cada receta conservará un número base de raciones. Sus cantidades de
ingredientes podrán calcularse para otro número de comensales mediante
escalado proporcional.

## Consequence

Una misma receta sirve para distintos tamaños de comida sin duplicar fichas.
Las cantidades no lineales o los límites prácticos podrán registrarse como
excepciones cuando aparezcan casos reales.
