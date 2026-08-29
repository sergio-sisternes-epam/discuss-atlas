---
type: experience
title: "Scope — planned for design vs deferred protostars"
created: "2026-08-26"
work_id: "2026-08-26-autogenesis-discuss-activation"
status: settled
kva: alive
reality: current
description: "Scope accepted. Work-node link added to planned. Deferred sprouted."
tags: [wire, scope]
origin: derived
sensitivity: internal
relates_to:
  - path: wire/q6-fail-fast-enter.md
    kind: follows
  - path: wire/hub.md
    kind: derived_from
  - path: wire/orbit-activation-path.md
    kind: related
  - path: autogenesis/work/2026-08-26-autogenesis-discuss-activation.md
    kind: implements
  - path: wire/ready-for-design.md
    kind: follows
---

## Context

Original batch is pinned. Q5 handoff: scope planned vs deferred. Deferred become protostars. This node does not start the design Run.

## What happened

Proposed **planned** (later Autogenesis design Run, subject autogenesis, work_id `2026-08-26-autogenesis-discuss-activation`):

1. New path_id `discuss` (`references/paths/discuss.md`). Default Run path stays `design`.
2. Path module substrate-loads catalog discuss and follows the full body.
3. Write-home is the subject Atlas. Discuss skill Atlas is not the dump.
4. Cross-root relationship by `external_ref` + body citation. No dual-write of the fabric.
5. Discussion mode replaces think-grill and think-ramble.
6. Graph links Autogenesis stage and artifacts under discussion.
6b. Every discussion node `relates_to` the Autogenesis **work** hub (`work/<work_id>.md`) or the tighter related node (plan, path receipt, challenged artifact). Work frames where the talk happened.
7. Internal think-challenge remains Autogenesis-only validation gate; not user-activable; user may ask to discuss a challenge result.
8. Human-gated: discussion does not edit Autogenesis product files.
9. Fail-closed Enter if discuss is not loaded or discuss fields are missing.
10. workflow-discipline / activation card / registry updates required to make 1–9 true.
11. Canonical work hub is subject Atlas `work/<work_id>.md`. Discuss-Atlas work page for the same id is `work_role: pointer`.
12. Caller passes `atlas_root` = subject Atlas into discuss.
13. Pages carry `stage` and `artifact`.

**Deferred sprouted** from this node:

- residuals/typed-cross-atlas-relates.md
- residuals/subject-atlas-discuss-folder.md
- residuals/path-vs-skill-name-discuss.md
- residuals/implement-autogenesis-discuss-path.md (action; not implement authority)

agent-spec specify + evaluation plan stays a **design-path obligation**, not a protostar.

## Outcome

User accepted the split and added the work-node link. KVA keep. Next: wire/ready-for-design.md.
