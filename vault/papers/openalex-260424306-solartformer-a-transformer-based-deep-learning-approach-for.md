---
# CSL-compatible fields
title: "SolarTformer: A Transformer Based Deep Learning Approach for Short Term Solar Power Forecasting"
author:
  - literal: "Ankan Basu"
  - literal: "J.C. Roy"
  - literal: "Aditya Datta"
  - literal: "Prayas Sanyal"
  - literal: "Sumanta Banerjee"
issued:
  date-parts:
    - [2026, 4, 27]
url: "https://arxiv.org/abs/2604.24306"

# Custom fields
paper_id: "2604.24306"
paper_source: "openalex"
domain: "time-series"
tags:
  - "time-series-forecasting"
  - "transformer"
  - "energy-management"
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-30T06:03:21Z"
created_at: "2026-04-30T06:03:21Z"
---

# SolarTformer: A Transformer Based Deep Learning Approach for Short Term Solar Power Forecasting

**Authors**: Ankan Basu, J.C. Roy, Aditya Datta, Prayas Sanyal, Sumanta Banerjee
**Date**: 2026-04-27
**Paper ID**: [openalex:2604.24306](https://arxiv.org/abs/2604.24306)

## Summary

This paper introduces SolarTformer, an attention-based deep learning model designed for short-term solar power forecasting using meteorological inputs. By utilizing self-attention mechanisms, the architecture effectively captures intricate temporal dependencies and spatial variability in solar irradiance. Furthermore, the inclusion of power station-specific metadata enhances the model's ability to generalize across different site configurations and seasonal changes, outperforming existing forecasting baselines.

## Key Contributions

- Introduces SolarTformer, a transformer-based architecture for short-term solar power forecasting leveraging self-attention for complex temporal and spatial dependencies.
- Integrates station-specific metadata into the forecasting pipeline to improve generalization across diverse geographical locations, panel configurations, and seasonal variations.
- Demonstrates significant performance improvements over state-of-the-art models, maintaining high robustness during both clear and cloudy weather conditions.

## Open Questions & Future Work

- [[efficient-solar-forecasting-edge]]
- [[generalization-geographically-diverse-solar-data]]

## Archivist Review

I have rejected the model name 'SolarTformer' as it is a specific implementation instance. The open questions regarding edge efficiency and geographic generalization are highly relevant to the broader field of solar energy forecasting and deserve tracking as industry-wide challenges.

### Approved Open Questions
- Efficiency on Edge Devices: This is a critical bottleneck for real-world adoption of high-accuracy deep learning models in remote PV stations where hardware resources are limited.
- Geographic and Climatic Generalization: Generalization is the primary challenge in scaling solar forecasting solutions to global power grids, where weather patterns and PV system configurations vary significantly.

### Rejected Candidates
- [concept] SolarTformer (`solartformer`) - paper_local: This is a paper-specific model name rather than a reusable architectural concept.

## Links

- [Abstract](https://arxiv.org/abs/2604.24306)
- [PDF](https://arxiv.org/pdf/2604.24306)

