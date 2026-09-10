---
type: document
title: "Offering is the canonical reusable record"
created: "2026-09-10"
status: settled
kva: alive
reality: current
description: "A dedicated offering type holds reusable commercial and delivery guidance, while pursuits retain client-specific context."
origin: user
sensitivity: internal
relates_to:
  - path: offering-development/offering-boundary.md
    kind: derived_from
  - path: offering-development/hub.md
    kind: follows
---

## Context

The offering-development schema needs a reusable unit that is not conflated with a client-specific pursuit.

## Decision

Introduce a dedicated `offering` type as the canonical reusable record. It will link to one or more `pursuit` records, but it will not inherit client-specific status, account facts, commercial commitments, or opportunity workflow.

## Consequences

The offering can own the stable proposition, target buyers, fit and disqualifier guidance, buying signals, discovery prompts, objections, approved assets, proof-point references, glossary, and accountable specialists. Client outcomes and other evidence remain linked and governed rather than copied into each pursuit.

The battlecard boundary, evidence rules, and lifecycle are unresolved. They determine the type's detailed fields and its rendering contract.
