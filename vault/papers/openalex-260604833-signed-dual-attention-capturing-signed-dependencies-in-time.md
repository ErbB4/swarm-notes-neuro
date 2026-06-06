---
# CSL-compatible fields
title: "Signed Dual Attention: Capturing Signed Dependencies in Time Series Forecasting"
author:
  - literal: "Balthazar Courvoisier"
  - literal: "Tristan Cazenave"
issued:
  date-parts:
    - [2026, 6, 3]
url: "https://arxiv.org/abs/2606.04833"

# Custom fields
paper_id: "2606.04833"
paper_source: "openalex"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "signed-dual-attention"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-06-06T06:13:07Z"
created_at: "2026-06-06T06:13:07Z"
---

# Signed Dual Attention: Capturing Signed Dependencies in Time Series Forecasting

**Authors**: Balthazar Courvoisier, Tristan Cazenave
**Date**: 2026-06-03
**Paper ID**: [openalex:2606.04833](https://arxiv.org/abs/2606.04833)

## Summary

This paper addresses the limitation of standard attention mechanisms in time series forecasting, which typically assume homophilic interactions. The authors propose Signed Dual Attention, a novel formulation that explicitly models both positive (supportive) and negative (contrastive) relational patterns. By utilizing a dual message-passing scheme, the model achieves the expressiveness of a two-head attention mechanism without increasing the total parameter count.

## Key Contributions

- Introduces Signed Dual Attention, a parameter-efficient formulation to capture both positive and negative temporal dependencies.
- Demonstrates that the proposed module achieves the expressiveness of a dual-head attention mechanism without requiring additional parameters.
- Provides a modular attention block compatible with existing transformer architectures to improve forecasting performance in scenarios with signed dependencies.

## Key Concepts

- [[signed-dual-attention]]: A novel attention mechanism that captures positive and negative dependencies by propagating supportive and contrastive information within a single shared block.

## Archivist Review

Signed Dual Attention is approved as a novel, parameter-efficient architectural primitive for capturing both supportive and contrastive temporal dependencies in transformers. The review applied strict criteria to ensure only foundational, reusable modules are added to the vault, excluding implementation-specific details. No other concepts, open questions, or datasets met the threshold for standalone inclusion.

### Approved Concepts
- Signed Dual Attention: It introduces a parameter-efficient way to model both positive and negative dependencies in attention mechanisms, addressing a limitation of standard homophilic attention.

## Links

- [Abstract](https://arxiv.org/abs/2606.04833)
- [PDF](https://arxiv.org/pdf/2606.04833)

