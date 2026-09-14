---
type: decision
title: "Organización física por tipo de entidad"
created: "2026-09-14"
work_id: "2026-09-14-cocina-atlas-schema"
status: settled
kva: alive
reality: current
description: "El Atlas tendrá una carpeta por tipo de entidad y una página Markdown por elemento estable."
origin: user
sensitivity: internal
relates_to:
  - path: cocina/ingredient-specific-conversions.md
    kind: follows
  - path: cocina/page-granularity.md
    kind: related
  - path: autogenesis/work/2026-09-14-cocina-atlas-schema.md
    kind: implements
---

## Decision

El Atlas se organizará por carpetas de entidad, como `recetas/`,
`ingredientes/`, `utensilios/`, `personas/` e `inventario/`. Cada elemento
estable tendrá su propia página Markdown.

## Consequence

La navegación, las relaciones y las búsquedas podrán seguir una estructura
predecible. Los eventos y existencias operativos seguirán siendo registros
ligados a su origen, salvo que necesiten promoción a página.
