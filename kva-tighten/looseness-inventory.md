---
type: experience
title: "Orbit — where KVA and protostar are loose today"
created: "2026-08-26"
work_id: "2026-08-26-kva-protostar-tighten"
status: in-discussion
kva: alive
reality: current
description: "Inventory of the loose definition. Batch questions hang here until engaged 1-by-1."
tags: [kva, protostar]
origin: derived
sensitivity: internal
stage: discussion
artifact: kva-tighten/looseness-inventory.md
relates_to:
  - path: kva-tighten/hub.md
    kind: derived_from
  - path: kva-tighten/hub.md
    kind: follows
  - path: protostars/kva-statuses.md
    kind: related
  - path: residuals/kva-value-criteria.md
    kind: related
  - path: residuals/kva-cadence.md
    kind: related
  - path: residuals/kva-terminate-encoding.md
    kind: related
  - path: autogenesis/decisions/protostar-type-name.md
    kind: related
  - path: autogenesis/work/2026-08-26-kva-protostar-tighten.md
    kind: implements
---

## Context

Query-first pass over the discuss Atlas before pinning anything. This page records what is already settled versus what is still two-valued or unenforced.

## What happened

### Settled (do not reopen unless contradicted)

1. Control function is named KVA. Keep / expand / terminate against the discussion objective. Loki TVA is origin metaphor only.
2. Schema type for a forming idea is `protostar`. Not residual. Not leaf.
3. Every protostar must `relates_to` its originating conversation node (`derived_from`). No concept hub.
4. Sprout is the only parking path. `star_kind` is a field, not a second type.
5. A protostar is not implement authority.
6. Lint L1 forbids hub files. Compile is structure; lint is discussion discipline.

### Loose (this is the defect)

1. **Two fields carry lifecycle.** Pages use `status` and `kva` with overlapping vocabularies. SKILL lists status values `in-discussion, keep, expand, terminate, open, settled, probed`. KVA decisions are `keep, expand, terminate`. Protostar birth is `status: open` plus `kva: expand`. The kva-statuses protostar proposes `open, done, terminate` and asks which field owns them.
2. **Required vs recommended.** SCHEMA protostar requires only `type, title, created, status`. `kva`, `growth`, and `star_kind` are recommended. Sprout procedure writes all three. Adversarial smoke `missing-kva` expects kva at birth. A page can compile green and still be an incomplete protostar.
3. **`growth: true` can lie.** Search handle for forming ideas. A terminated stub should not stay findable as growth, but nothing compiles that invariant.
4. **Four open KVA stars, no pin.** residuals/kva-value-criteria, residuals/kva-cadence, residuals/kva-terminate-encoding, protostars/kva-statuses. Operating manual never written.
5. **Two folders.** `residuals/` still holds type:protostar pages. `protostars/` holds one. Decision protostar-type-name said migrate the eleven residual pages. Folder is not identity; type is. Search-by-folder is a trap.
6. **Objective is card-only.** KVA evaluates against the original objective, but the objective lives on the Enter card and the discussion_root body. Child pages do not carry `objective`. Evaluation can drift to local interest.
7. **No KVA lint rule.** L1 is hub-only. Cadence, missing kva, growth/terminate mismatch, and missing origin are prose.
8. **`done` vs `keep` vs `settled`.** Action stars were renamed terminate→done in one session. Thesis uses settled. KVA uses keep. Three words for “this stays”.

## Outcome

KVA expand. Batch 1 and 2 engaged as three-state-kva.md. Probe on challenge-three-state-kva.md. Remaining batch 3–8 still listed, not pages.

## Batch (not yet pages)

1. Field split — does `kva` own keep/expand/terminate only, and `status` own page lifecycle (open / settled / probed / terminated-stub)?
2. Legal enums — pin both fields; accept or reject `done`.
3. Protostar invariant — which of `kva`, `growth`, `star_kind`, origin edge become SCHEMA-required?
4. Cadence — when must the agent write a KVA decision (every persist, every turn, on request, on branch change)?
5. Value test — what counts as value against the locked objective, in one sentence a later lint can quote?
6. Terminate encoding — stub kept, `growth: false`, `kva: terminate`, no new inbound. Pin or replace.
7. Folder — leave residuals as legacy location, or treat folder as irrelevant and search only `type: protostar` + `growth: true`?
8. Implementation fence — this graph pins the contract. Formal design later materialises SKILL, sprout, lint, SCHEMA, scenarios. Confirm no discussion→implement.

## Follow-ups

Engage any batch item 1-by-1 to sprout or settle it.
