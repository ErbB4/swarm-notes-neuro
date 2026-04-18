---
# CSL-compatible fields
title: "An End-to-end Building Load Forecasting Framework with Patch-based Information Fusion Network and Error-weighted Adaptive Loss"
author:
  - literal: "Hang Fan"
  - literal: "Ying Lu"
  - literal: "Weican Liu"
  - literal: "Dunnan Liu"
  - literal: "Xiaotao Chen"
  - literal: "Shengwei Mei"
issued:
  date-parts:
    - [2026, 4, 15]
url: "https://arxiv.org/abs/2604.13714"

# Custom fields
paper_id: "2604.13714"
paper_source: "openalex"
domain: "time-series"
tags:
  - "time-series-forecasting"
  - "energy-forecasting"
  - "anomaly-detection"
  - "feature-selection"
architectures:
  []
datasets:
  []
concept_slugs:
  - "patch-based-information-fusion-network"
  - "error-weighted-adaptive-loss"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-18T05:34:50Z"
created_at: "2026-04-18T05:34:50Z"
---

# An End-to-end Building Load Forecasting Framework with Patch-based Information Fusion Network and Error-weighted Adaptive Loss

**Authors**: Hang Fan, Ying Lu, Weican Liu, Dunnan Liu, Xiaotao Chen, Shengwei Mei
**Date**: 2026-04-15
**Paper ID**: [openalex:2604.13714](https://arxiv.org/abs/2604.13714)

## Summary

This paper introduces an end-to-end building load forecasting framework designed to address complex temporal dependencies and high load volatility. The architecture utilizes a Patch-based Information Fusion Network (PIF-Net) to process input series as local patches, employing gated hidden state integration for dynamic temporal weighting. To improve model robustness, the framework is trained with an Error-weighted Adaptive Loss (EWAL) function that adjusts penalties according to prediction error distributions. Experimental results confirm the framework's superior performance in capturing building load patterns compared to baseline models.

## Key Contributions

- Proposed the Patch-based Information Fusion Network (PIF-Net) to effectively capture local and global temporal dependencies in load data.
- Developed the Error-weighted Adaptive Loss (EWAL) to enhance prediction robustness against volatile load spikes and extreme conditions.
- Introduced a two-stage preprocessing pipeline incorporating Local Outlier Factor (LOF) and SVM-SHAP for effective anomaly detection and feature selection.

## Open Questions & Future Work

- [[probabilistic-building-load-forecasting]]
- [[edge-optimization-forecasting-models]]

## Key Concepts

- [[patch-based-information-fusion-network]]: A neural architecture for time series forecasting that processes input sequences as local patches and fuses them via a gating mechanism to weight temporal importance.
- [[error-weighted-adaptive-loss]]: A training objective for forecasting models that dynamically adjusts penalty weights based on real-time prediction error distributions.

## Archivist Review

I approved the two primary architectural and objective function contributions (PIF-Net and EWAL) as they represent reusable paradigms for time-series modeling. I also approved the two open questions concerning the transition to probabilistic frameworks and edge-deployment efficiency, as these represent significant, long-term challenges in the field of time-series forecasting. No new datasets were proposed, and standard preprocessing steps (LOF, SHAP) were rejected as routine practice.

### Approved Concepts
- Patch-based Information Fusion Network: It is the core architectural contribution of the paper, enabling multi-scale temporal feature extraction through patching and gated fusion.
- Error-weighted Adaptive Loss: It provides a novel method for improving model robustness in the presence of extreme outliers or high-volatility data by dynamically adjusting penalty weights.

### Approved Open Questions
- Probabilistic Building Load Forecasting: Probabilistic forecasting is crucial for robust risk management and grid balancing in the presence of high load volatility, which deterministic models struggle to capture adequately.
- Edge Optimization for Forecasting Models: Edge-based forecasting is necessary for local demand-side management and reducing data transmission latencies, but current deep learning models are often too computationally demanding for these environments.

## Links

- [Abstract](https://arxiv.org/abs/2604.13714)
- [PDF](https://arxiv.org/pdf/2604.13714)

