---
type: document
title: "Lifecycle is draft, in review, approved, stale, and retired"
created: "2026-09-10"
status: settled
kva: alive
reality: current
description: "Battlecard editions use a controlled lifecycle and become stale when review or required evidence validation is overdue."
origin: user
sensitivity: internal
relates_to:
  - path: offering-development/lifecycle-contract.md
    kind: derived_from
  - path: offering-development/evidence-threshold.md
    kind: follows
  - path: offering-development/hub.md
    kind: follows
---

## Context

The battlecard template displays a last-updated date but needs a rule that prevents obsolete approved guidance from remaining in normal use.

## Decision

Use the ordered lifecycle `draft`, `in-review`, `approved`, `stale`, and `retired` for offerings and battlecard editions. An approved edition becomes stale when its scheduled review date or any required evidence `last_validated` date is overdue.

## Consequences

Only approved, non-stale battlecards are current seller guidance. A stale record remains discoverable with its history and must be reviewed before returning to approved status. Retired records remain retained for provenance but must not be used as current guidance.

This is content governance only. It neither creates nor replaces a CRM opportunity lifecycle.
