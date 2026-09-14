---
type: decision
title: "Conversiones específicas por ingrediente"
created: "2026-09-14"
work_id: "2026-09-14-cocina-atlas-schema"
status: settled
kva: alive
reality: current
description: "Las equivalencias que dependan del ingrediente se declararán en su contexto, con posibles condiciones."
origin: user
sensitivity: internal
relates_to:
  - path: cocina/unit-vocabulary.md
    kind: follows
  - path: cocina/ingredient-contract.md
    kind: related
  - path: autogenesis/work/2026-09-14-cocina-atlas-schema.md
    kind: implements
---

## Decision

Las conversiones dependientes del ingrediente se conservarán como
equivalencias específicas del ingrediente y podrán incluir contexto, como
tamaño, presentación o estado.

## Consequence

El Atlas evitará conversiones engañosas y podrá explicar por qué una
equivalencia solo es válida para ciertos productos o condiciones.
