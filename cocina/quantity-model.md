---
type: decision
title: "Cantidades precisas y unidades convertibles"
created: "2026-09-14"
work_id: "2026-09-14-cocina-atlas-schema"
status: settled
kva: alive
reality: current
description: "El Atlas conservará cantidades precisas y conversiones entre gramos, mililitros, unidades y envases."
origin: user
sensitivity: internal
relates_to:
  - path: cocina/domain-boundary.md
    kind: follows
  - path: cocina/hub.md
    kind: related
  - path: autogenesis/work/2026-09-14-cocina-atlas-schema.md
    kind: implements
---

## Decision

Las recetas y las existencias usarán cantidades precisas. El modelo deberá
distinguir unidades de masa, volumen, unidades contables y envases, y admitir
conversiones cuando sean fiables.

## Consequence

La disponibilidad de una receta podrá calcularse comparando cantidades, no solo
la presencia nominal de un ingrediente. Las conversiones ambiguas o dependientes
del producto deberán poder conservar una equivalencia específica en vez de
forzar una regla universal.
