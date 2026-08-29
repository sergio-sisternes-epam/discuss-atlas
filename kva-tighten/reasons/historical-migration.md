---
type: document
title: "Exit reason — pre-0.3.0 KVA migrate"
created: "2026-08-26"
work_id: "2026-08-26-kva-protostar-tighten"
status: settled
kva: alive
kva_role: exit-reason
description: "Shared final node for pages that were kva terminate before the five-state contract. Stub history, not reconstructed argument."
origin: derived
sensitivity: internal
relates_to:
  - path: autogenesis/work/2026-08-26-kva-protostar-tighten.md
    kind: implements
  - path: autogenesis/plans/2026-08-26-kva-protostar-tighten.md
    kind: related
---

## Context

Implement of 2026-08-26-kva-protostar-tighten replaced legacy `kva: terminate` with `terminated`. Those pages had no final-reason node.

## Decision

One historical final node covers that migrate event. New exits must mint their own reason page. Do not point unrelated future kills here.
