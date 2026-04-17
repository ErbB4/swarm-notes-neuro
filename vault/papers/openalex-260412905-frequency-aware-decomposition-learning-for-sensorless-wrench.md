---
# CSL-compatible fields
title: "Frequency-aware Decomposition Learning for Sensorless Wrench Forecasting on a Vibration-rich Hydraulic Manipulator"
author:
  - literal: "Hyeonbeen Lee"
  - literal: "Min-Jae Jung"
  - literal: "Tae–Kyeong Yeu"
  - literal: "Jong-Boo Han"
  - literal: "Daegil Park"
  - literal: "Jin‐Gyun Kim"
issued:
  date-parts:
    - [2026, 4, 14]
url: "https://arxiv.org/abs/2604.12905"

# Custom fields
paper_id: "2604.12905"
paper_source: "openalex"
domain: "time-series"
tags:
  - "forecasting"
  - "transfer-learning"
  - "time-series-forecasting"
architectures:
  []
datasets:
  []
concept_slugs:
  - "frequency-aware-decomposition-network"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-17T05:46:12Z"
created_at: "2026-04-17T05:46:12Z"
---

# Frequency-aware Decomposition Learning for Sensorless Wrench Forecasting on a Vibration-rich Hydraulic Manipulator

**Authors**: Hyeonbeen Lee, Min-Jae Jung, Tae–Kyeong Yeu, Jong-Boo Han, Daegil Park, Jin‐Gyun Kim
**Date**: 2026-04-14
**Paper ID**: [openalex:2604.12905](https://arxiv.org/abs/2604.12905)

## Summary

The paper introduces the Frequency-aware Decomposition Network (FDN) to address the challenges of sensorless wrench forecasting in vibration-rich robotic tasks like grinding. FDN utilizes spectral decomposition to model deterministic low-frequency components and probabilistic high-frequency residuals, incorporating frequency-aware mechanisms to improve spectral fidelity. Experimental results on a 6-DoF hydraulic manipulator show significant improvements in high-frequency forecasting accuracy, further enhanced by transfer learning from large-scale pretraining.

## Key Contributions

- Proposes a Frequency-aware Decomposition Network (FDN) that separates low-frequency deterministic trends from high-frequency residuals using asymmetric prediction heads.
- Introduces frequency-aware spectral enhancement through adaptive filtering and learned frequency-band priors to improve forecasting in vibration-rich environments.
- Demonstrates superior performance in high-frequency wrench forecasting for a 6-DoF hydraulic manipulator during grinding, validated through transfer learning from large-scale pretraining.

## Open Questions & Future Work

- [[generalization-of-wrench-estimation]]

## Key Concepts

- [[frequency-aware-decomposition-network]]: A neural network architecture that employs spectral decomposition and asymmetric heads to forecast wrench signals from proprioceptive data.

## Archivist Review

I approved the Frequency-aware Decomposition Network as a representative architectural approach for multi-scale, vibration-rich time-series forecasting. The open question regarding the generalization of wrench estimation was approved due to the specificity of the challenge in robotics. I rejected the transfer learning scaling question as it remains too broad and speculative compared to the specific task-related challenges identified in the paper.

### Approved Concepts
- Frequency-aware Decomposition Network: The core architectural innovation enabling simultaneous modeling of low-frequency deterministic trends and high-frequency stochastic vibrations in robotic wrench estimation.

### Approved Open Questions
- Generalization of wrench estimation: Robustness and cross-platform generalization are critical bottlenecks for the deployment of sensorless wrench estimation in real-world industrial environments where dynamics vary significantly.

### Rejected Candidates
- [open_question] Transfer learning scaling limits (`transfer-learning-scaling-limits`) - low_impact: The question focuses on general pretraining and scaling concerns rather than a specific unresolved mechanism or fundamental bottleneck unique to temporal representation.

## Links

- [Abstract](https://arxiv.org/abs/2604.12905)
- [PDF](https://arxiv.org/pdf/2604.12905)

