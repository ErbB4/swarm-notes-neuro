---
# CSL-compatible fields
title: "Superposition Is Not Necessary: A Mechanistic Interpretability Analysis of Transformer Representations for Time Series Forecasting"
author:
  - literal: "Alper Yildirim"
issued:
  date-parts:
    - [2026, 5, 6]
url: "https://arxiv.org/abs/2605.05151"

# Custom fields
paper_id: "2605.05151"
paper_source: "openalex"
domain: "time-series"
tags:
  - "time-series-forecasting"
  - "mechanistic-interpretability"
  - "transformer-analysis"
architectures:
  []
datasets:
  []
concept_slugs:
  - "sparse-autoencoders-sae"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-09T05:56:39Z"
created_at: "2026-05-09T05:56:39Z"
---

# Superposition Is Not Necessary: A Mechanistic Interpretability Analysis of Transformer Representations for Time Series Forecasting

**Authors**: Alper Yildirim
**Date**: 2026-05-06
**Paper ID**: [openalex:2605.05151](https://arxiv.org/abs/2605.05151)

## Summary

This paper investigates whether Transformers use superposition for time series forecasting by applying sparse autoencoders (SAEs) to the internal representations of PatchTST. The analysis reveals that increasing dictionary dimensionality results in negligible performance gains and minimal latent feature activation, suggesting that the model's representations are sparse rather than superposed. These findings challenge the assumption that time series tasks require the rich, compositional representations typical of NLP, helping to explain the persistent competitiveness of simple linear baselines.

## Key Contributions

- Demonstrates that a single-layer, narrow-dimensional Transformer achieves parity with deeper configurations on standard time series forecasting benchmarks.
- Proves that time series Transformer FFN representations do not exhibit strong superposition by showing insensitivity to dictionary expansion via sparse autoencoders.
- Provides a mechanistic explanation for the competitiveness of simple linear models in time series by suggesting that forecasting tasks do not inherently require high-dimensional compositional representations.

## Open Questions & Future Work

- [[superposition-in-complex-time-series-domains]]

## Key Concepts

- [[sparse-autoencoders-sae]]: An interpretability technique using overcomplete dictionary learning to decompose neural network activations into sparse latent features.

## Archivist Review

The paper offers a compelling mechanistic critique of current time-series modeling, challenging the assumption that deep architectures are always necessary. I have approved the use of SAEs as a methodology for future diagnostic work and the open question regarding representational complexity in high-stakes domains, as these address a central, unresolved bottleneck in time-series model architecture design.

### Approved Concepts
- Sparse Autoencoders (SAEs): Used here as the primary method to probe for representational superposition in time-series models, demonstrating its utility in cross-domain mechanistic analysis.

### Approved Open Questions
- Superposition in Complex Time-Series Domains: This is critical for understanding whether current forecasting benchmarks are too simple to warrant advanced transformer architectures and for defining the scope of future foundation models.

### Rejected Candidates
- [concept] PatchTST (`patchtst`) - paper_local: Standard model architecture used for demonstration rather than a reusable mechanistic concept.

## Links

- [Abstract](https://arxiv.org/abs/2605.05151)
- [PDF](https://arxiv.org/pdf/2605.05151)

