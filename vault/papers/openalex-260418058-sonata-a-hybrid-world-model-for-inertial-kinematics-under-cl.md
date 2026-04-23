---
# CSL-compatible fields
title: "Sonata: A Hybrid World Model for Inertial Kinematics under Clinical Data Scarcity"
author:
  - literal: "Blaise Delaney"
  - literal: "Salil Patel"
  - literal: "Yuji Xing"
  - literal: "Dominic Dootson"
  - literal: "Karin Sevegnani"
issued:
  date-parts:
    - [2026, 4, 20]
url: "https://arxiv.org/abs/2604.18058"

# Custom fields
paper_id: "2604.18058"
paper_source: "openalex"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "latent-world-model-kinematics"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-23T05:48:57Z"
created_at: "2026-04-23T05:48:57Z"
---

# Sonata: A Hybrid World Model for Inertial Kinematics under Clinical Data Scarcity

**Authors**: Blaise Delaney, Salil Patel, Yuji Xing, Dominic Dootson, Karin Sevegnani
**Date**: 2026-04-20
**Paper ID**: [openalex:2604.18058](https://arxiv.org/abs/2604.18058)

## Summary

Sonata is a compact, hybrid latent world model designed for six-axis trunk IMU representation learning, specifically tailored for scenarios with limited clinical data. Unlike standard masked-reconstruction objectives, Sonata utilizes a predictive future-state objective to learn structured representations from a harmonized corpus of inertial sensor data. Empirical results across 14 evaluation tasks demonstrate that this approach consistently outperforms autoregressive forecasting baselines in clinical discrimination and fall-risk prediction tasks. The model's small parameter footprint facilitates efficient on-device inference for neurological assessment.

## Key Contributions

- Introduces Sonata, a 3.77M-parameter hybrid latent world model for six-axis trunk IMU representation learning.
- Demonstrates superior clinical discrimination and fall-risk prediction performance compared to masked-reconstruction (MAE) baselines under data-scarce clinical conditions.
- Achieves effective cross-cohort transfer learning across a 14-arm evaluation suite while remaining compatible with on-device wearable inference.

## Open Questions & Future Work

- [[longitudinal-clinical-monitoring-wearables]]
- [[multi-site-kinematic-modeling]]

## Key Concepts

- [[latent-world-model-kinematics]]: A representation learning approach that uses predictive future-state objectives rather than raw signal reconstruction to capture structured kinematic dynamics in low-data regimes.

## Archivist Review

I approved the latent world model for kinematics concept as it captures the specific shift towards predictive future-state objectives over masked-reconstruction in data-scarce time-series domains. The open questions regarding longitudinal clinical monitoring and multi-site kinematic modeling were selected because they identify fundamental bottlenecks in deploying wearable foundation models in clinical settings beyond this specific study. Sonata itself was rejected as a concept to keep the focus on the broader mechanism.

### Approved Concepts
- Latent World Model for Kinematics: Represents a shift from standard masked-reconstruction tasks to predictive future-state tasks in small-data inertial time series, offering a more robust representation for clinical downstream tasks.

### Approved Open Questions
- Longitudinal Clinical Monitoring via Wearables: Infrequent clinical rating scales are insensitive to subtle fluctuations; developing a longitudinal methodology for wearables is essential for clinical trial design and neurological patient management.
- Multi-site Kinematic World Modeling: Relaxing placement constraints would allow for larger training corpora and more comprehensive whole-body representations necessary for complex neurological movement disorders.

### Rejected Candidates
- [concept] Sonata (Hybrid World Model) (`sonata-model`) - subcomponent_of_broader_mechanism: The model itself is a specific architectural implementation; the underlying approach is better represented by the concept of the latent world model for kinematics.

## Links

- [Abstract](https://arxiv.org/abs/2604.18058)
- [PDF](https://arxiv.org/pdf/2604.18058)

