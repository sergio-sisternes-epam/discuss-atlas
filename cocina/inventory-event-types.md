---
type: decision
title: "Tipos de evento que modifican la despensa"
created: "2026-09-14"
work_id: "2026-09-14-cocina-atlas-schema"
status: settled
kva: alive
reality: current
description: "La despensa admitirá eventos de compra, consumo, producción, desperdicio, ajuste manual y traslado."
origin: user
sensitivity: internal
relates_to:
  - path: cocina/recipe-yield.md
    kind: follows
  - path: cocina/consumption-events.md
    kind: related
  - path: autogenesis/work/2026-09-14-cocina-atlas-schema.md
    kind: implements
---

## Decision

Los cambios de inventario se expresarán mediante eventos de compra, consumo,
producción, desperdicio, ajuste manual y traslado.

## Consequence

El estado actual puede derivarse del historial y cada diferencia puede
atribuirse a una causa concreta.
