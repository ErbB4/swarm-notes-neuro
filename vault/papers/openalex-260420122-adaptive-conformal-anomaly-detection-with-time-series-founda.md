---
# CSL-compatible fields
title: "Adaptive Conformal Anomaly Detection with Time Series Foundation Models for Signal Monitoring"
author:
  - literal: "Natalia Martinez Gil"
  - literal: "Fearghal O’Donncha"
  - literal: "Wesley M. Gifford"
  - literal: "Nianjun Zhou"
  - literal: "Dhaval C. Patel"
  - literal: "Roman Vaculín"
issued:
  date-parts:
    - [2026, 4, 22]
url: "https://arxiv.org/abs/2604.20122"

# Custom fields
paper_id: "2604.20122"
paper_source: "openalex"
domain: "time-series"
tags:
  - "anomaly-detection"
  - "conformal-prediction"
  - "foundation-models"
  - "time-series-forecasting"
architectures:
  []
datasets:
  []
concept_slugs:
  - "weighted-conformal-anomaly-detection"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-25T05:37:23Z"
created_at: "2026-04-25T05:37:23Z"
---

# Adaptive Conformal Anomaly Detection with Time Series Foundation Models for Signal Monitoring

**Authors**: Natalia Martinez Gil, Fearghal O’Donncha, Wesley M. Gifford, Nianjun Zhou, Dhaval C. Patel, Roman Vaculín
**Date**: 2026-04-22
**Paper ID**: [openalex:2604.20122](https://arxiv.org/abs/2604.20122)

## Summary

This paper presents a post-hoc, model-agnostic conformal anomaly detection method designed for time series monitoring using pre-trained foundation models. By applying weighted quantile conformal prediction, the method provides statistically rigorous, interpretable p-values for anomaly detection while ensuring robust false alarm control. The adaptive mechanism learns weighting parameters from historical predictions, allowing the system to maintain performance under non-stationary conditions without the need for additional fine-tuning.

## Key Contributions

- Introduces a post-hoc adaptive conformal anomaly detection framework that integrates with pre-trained time series foundation models without requiring fine-tuning.
- Utilizes weighted quantile conformal prediction to maintain false alarm rate control and provide statistically interpretable p-values for anomalies.
- Implements an adaptive weighting mechanism for calibration that effectively handles distribution shifts while remaining computationally efficient for resource-constrained environments.

## Open Questions & Future Work

- [[conformal-anomaly-detection-non-stationarity-bottleneck]]

## Key Concepts

- [[weighted-conformal-anomaly-detection]]: A conformal prediction framework that uses adaptively learned weights on historical quantiles to maintain rigorous false alarm control under distribution shifts.

## Archivist Review

I have approved the core methodological concept of using weighted conformal prediction for adaptive anomaly detection, as it provides a robust, reusable framework for calibration in non-stationary time series. The open question was refined to capture the fundamental tension between statistical coverage guarantees and non-exchangeable temporal data streams, moving away from the paper-specific phrasing.

### Approved Concepts
- Weighted Conformal Anomaly Detection: Combines conformal prediction with adaptive weighting for non-stationary anomaly detection, which is a powerful mechanism for robust signal monitoring in time series.

### Approved Open Questions
- Conformal Anomaly Detection Bottleneck: This represents a foundational bottleneck in deploying rigorous statistical monitoring tools in high-stakes time-series environments where temporal dependencies and distribution shifts are the norm.

## Links

- [Abstract](https://arxiv.org/abs/2604.20122)
- [PDF](https://arxiv.org/pdf/2604.20122)

