---
type: decision
title: "Entidades nucleares de la primera versión"
created: "2026-09-14"
work_id: "2026-09-14-cocina-atlas-schema"
status: settled
kva: alive
reality: current
description: "La primera versión tendrá siete entidades principales y tratará menú y lista de compra como capacidades derivadas."
origin: user
sensitivity: internal
relates_to:
  - path: cocina/expiry-semantics.md
    kind: follows
  - path: cocina/hub.md
    kind: related
  - path: autogenesis/work/2026-09-14-cocina-atlas-schema.md
    kind: implements
---

## Decision

Las entidades nucleares serán:

- receta
- ingrediente conceptual
- existencia
- evento de inventario
- utensilio
- persona
- sustitución

La comida planificada y la lista de compra serán capacidades derivadas hasta
que los casos reales demuestren que necesitan identidad y ciclo de vida propios.

## Consequence

El esquema inicial conserva un núcleo pequeño, pero puede calcular
disponibilidad, recomendaciones y déficits de compra a partir de esas
entidades.
