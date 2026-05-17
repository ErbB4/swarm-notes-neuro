---
# CSL-compatible fields
title: "SeesawNet: Towards Non-stationary Time Series Forecasting with Balanced Modeling of Common and Specific Dependencies"
author:
  - literal: "Hao Li"
  - literal: "Lu Zhang"
  - literal: "Liu Chong"
  - literal: "Yankai Chen"
  - literal: "Pengyang Wang"
  - literal: "Yingjie Zhou"
issued:
  date-parts:
    - [2026, 5, 14]
url: "https://arxiv.org/abs/2605.14551"

# Custom fields
paper_id: "2605.14551"
paper_source: "openalex"
domain: "time-series"
tags:
  - "time-series-forecasting"
  - "non-stationary-time-series"
  - "attention-mechanism"
architectures:
  []
datasets:
  []
concept_slugs:
  - "adaptive-stationary-nonstationary-attention"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-17T06:07:11Z"
created_at: "2026-05-17T06:07:11Z"
---

# SeesawNet: Towards Non-stationary Time Series Forecasting with Balanced Modeling of Common and Specific Dependencies

**Authors**: Hao Li, Lu Zhang, Liu Chong, Yankai Chen, Pengyang Wang, Yingjie Zhou
**Date**: 2026-05-14
**Paper ID**: [openalex:2605.14551](https://arxiv.org/abs/2605.14551)

## Summary

SeesawNet addresses the limitations of instance normalization in non-stationary time series forecasting, which often obscures instance-specific structural information. By introducing Adaptive Stationary-Nonstationary Attention (ASNA), the framework captures common dependencies from normalized data and specific dependencies from raw data, fusing them dynamically based on instance-level characteristics. This dual-stream approach, combined with alternating temporal and channel modeling, effectively reconciles the trade-off between distribution alignment and capturing local dynamics.

## Key Contributions

- Proposed SeesawNet, which balances common and instance-specific dependency modeling to mitigate over-smoothing caused by traditional instance normalization.
- Introduced Adaptive Stationary-Nonstationary Attention (ASNA) to dynamically fuse patterns from normalized and raw sequences based on instance-specific non-stationarity.
- Demonstrated consistent performance improvements over existing state-of-the-art models across standard time series forecasting benchmarks.

## Open Questions & Future Work

- [[non-stationary-pattern-dependency-balance-bottleneck]]

## Key Concepts

- [[adaptive-stationary-nonstationary-attention]]: An attention mechanism that adaptively fuses dependencies derived from normalized and raw time series sequences based on instance-level non-stationarity.

## Archivist Review

The review approved the central attention mechanism as a reusable concept for handling the trade-off between instance normalization and information loss. The open question was reframed to highlight the broader bottleneck of dependency balancing in non-stationary regimes, avoiding generic boilerplate future work. The model architecture itself was rejected as a concept, as it is a specific instantiation of the proposed attention mechanism.

### Approved Concepts
- Adaptive Stationary-Nonstationary Attention (ASNA): It addresses the fundamental tension between modeling common global patterns and instance-specific local dynamics in non-stationary time series, which is the primary contribution of the paper.

### Approved Open Questions
- Non-stationary Pattern Dependency Balance: This is essential for designing more robust forecasting models that do not rely on static assumptions about normalization, as different types of non-stationarity likely require distinct strategies for balancing common and specific signals.

### Rejected Candidates
- [concept] SeesawNet (`seesaw-net`) - subcomponent_of_broader_mechanism: SeesawNet is the specific model architecture presented; the underlying attention mechanism (ASNA) is the more reusable and central concept.

## Links

- [Abstract](https://arxiv.org/abs/2605.14551)
- [PDF](https://arxiv.org/pdf/2605.14551)

