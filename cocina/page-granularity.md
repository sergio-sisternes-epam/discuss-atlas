---
type: decision
title: "Granularidad de páginas y registros"
created: "2026-09-14"
work_id: "2026-09-14-cocina-atlas-schema"
status: settled
kva: alive
reality: current
description: "Recetas, ingredientes, utensilios y personas tendrán páginas; existencias concretas estarán ligadas a eventos."
origin: user
sensitivity: internal
relates_to:
  - path: cocina/immutable-inventory-history.md
    kind: follows
  - path: cocina/core-entities.md
    kind: related
  - path: autogenesis/work/2026-09-14-cocina-atlas-schema.md
    kind: implements
---

## Decision

Cada receta, ingrediente conceptual, utensilio y persona tendrá una página
propia. Los tipos de evento tendrán un contrato común, mientras que las
existencias concretas se representarán como registros ligados a compras o
producciones, no necesariamente como páginas independientes.

## Consequence

El Atlas conserva páginas estables para conocimiento y perfiles, y evita una
explosión de páginas para cada lote o movimiento cotidiano.
