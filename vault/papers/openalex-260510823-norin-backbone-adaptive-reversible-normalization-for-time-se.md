---
# CSL-compatible fields
title: "NoRIN: Backbone-Adaptive Reversible Normalization for Time-Series Forecasting"
author:
  - literal: "Shun Zhang"
  - literal: "Yuyang Xiao"
issued:
  date-parts:
    - [2026, 5, 11]
url: "https://arxiv.org/abs/2605.10823"

# Custom fields
paper_id: "2605.10823"
paper_source: "openalex"
domain: "nlp"
tags:
  - "time-series-forecasting"
  - "normalization-methods"
  - "deep-learning-optimization"
architectures:
  []
datasets:
  []
concept_slugs:
  - "norin"
  - "degeneration-problem-normalization"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-14T06:08:44Z"
created_at: "2026-05-14T06:08:44Z"
---

# NoRIN: Backbone-Adaptive Reversible Normalization for Time-Series Forecasting

**Authors**: Shun Zhang, Yuyang Xiao
**Date**: 2026-05-11
**Paper ID**: [openalex:2605.10823](https://arxiv.org/abs/2605.10823)

## Summary

This paper addresses the limitations of standard linear reversible normalization (RevIN) in time-series forecasting, which fails to capture non-linear distribution characteristics like skewness and heavy tails. The authors identify a 'degeneration problem' where gradient-based joint training causes shape parameters to collapse to linear limits. To counter this, they propose NoRIN, which decouples shape selection from training via closed-form quantile initialization and Bayesian optimization. Experimental results across multiple backbones and datasets validate that backbone-specific, non-linear normalization significantly improves forecasting performance.

## Key Contributions

- Identifies and characterizes the 'degeneration problem' in adaptive reversible normalization, where learnable shape parameters collapse toward linear limits during gradient-based training.
- Introduces NoRIN, a non-linear normalization framework that uses Johnson S_U transforms and decoupled shape optimization to maintain non-linearity.
- Empirically demonstrates that optimal normalization parameters are backbone-dependent, showing performance gains across 90 diverse model-dataset-horizon configurations.

## Open Questions & Future Work

- [[higher-capacity-non-linear-normalization-bottleneck]]

## Key Concepts

- [[norin]]: A non-linear reversible normalization framework utilizing Johnson S_U transforms with decoupled shape parameter optimization to reshape time-series distributions.
- [[degeneration-problem-normalization]]: A phenomenon where learnable non-linear normalization shape parameters collapse to linear limits during end-to-end gradient-based training.

## Archivist Review

I have approved the NoRIN concept and the 'degeneration problem' it identifies, as these constitute a novel, reusable advancement in normalization techniques for time-series. The open question was narrowed to focus on the bottleneck of expressivity vs. stability. Datasets were rejected as they were not specified with unique identifiers or presented as novel benchmarks within the paper context.

### Approved Concepts
- NoRIN: Addresses the limitation of linear reversible normalization (RevIN) by enabling non-linear distribution shaping, critical for complex time-series data.
- Degeneration Problem in Normalization: Identifies a critical failure mode in current adaptive normalization research where high-capacity backbones learn to ignore non-linear shaping.

### Approved Open Questions
- Expressive Normalization Capacity Limits: The capability of the normalization layer bounds the representational flexibility of the entire pipeline; understanding the trade-off between normalization expressivity and optimization stability is vital.

## Links

- [Abstract](https://arxiv.org/abs/2605.10823)
- [PDF](https://arxiv.org/pdf/2605.10823)

