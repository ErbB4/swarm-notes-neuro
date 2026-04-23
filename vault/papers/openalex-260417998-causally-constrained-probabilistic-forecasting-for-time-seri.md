---
# CSL-compatible fields
title: "Causally-Constrained Probabilistic Forecasting for Time-Series Anomaly Detection"
author:
  - literal: "Pooyan Khosravinia"
  - literal: "João Gama"
  - literal: "Bruno Veloso"
issued:
  date-parts:
    - [2026, 4, 20]
url: "https://arxiv.org/abs/2604.17998"

# Custom fields
paper_id: "2604.17998"
paper_source: "openalex"
domain: "time-series"
tags:
  - "anomaly-detection"
  - "forecasting"
  - "causality"
  - "multivariate-time-series"
  - "transformer"
architectures:
  []
datasets:
  - "smd"
concept_slugs:
  - "causally-guided-transformer"
dataset_slugs:
  - "smd"
skill: "TimeSeriesSkill"
processed_at: "2026-04-23T05:47:00Z"
created_at: "2026-04-23T05:47:00Z"
---

# Causally-Constrained Probabilistic Forecasting for Time-Series Anomaly Detection

**Authors**: Pooyan Khosravinia, João Gama, Bruno Veloso
**Date**: 2026-04-20
**Paper ID**: [openalex:2604.17998](https://arxiv.org/abs/2604.17998)

## Summary

This paper introduces a Causally Guided Transformer (CGT) for multivariate time-series anomaly detection that incorporates time-lagged causal graph priors to bridge the gap between correlation-based deep learning and causal interpretability. The model utilizes a hard parent mask to restrict predictions to causal precursors and a shadow auxiliary path with safety-gated blending to selectively incorporate non-causal correlational data. Evaluation on the ASD and SMD benchmarks demonstrates that this causally-constrained approach outperforms existing models in both detection accuracy and root-cause localization precision.

## Key Contributions

- Introduces a Causally Guided Transformer (CGT) that uses time-lagged causal graph priors to constrain multivariate time-series forecasting.
- Implements a safety-gated blending mechanism to isolate causal predictions from residual correlational information.
- Achieves SOTA anomaly detection on ASD (96.19% F1) and SMD (95.32% F1) datasets while providing improved root-cause localization through counterfactual clamping.

## Open Questions & Future Work

- [[joint-causal-discovery-and-detection-bottleneck]]

## Key Concepts

- [[causally-guided-transformer]]: A transformer architecture that restricts predictive paths to graph-supported causal precursors via hard parent masking.

## Archivist Review

Approved the Causally Guided Transformer as a distinct architectural paradigm for incorporating structural priors. The dataset ASD was rejected as a standard benchmark, while SMD was kept to track core industrial evaluation. The open question was reframed to focus on the bottleneck of joint end-to-end causal learning.

### Approved Concepts
- Causally Guided Transformer: It provides a reusable framework for incorporating structural inductive biases into transformer-based forecasting via hard parent masking.

### Approved Open Questions
- Joint Causal Discovery Bottleneck: This question addresses the core tension between static causal priors and dynamic real-world environments, which is essential for advancing robust, interpretable forecasting.

### Rejected Candidates
- [dataset] ASD (`asd`) - not_novel: Routine industrial anomaly detection dataset.

## Datasets

- [[smd]]

## Links

- [Abstract](https://arxiv.org/abs/2604.17998)
- [PDF](https://arxiv.org/pdf/2604.17998)

