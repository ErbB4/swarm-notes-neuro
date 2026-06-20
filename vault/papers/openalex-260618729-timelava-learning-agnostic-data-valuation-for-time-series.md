---
# CSL-compatible fields
title: "TimeLAVA: Learning-Agnostic Data Valuation for Time Series"
author:
  - literal: "刘文琴"
  - literal: "Weizhi Quan"
  - literal: "Aoqi Zuo"
  - literal: "Erdun Gao"
  - literal: "Vu Nguyen"
  - literal: "Dino Sejdinović"
  - literal: "Howard Bondell"
  - literal: "Mingming Gong"
issued:
  date-parts:
    - [2026, 6, 17]
url: "https://arxiv.org/abs/2606.18729"

# Custom fields
paper_id: "2606.18729"
paper_source: "openalex"
domain: "time-series"
tags:
  - "anomaly-detection"
  - "data-pruning"
  - "label-noise-detection"
  - "time-series-forecasting"
architectures:
  []
datasets:
  []
concept_slugs:
  - "timelava"
  - "selective-wavelet-based-wasserstein-discrepancy"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-06-20T06:31:34Z"
created_at: "2026-06-20T06:31:34Z"
---

# TimeLAVA: Learning-Agnostic Data Valuation for Time Series

**Authors**: 刘文琴, Weizhi Quan, Aoqi Zuo, Erdun Gao, Vu Nguyen, Dino Sejdinović, Howard Bondell, Mingming Gong
**Date**: 2026-06-17
**Paper ID**: [openalex:2606.18729](https://arxiv.org/abs/2606.18729)

## Summary

TimeLAVA is a learning-agnostic framework designed for quantifying the importance of temporal segments in non-stationary time series data. By utilizing a novel Selective Wavelet-based Wasserstein Discrepancy, the framework evaluates the marginal contribution of data segments toward reducing distributional shifts without requiring costly model training. The approach provides theoretical guarantees regarding generalization and outlier robustness, outperforming existing methods on tasks including anomaly detection, data pruning, and label noise identification.

## Key Contributions

- Proposed TimeLAVA, a learning-agnostic framework for quantifying the value of temporal segments in time series without model retraining.
- Developed a novel Selective Wavelet-based Wasserstein Discrepancy that captures temporal dependencies and multi-scale patterns while remaining robust to non-stationary dynamics.
- Established theoretical guarantees linking segment valuation to model-agnostic generalization performance and outlier sensitivity.

## Key Concepts

- [[timelava]]: A learning-agnostic framework that values time series segments by their marginal contribution to minimizing distributional discrepancy.
- [[selective-wavelet-based-wasserstein-discrepancy]]: A discrepancy measure combining multi-scale wavelet transforms and unbalanced optimal transport for robust time series valuation.

## Archivist Review

I approved the core framework (TimeLAVA) and its primary technical innovation (the discrepancy measure) as they represent a substantial, reusable shift towards learning-agnostic data valuation in time series. The review followed the policy of being selective, focusing on mechanisms that generalize across models and tasks rather than specific applications. No open questions or datasets met the strict criteria for standalone archival.

### Approved Concepts
- TimeLAVA: It introduces a unique learning-agnostic framework for segment-level data valuation in time series, addressing the need for model-independent quality assessment.
- Selective Wavelet-based Wasserstein Discrepancy: It offers a principled way to compare temporal distributions across multiple scales while remaining robust to outliers via optimal transport.

## Links

- [Abstract](https://arxiv.org/abs/2606.18729)
- [PDF](https://arxiv.org/pdf/2606.18729)

