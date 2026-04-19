---
# CSL-compatible fields
title: "CSRA: Controlled Spectral Residual Augmentation for Robust Sepsis Prediction"
author:
  - literal: "Honglin Guo"
  - literal: "Rihao Chang"
  - literal: "He Jiao"
  - literal: "Weizhi Nie"
  - literal: "Zhongheng Zhang"
  - literal: "Yuehao Shen"
issued:
  date-parts:
    - [2026, 4, 16]
url: "https://arxiv.org/abs/2604.14532"

# Custom fields
paper_id: "2604.14532"
paper_source: "openalex"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  - "MIMIC-IV"
concept_slugs:
  - "controlled-spectral-residual-augmentation"
dataset_slugs:
  - "mimic-iv"
skill: "TimeSeriesSkill"
processed_at: "2026-04-19T05:45:26Z"
created_at: "2026-04-19T05:45:26Z"
---

# CSRA: Controlled Spectral Residual Augmentation for Robust Sepsis Prediction

**Authors**: Honglin Guo, Rihao Chang, He Jiao, Weizhi Nie, Zhongheng Zhang, Yuehao Shen
**Date**: 2026-04-16
**Paper ID**: [openalex:2604.14532](https://arxiv.org/abs/2604.14532)

## Summary

CSRA addresses the difficulty of short-window sepsis prediction by introducing a controlled spectral residual augmentation framework. By grouping clinical variables and applying adaptive spectral perturbations, the method generates structured and clinically plausible trajectory variations. The model is trained end-to-end with an anchor consistency loss and controller regularization, leading to consistent performance gains across various clinical settings, including constrained data availability and challenging forecast horizons.

## Key Contributions

- Proposed CSRA, a controlled data augmentation framework that improves sepsis prediction performance in short-window and limited-data clinical settings.
- Introduced input-adaptive residual perturbation in the spectral domain for generating clinically plausible multi-system ICU time-series variations.
- Demonstrated empirical superiority over baselines, reducing regression MSE by 10.2% and MAE by 3.7% on the MIMIC-IV dataset while maintaining effectiveness on the ZiGongICUinfection dataset.

## Open Questions & Future Work

- [[spectral-augmentation-for-irregular-time-series]]

## Key Concepts

- [[controlled-spectral-residual-augmentation]]: A time-series augmentation framework that performs adaptive residual perturbation in the spectral domain, controlled by a unified objective to maintain clinical plausibility.

## Archivist Review

The concept of Controlled Spectral Residual Augmentation is approved as a reusable method for domain-aware time-series data augmentation. MIMIC-IV is included as a core, widely-used clinical dataset. The open question regarding irregular time-series sampling is retained as it highlights a specific, significant gap for frequency-domain approaches in clinical applications, while the other open question was rejected as too generic.

### Approved Concepts
- Controlled Spectral Residual Augmentation: Introduces a controlled frequency-domain approach to data augmentation that preserves physiological plausibility in time-series forecasting.

### Approved Open Questions
- Spectral Augmentation for Irregular Time-Series: Addressing irregular sampling is critical for the practical deployment of clinical time-series models in real-world EHR settings.

### Rejected Candidates
- [open_question] Adaptive Variable Dependency Modeling (`adaptive-variable-dependency-modeling`) - generic: This is a general challenge in multivariate time-series modeling rather than a specific unresolved problem unique to spectral augmentation.

## Datasets

- [[mimic-iv]]

## Links

- [Abstract](https://arxiv.org/abs/2604.14532)
- [PDF](https://arxiv.org/pdf/2604.14532)

