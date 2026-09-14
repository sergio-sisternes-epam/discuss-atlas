---
type: decision
title: "Vocabulario canónico de unidades"
created: "2026-09-14"
work_id: "2026-09-14-cocina-atlas-schema"
status: settled
kva: alive
reality: current
description: "El Atlas usará unidades canónicas de masa, volumen, conteo, envase y ración con conversiones explícitas."
origin: user
sensitivity: internal
relates_to:
  - path: cocina/person-contract.md
    kind: follows
  - path: cocina/quantity-model.md
    kind: related
  - path: autogenesis/work/2026-09-14-cocina-atlas-schema.md
    kind: implements
---

## Decision

Las cantidades usarán gramos, kilogramos, mililitros, litros, unidad, envase y
ración como unidades canónicas. Las conversiones se declararán de forma
explícita.

## Consequence

Las recetas y existencias podrán compararse con reglas consistentes. Las
unidades domésticas o ambiguas deberán traducirse a una equivalencia concreta
antes de participar en cálculos.
