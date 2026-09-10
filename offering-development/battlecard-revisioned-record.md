---
type: document
title: "Battlecard is a revisioned record"
created: "2026-09-10"
status: settled
kva: alive
reality: current
description: "A battlecard is a reviewable edition of sales guidance linked to its canonical offering."
origin: user
sensitivity: internal
relates_to:
  - path: offering-development/battlecard-boundary.md
    kind: derived_from
  - path: offering-development/offering-canonical-record.md
    kind: follows
  - path: offering-development/hub.md
    kind: follows
---

## Context

The battlecard template blends canonical offering knowledge with sales-ready wording, objections, named contacts, and a visible last-updated date.

## Decision

Introduce a revisioned `battlecard` type linked to exactly one canonical `offering`. A battlecard is not merely an export format.

## Consequences

The record can carry an edition, status, owner, approver, review date, audience, and content that is specifically designed for a sales conversation. It should link to, rather than duplicate, approved offering claims and evidence.

This preserves a reliable release history for seller guidance. The evidence burden for individual fields and the lifecycle state model remain unresolved.
