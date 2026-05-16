---
# CSL-compatible fields
title: "Uncertainty-Driven Anomaly Detection for Psychotic Relapse Using Smartwatches: Forecasting and Multi-Task Learning Fusion"
author:
  - literal: "Nikolaos Tsalkitzis"
  - literal: "Panagiotis P. Filntisis"
  - literal: "Petros Maragos"
  - literal: "Niki Efthymiou"
issued:
  date-parts:
    - [2026, 5, 13]
url: "https://arxiv.org/abs/2605.13816"

# Custom fields
paper_id: "2605.13816"
paper_source: "openalex"
domain: "time-series"
tags:
  - "anomaly-detection"
  - "multi-task-learning"
  - "uncertainty-estimation"
  - "sensor-fusion"
  - "digital-phenotyping"
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-16T06:01:46Z"
created_at: "2026-05-16T06:01:46Z"
---

# Uncertainty-Driven Anomaly Detection for Psychotic Relapse Using Smartwatches: Forecasting and Multi-Task Learning Fusion

**Authors**: Nikolaos Tsalkitzis, Panagiotis P. Filntisis, Petros Maragos, Niki Efthymiou
**Date**: 2026-05-13
**Paper ID**: [openalex:2605.13816](https://arxiv.org/abs/2605.13816)

## Summary

This paper addresses the early detection of psychotic relapse through digital phenotyping using smartwatch data. The authors propose two complementary frameworks: one forecasting cardiac dynamics to identify anomalies via prediction error, and another utilizing multi-task learning to fuse sleep, motion, and cardiac signals into time-aware embeddings. Both pipelines integrate an uncertainty-estimation module to improve robustness, and a final late-fusion strategy provides a unified anomaly score. The proposed method demonstrates superior performance over existing benchmarks on the e-Prevention Grand Challenge dataset.

## Key Contributions

- Developed two smartwatch-based frameworks for psychotic relapse detection: a predictive cardiac dynamics approach and a multi-task sensor-fusion approach.
- Introduced an uncertainty-driven anomaly score, derived from a multilayer perceptron ensemble, to enhance robustness against wearable sensor noise.
- Achieved an 8% relative improvement over the competition-winning baseline on the e-Prevention Grand Challenge dataset through a proposed late-fusion strategy.

## Open Questions & Future Work

- [[early-fusion-for-multimodal-relapse-detection]]

## Archivist Review

The paper provides a straightforward application of standard ensemble uncertainty and late fusion for a specific clinical task. No new foundational concepts were identified that aren't already captured by existing terms in the vault. The open question regarding early versus late fusion in multimodal digital phenotyping is sufficiently specific and impactful to warrant tracking.

### Approved Open Questions
- Early Fusion for Relapse Detection: Current late-fusion methods treat models as independent, potentially missing complex nonlinear interactions between physiological modalities that are vital for early warning detection. Moving to early fusion is technically necessary to advance the state-of-the-art in multi-modal digital phenotyping.

### Rejected Candidates
- [dataset] e-Prevention Grand Challenge dataset (`e-prevention-grand-challenge-dataset`) - low_impact: This is a competition-specific dataset that does not have widespread community usage or long-term utility beyond the challenge context.

## Links

- [Abstract](https://arxiv.org/abs/2605.13816)
- [PDF](https://arxiv.org/pdf/2605.13816)

