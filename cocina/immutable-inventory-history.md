---
type: decision
title: "Historial de inventario inmutable"
created: "2026-09-14"
work_id: "2026-09-14-cocina-atlas-schema"
status: settled
kva: alive
reality: current
description: "Los eventos de inventario no se editarán; las correcciones se expresarán mediante nuevos eventos."
origin: user
sensitivity: internal
relates_to:
  - path: cocina/inventory-event-types.md
    kind: follows
  - path: cocina/pantry-state.md
    kind: related
  - path: autogenesis/work/2026-09-14-cocina-atlas-schema.md
    kind: implements
---

## Decision

El historial de inventario será append-only. Un error se corregirá con un
nuevo evento de ajuste que referencie el evento o existencia afectada.

## Consequence

El estado actual seguirá siendo derivable y auditable. Las correcciones no
romperán la secuencia histórica de compras, consumos y producciones.
