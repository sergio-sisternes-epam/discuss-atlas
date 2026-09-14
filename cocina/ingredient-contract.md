---
type: decision
title: "Contrato mínimo de un ingrediente conceptual"
created: "2026-09-14"
work_id: "2026-09-14-cocina-atlas-schema"
status: settled
kva: alive
reality: current
description: "Un ingrediente tendrá nombre canónico, sinónimos, categoría, unidades válidas, alérgenos y sustituciones relacionadas."
origin: user
sensitivity: internal
relates_to:
  - path: cocina/recipe-contract.md
    kind: follows
  - path: cocina/substitutions.md
    kind: related
  - path: autogenesis/work/2026-09-14-cocina-atlas-schema.md
    kind: implements
---

## Decision

La página de ingrediente conceptual declarará nombre canónico, sinónimos,
categoría, unidades válidas, alérgenos y sustituciones relacionadas.

## Consequence

Las recetas y existencias podrán apuntar a una identidad estable aunque usen
variantes de nombre. Las unidades y advertencias de seguridad serán
reutilizables.
