---
type: document
title: "Current offering-development schema contract"
created: "2026-09-10"
status: settled
kva: alive
reality: current
description: "Consolidated current direction for a reusable offering and revisioned battlecard schema."
origin: derived
sensitivity: internal
relates_to:
  - path: offering-development/offering-canonical-record.md
    kind: records
  - path: offering-development/battlecard-revisioned-record.md
    kind: records
  - path: offering-development/evidence-threshold.md
    kind: records
  - path: offering-development/lifecycle-governance.md
    kind: records
  - path: offering-development/hub.md
    kind: follows
---

## Current reality

The schema will introduce a reusable `offering` type and a revisioned `battlecard` type. An offering is canonical reusable knowledge; a battlecard is an approved sales-facing edition linked to exactly one offering. Pursuits remain client-specific consumers of offering guidance.

## Minimum contract

`offering` owns the reusable proposition, target buyers, fit and disqualifier guidance, buying signals, discovery questions, objections, approved assets, proof-point references, glossary, and accountable specialists.

`battlecard` owns its edition, lifecycle state, audience, owner, approver, review date, and the sales-ready content selected for the template. It links to approved offering claims and evidence rather than copying sensitive source detail.

Proof points, client outcomes, market triggers, and competitor comparisons require linked evidence and a `last_validated` date. Other seller guidance is approved at edition level.

## Governance

Offerings and battlecard editions follow `draft`, `in-review`, `approved`, `stale`, and `retired`. An overdue scheduled review or required evidence validation makes an approved edition stale. Stale or retired records are not current seller guidance.

## Boundary

This governs reusable offering knowledge and battlecard editions. It does not create a CRM workflow or redefine pursuit and opportunity status.
