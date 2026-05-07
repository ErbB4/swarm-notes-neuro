---
# CSL-compatible fields
title: "MSMixer: Learned Multi-Scale Temporal Mixing with Complementary Linear Shortcut for Long-Term Time Series Forecasting"
author:
  - literal: "Ahmed Cherif"
issued:
  date-parts:
    - [2026, 5, 4]
url: "https://arxiv.org/abs/2605.02689"

# Custom fields
paper_id: "2605.02689"
paper_source: "openalex"
domain: "time-series"
tags:
  - "time-series-forecasting"
  - "long-term-forecasting"
  - "lightweight-models"
  - "multi-scale-modeling"
architectures:
  - "MLP"
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-07T06:03:37Z"
created_at: "2026-05-07T06:03:37Z"
---

# MSMixer: Learned Multi-Scale Temporal Mixing with Complementary Linear Shortcut for Long-Term Time Series Forecasting

**Authors**: Ahmed Cherif
**Date**: 2026-05-04
**Paper ID**: [openalex:2605.02689](https://arxiv.org/abs/2605.02689)

## Summary

MSMixer is a lightweight, channel-independent MLP architecture designed for efficient long-term time series forecasting. It utilizes three parallel branches with varied down-sampling rates and a learnable softmax gate to adaptively capture temporal dynamics across different scales. By incorporating a DLinear-based shortcut, the model effectively combines multi-scale feature learning with explicit global trend and seasonality modeling, achieving state-of-the-art results for its parameter class on ETT benchmarks.

## Key Contributions

- MSMixer achieves a competitive average MSE of 0.357 on the ETT benchmarks, outperforming DLinear and NLinear.
- Introduces a multi-scale MLP architecture with parallel branches at 1x, 4x, and 16x down-sampling factors to capture multi-scale temporal patterns.
- Integrates a DLinear-based complementary shortcut to explicitly model global trend and seasonality trends alongside learned multi-scale features.

## Open Questions & Future Work

- [[adaptive-scale-selection-forecasting]]

## Archivist Review

I have approved one open question regarding adaptive scale selection, as it addresses a fundamental design challenge in multi-scale time series modeling. The proposed open question on normalization was rejected because it suggests replacing a module with an existing method rather than exploring a deeper, unresolved theoretical or empirical bottleneck. No concepts were approved as the proposed architecture components were too tightly coupled to the specific MSMixer design or represented minor variations of existing techniques.

### Approved Open Questions
- Adaptive Scale Selection Forecasters: Developing adaptive scale selection mechanisms is crucial for improving model performance on diverse datasets where fixed, heuristic-based down-sampling might not be optimal.

### Rejected Candidates
- [open_question] Advanced Normalization for LTSF (`advanced-normalization-ltsf`) - other: This suggests replacing a component (RevIN) with existing methods rather than identifying a deep, unresolved research bottleneck in forecasting.

## Links

- [Abstract](https://arxiv.org/abs/2605.02689)
- [PDF](https://arxiv.org/pdf/2605.02689)

