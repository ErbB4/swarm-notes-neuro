---
title: "Degeneration Problem in Normalization"
slug: "degeneration-problem-normalization"
type: concept
generated_stub: true
source_papers:
  - "[[openalex-260510823-norin-backbone-adaptive-reversible-normalization-for-time-se]]"
processed_at: "2026-05-14T06:08:44Z"
created_at: "2026-05-14T06:08:44Z"
---

# Degeneration Problem in Normalization

> *Auto-generated stub. Edit this file to add more details.*

A phenomenon where learnable non-linear normalization shape parameters collapse to linear limits during end-to-end gradient-based training.


## Why It Matters

Identifies a critical failure mode in current adaptive normalization research where high-capacity backbones learn to ignore non-linear shaping.

## Evidence

> Training (δ,ε) jointly with the backbone via gradient descent reliably pushes them toward this linear limit within a few epochs -- a phenomenon we name the degeneration problem

## Related Papers

- [[openalex-260510823-norin-backbone-adaptive-reversible-normalization-for-time-se]]
