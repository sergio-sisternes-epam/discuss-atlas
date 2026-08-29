---
type: experience
title: "Implement sprout 0.3.1 — no residuals bucket"
created: 2026-08-26
work_id: 2026-08-26-residuals-vs-protostar
status: closed
origin: internal
sensitivity: internal
description: "Sprout copy and required edges changed with the Autogenesis/Atlas pairing."
relates_to:
  - path: autogenesis/work/2026-08-26-residuals-vs-protostar.md
    kind: implements
---

## Context

Shared work_id with Autogenesis. Discuss was a required sibling: sprout text said “often residuals/” and only required an origin edge.

## What happened

Sprout now writes beside the origin, forbids a residuals bucket, requires work_id when work exists, origin derived_from, work hub implements. Skill metadata 0.3.1.

## Changed files

- discuss/SKILL.md
- discuss/references/paths/sprout.md

## Outcome

Discuss atlas now records this change. Historical `residuals/` pages in this atlas from earlier work were not moved in this pass.
