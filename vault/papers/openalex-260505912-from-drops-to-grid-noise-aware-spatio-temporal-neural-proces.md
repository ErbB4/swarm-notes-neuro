---
# CSL-compatible fields
title: "From Drops to Grid: Noise-Aware Spatio-Temporal Neural Process for Rainfall Estimation"
author:
  - literal: "Rafael Pablos Sarabia"
  - literal: "Joachim Nyborg"
  - literal: "Morten Birk"
  - literal: "Ira Assent"
issued:
  date-parts:
    - [2026, 5, 7]
url: "https://arxiv.org/abs/2605.05912"

# Custom fields
paper_id: "2605.05912"
paper_source: "openalex"
domain: "time-series"
tags:
  - "time-series"
  - "spatio-temporal-forecasting"
  - "uncertainty-quantification"
  - "neural-processes"
  - "multi-modal-learning"
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-10T06:05:32Z"
created_at: "2026-05-10T06:05:32Z"
---

# From Drops to Grid: Noise-Aware Spatio-Temporal Neural Process for Rainfall Estimation

**Authors**: Rafael Pablos Sarabia, Joachim Nyborg, Morten Birk, Ira Assent
**Date**: 2026-05-07
**Paper ID**: [openalex:2605.05912](https://arxiv.org/abs/2605.05912)

## Summary

DropsToGrid is a Neural Process-based approach designed to generate high-resolution, continuous rainfall maps by integrating sparse, noisy station measurements with spatial radar context. The method leverages multi-scale feature extraction, temporal attention, and multi-modal fusion to handle the highly localized and skewed nature of rainfall data. By producing stochastic estimates with explicit uncertainty quantification, the model outperforms traditional and existing deep learning approaches in both data-limited and cross-regional scenarios.

## Key Contributions

- Introduces DropsToGrid, a Neural Process-based framework that enables continuous spatio-temporal rainfall field estimation from sparse, noisy point observations and radar data.
- Implements multi-scale feature extraction combined with temporal attention and multi-modal fusion to effectively handle the skewed, localized characteristics of precipitation.
- Demonstrates superior predictive accuracy and robust uncertainty quantification compared to existing operational and deep learning baselines in data-scarce and cross-regional settings.

## Open Questions & Future Work

- [[general-probabilistic-data-assimilation]]

## Archivist Review

I have approved the open question regarding general probabilistic data assimilation as it identifies a substantive limitation in how current deep learning models handle heterogeneous multi-modal weather inputs. The DropsToGrid framework itself was rejected as a concept because it represents a specific application of Neural Processes to rainfall, which is a paper-local contribution rather than a general methodology. I maintained high standards for reusability, rejecting any candidates that were merely task-specific implementations.

### Approved Open Questions
- General Probabilistic Data Assimilation: This is a significant step toward moving beyond task-specific rainfall densification models to more robust, unified systems capable of handling multi-variable, long-term atmospheric modeling and data assimilation in a principled, uncertainty-aware manner.

### Rejected Candidates
- [concept] DropsToGrid Framework (`dropstogrid-framework`) - paper_local: The proposed framework is a paper-local instantiation of existing Neural Process concepts for a specific application.

## Links

- [Abstract](https://arxiv.org/abs/2605.05912)
- [PDF](https://arxiv.org/pdf/2605.05912)

