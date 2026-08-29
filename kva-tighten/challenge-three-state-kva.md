---
type: experience
title: "Fail-fast — counters to three-state KVA"
created: "2026-08-26"
work_id: "2026-08-26-kva-protostar-tighten"
status: probed
kva: alive
reality: current
description: "Discuss cheap probe on the three-state proposal. Grounded counters. Not an Autogenesis think-challenge path switch."
tags: [kva, probe]
origin: derived
sensitivity: internal
stage: discussion
artifact: kva-tighten/challenge-three-state-kva.md
relates_to:
  - path: kva-tighten/three-state-kva.md
    kind: counters
  - path: kva-tighten/three-state-kva.md
    kind: derived_from
  - path: kva-tighten/hub.md
    kind: related
  - path: autogenesis/work/2026-08-26-kva-protostar-tighten.md
    kind: implements
---

## Context

User asked for think-challenge on the three-state model. Autogenesis discussion mode does not activate catalog think-challenge as a path. Discuss step 8 allows a cheap probe. Counters below are that probe, grounded in external lifecycle practice plus this Atlas.

## What happened

### Counters

1. **Three states are the right grain. Two fields are not.** Knowledge-base lifecycle practice separates *process stage* from *disposition*, and warns that one overloaded status column is how systems rot. Collapsing keep/expand/terminate + open/settled/done into one KVA field matches the "at most one status field" heuristic. Seriousness: high support for the simplification, not a kill.

2. **Terminated must leave default search.** KCS archives instead of deleting so links do not break, and removes the article from ordinary search. Gartner-cited KB rot: stale active hits destroy trust. If terminated nodes stay `growth: true` or appear in default protostar search, the three-state model fails in use. Seriousness: high. Encoding rule required: terminated ⇒ not in forming/active search.

3. **Historic without a why is a known failure.** IESG on RFC Historic: reclassifications often had no pointer from the document to *why* it was retired. Obsoletes ≠ Historic (replaced text vs retired technology). "Terminated" is one bucket covering failed, superseded, and out-of-scope. Without a mandatory reason field (and optionally a `superseded_by` edge), trace collapses. Seriousness: high. Matches the user's own "termination rationale" requirement — that field is not optional.

4. **Reactivation is a new ref, not a flip.** Git restore of a deleted branch creates a *new* pointer to old commits; it does not unmute the deleted name in place. IETF never edits a published RFC; a new RFC obsoletes the old one. If KVA allows `terminated → forming` on the same page, lineage of the kill is overwritten. Subtle branching must be a new page with `derived_from` the stub plus `kva: forming`, stub stays terminated. Seriousness: high if we want the scar to remain readable.

5. **Type is not a KVA state.** Zettelkasten distinguishes fleeting / literature / permanent as *kinds of note*, not as one status enum. A forming protostar and an active decision can both be "alive" and must not share one type. `kva: forming` should not secretly mean `type: protostar`. If we bind them 1:1, sprout becomes the only way to be forming, and a forming revision of an active decision has nowhere to live. Seriousness: medium-high. Keep `type` and `star_kind` off the KVA enum.

6. **Active + forming growth needs an edge rule.** "Active may grow with forming nodes" is a graph law (`relates_to` origin / follows / derived_from), not a status. Without that law, every active page becomes a magnet hub and L1 returns. Seriousness: medium. Pair the enum with: forming nodes attach to one origin conversation node, not to "all active thesis pages".

## Outcome

KVA expand on the proposal. Probe did not kill three states. It kills in-place unmute, search pollution, and a missing reason field.

No failure yet ≠ proof. Candidate pin if user accepts the four hardenings:

- one field `kva`: forming | active | terminated
- `kva_reason` required when terminated
- reactivation = new forming page, stub stays terminated
- terminated excluded from default growth search
