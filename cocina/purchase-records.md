---
type: decision
title: "Registro estructurado de compras"
created: "2026-09-14"
work_id: "2026-09-14-cocina-atlas-schema"
status: settled
kva: alive
reality: current
description: "Cada compra conservará producto, cantidad, unidad, fecha, tienda, precio opcional y caducidad."
origin: user
sensitivity: internal
relates_to:
  - path: cocina/purchase-packaging-deferred.md
    kind: follows
  - path: cocina/pantry-state.md
    kind: related
  - path: autogenesis/work/2026-09-14-cocina-atlas-schema.md
    kind: implements
---

## Decision

Una compra será un evento estructurado con producto, cantidad, unidad, fecha,
tienda, precio opcional y caducidad.

## Consequence

Las existencias podrán trazarse hasta su compra y podrán filtrarse por tienda,
fecha o caducidad. El precio se mantendrá como dato opcional para no bloquear
el registro cuando no esté disponible.
