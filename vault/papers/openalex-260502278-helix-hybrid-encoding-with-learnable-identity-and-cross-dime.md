---
# CSL-compatible fields
title: "HELIX: Hybrid Encoding with Learnable Identity and Cross-dimensional Synthesis for Time Series Imputation"
author:
  - literal: "Fengming Zhang"
  - literal: "Wenjie Du"
  - literal: "Huan Zhang"
  - literal: "Ke Yu"
  - literal: "Shen Qu"
issued:
  date-parts:
    - [2026, 5, 4]
url: "https://arxiv.org/abs/2605.02278"

# Custom fields
paper_id: "2605.02278"
paper_source: "openalex"
domain: "time-series"
tags:
  - "time-series"
  - "imputation"
  - "attention-mechanism"
architectures:
  []
datasets:
  []
concept_slugs:
  - "learnable-feature-identity"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-07T06:04:01Z"
created_at: "2026-05-07T06:04:01Z"
---

# HELIX: Hybrid Encoding with Learnable Identity and Cross-dimensional Synthesis for Time Series Imputation

**Authors**: Fengming Zhang, Wenjie Du, Huan Zhang, Ke Yu, Shen Qu
**Date**: 2026-05-04
**Paper ID**: [openalex:2605.02278](https://arxiv.org/abs/2605.02278)

## Summary

HELIX is a hybrid time series imputation framework that addresses the inconsistency of attention-based models by introducing learnable, persistent feature identities. By decoupling static feature semantic properties from dynamic temporal dependencies, the model learns arbitrary cross-feature relationships end-to-end without needing predefined graph structures. Empirical evaluations across five benchmark datasets demonstrate that HELIX achieves state-of-the-art results, effectively aligning learned dependencies with latent physical and semantic structures.

## Key Contributions

- Introduces HELIX, a hybrid attention architecture that replaces dynamic re-discovery of feature relationships with persistent learnable feature identities.
- Eliminates reliance on predefined graph topology by learning arbitrary feature dependencies end-to-end from temporal co-variation.
- Establishes state-of-the-art imputation performance across 5 public benchmark datasets and 21 experimental settings.

## Key Concepts

- [[learnable-feature-identity]]: A persistent embedding strategy that encodes intrinsic semantic properties of time series features to provide stable anchors for cross-feature dependency modeling.

## Archivist Review

I approved 'Learnable Feature Identity' as it introduces a reusable inductive bias for time series attention mechanisms, enabling persistent feature-wise semantic modeling. No open questions or datasets were approved as the paper focuses on a specific architecture improvement without explicitly formulating general research bottlenecks or using unique, non-benchmark datasets.

### Approved Concepts
- Learnable Feature Identity: Provides a stable anchor for cross-feature dependencies, addressing the instability of re-discovering relationships at each layer in standard attention mechanisms.

## Links

- [Abstract](https://arxiv.org/abs/2605.02278)
- [PDF](https://arxiv.org/pdf/2605.02278)

