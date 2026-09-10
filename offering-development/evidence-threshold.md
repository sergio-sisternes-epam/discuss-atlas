---
type: document
title: "Evidence threshold is limited to externally verifiable claims"
created: "2026-09-10"
status: settled
kva: alive
reality: current
description: "Evidence and validation dates are mandatory for quantified, externally verifiable battlecard claims, not every sales-guidance field."
origin: user
sensitivity: internal
relates_to:
  - path: offering-development/evidence-contract.md
    kind: derived_from
  - path: offering-development/battlecard-revisioned-record.md
    kind: follows
  - path: offering-development/hub.md
    kind: follows
---

## Context

The battlecard needs credibility controls without making maintained sales guidance impractical to author.

## Decision

Require a linked evidence source and a `last_validated` date for externally verifiable or quantified claims: proof points, client outcomes, market triggers, and competitor comparisons.

## Consequences

Personas, fit signals, discovery questions, objection responses, and seller talk tracks remain subject to edition approval but do not require individual evidence records. Sensitive client details remain in linked source material or approved ranges rather than copied into the battlecard.

The lifecycle state model must specify when validation becomes stale and who can approve an edition.
