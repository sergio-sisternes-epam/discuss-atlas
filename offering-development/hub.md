---
type: document
title: "Hub — offering-development schema"
created: "2026-09-10"
status: in-discussion
kva: alive
reality: current
description: "Discussion root for deciding the minimum Atlas schema that supports reusable offering development and battlecard production."
tags: [offering-development, battlecard, schema, discussion-root]
origin: user
sensitivity: internal
stage: discussion
artifact: offering-development/hub.md
relates_to: []
---

## Context

Subject: offering-development schema.
Objective: decide the boundaries and minimum contract for a new offering-development schema.

This page is `discussion_root`. It does not move.

The current EPAM overlay has no offering or battlecard type. The supplied battlecard template needs a pitch, buyer problem, urgency, solution, competitive positioning, proof, qualification, personas, signals, discovery questions, objections, resources, glossary, and escalation contacts.

## What happened

The user introduced the battlecard as a reusable offering-development asset and opened a discussion about a new schema. The existing `pursuit` and `opportunity` records remain client-specific and should not become the canonical representation of an offering.

The user accepted a dedicated, reusable `offering` type. It will link to client-specific pursuits rather than extending their scope.

## Live questions

- Should a battlecard be a first-class typed record or a governed rendering of an offering?
No unresolved design question remains in this initial orbit.

## Outcome

The canonical offering boundary, revisioned battlecard representation, evidence threshold, and lifecycle are accepted. Current branch: offering-development/current-schema-contract.md.
