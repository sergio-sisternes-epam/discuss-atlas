---
type: decision
title: "Existencias como registros promovibles"
created: "2026-09-14"
work_id: "2026-09-14-cocina-atlas-schema"
status: settled
kva: alive
reality: current
description: "Una existencia será un registro ligado a compra o producción y solo tendrá página propia si requiere historial detallado."
origin: user
sensitivity: internal
relates_to:
  - path: cocina/page-granularity.md
    kind: follows
  - path: cocina/immutable-inventory-history.md
    kind: related
  - path: autogenesis/work/2026-09-14-cocina-atlas-schema.md
    kind: implements
---

## Decision

Las existencias concretas se representarán como registros por defecto,
vinculados al evento que las creó. Podrán promoverse a páginas propias si
acumulan historial, transformaciones o decisiones que lo justifiquen.

## Consequence

La estructura cotidiana permanece compacta y el modelo conserva una vía
explícita para elevar un producto a conocimiento duradero cuando sea necesario.
