---
# CSL-compatible fields
title: "DecompKAN: Decomposed Patch-KAN for Long-Term Time Series Forecasting"
author:
  - literal: "Naveen Mysore"
issued:
  date-parts:
    - [2026, 4, 27]
url: "https://arxiv.org/abs/2604.23968"

# Custom fields
paper_id: "2604.23968"
paper_source: "openalex"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  - "ppg-dalia"
concept_slugs:
  - "kolmogorov-arnold-network"
dataset_slugs:
  - "ppg-dalia"
skill: "TimeSeriesSkill"
processed_at: "2026-04-30T06:02:37Z"
created_at: "2026-04-30T06:02:37Z"
---

# DecompKAN: Decomposed Patch-KAN for Long-Term Time Series Forecasting

**Authors**: Naveen Mysore
**Date**: 2026-04-27
**Paper ID**: [openalex:2604.23968](https://arxiv.org/abs/2604.23968)

## Summary

DecompKAN is a novel time series forecasting architecture that avoids standard attention mechanisms in favor of a pipeline featuring trend-residual decomposition, channel-wise patching, and Kolmogorov-Arnold Network (KAN) layers. By replacing traditional MLP nodes with B-spline-based KAN edges, the model provides inherent transparency, allowing for the direct visualization of latent nonlinear transformations. Evaluation across nine datasets, including the PPG-DaLiA physiological benchmark, shows competitive predictive performance and significant improvements on datasets with smooth temporal dynamics compared to existing transformer-based baselines.

## Key Contributions

- Introduces DecompKAN, an attention-free architecture combining trend-residual decomposition, channel-wise patching, and KAN-based edge functions for time series forecasting.
- Achieves state-of-the-art or competitive MSE on 20 of 36 controlled-recipe evaluations across 9 benchmarks, outperforming iTransformer on datasets with smooth dynamics like Solar (-17%) and ECL (-10%).
- Demonstrates that while the architectural pipeline (decomposition, patching) drives forecasting accuracy, the KAN integration uniquely enables visualization of domain-specific latent nonlinearities.

## Open Questions & Future Work

- [[kan-forecasting-performance-taxonomy]]
- [[kan-latent-to-raw-mapping]]

## Key Concepts

- [[kolmogorov-arnold-network]]: A neural network architecture where learnable functions reside on edges instead of nodes, represented as B-splines to allow for direct visualization of learned nonlinearities.

## Archivist Review

I approved the KAN concept and the two open questions because they address the critical intersection of model interpretability and predictive performance in time-series forecasting. The PPG-DaLiA dataset was approved as a high-quality, reusable physiological benchmark, while other architectural components were rejected as they represent standard modular pipelines (patching/decomposition) rather than novel, reusable concepts.

### Approved Concepts
- Kolmogorov-Arnold Network: Central to the paper's claim of balancing performance with model transparency/inspectability.

### Approved Open Questions
- Characterizing KAN Forecasting Suitability: Understanding the failure modes of KANs is crucial for their adoption in high-stakes scientific forecasting, as it clarifies whether poor performance is a fundamental limitation of B-spline function approximation for non-stationary temporal dynamics or a symptom of current architectural design.
- Mapping KAN Latents to Features: Bridging the gap between 'latent-space inspectability' and 'feature-space interpretability' is critical for scientific validity, ensuring that identified patterns correspond to physical phenomena in the raw time series.

## Datasets

- [[ppg-dalia]]

## Links

- [Abstract](https://arxiv.org/abs/2604.23968)
- [PDF](https://arxiv.org/pdf/2604.23968)

