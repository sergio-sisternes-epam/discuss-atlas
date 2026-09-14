---
type: decision
title: "Preferencias y restricciones por persona"
created: "2026-09-14"
work_id: "2026-09-14-cocina-atlas-schema"
status: settled
kva: alive
reality: current
description: "Las preferencias y restricciones alimentarias se configurarán por persona y se combinarán para evaluar una comida familiar."
origin: user
sensitivity: internal
relates_to:
  - path: cocina/recommendation-criteria.md
    kind: follows
  - path: cocina/recipe-scaling.md
    kind: related
  - path: autogenesis/work/2026-09-14-cocina-atlas-schema.md
    kind: implements
---

## Decision

Cada persona podrá tener preferencias, aversiones y restricciones por
alérgenos. El Atlas calculará una combinación familiar para decidir si una
receta es adecuada para todos los comensales seleccionados.

## Consequence

Una receta puede ser apta para una persona y no apta para otra. La explicación
de una recomendación deberá indicar qué perfil provoca una exclusión o qué
sustitución podría resolverla.
