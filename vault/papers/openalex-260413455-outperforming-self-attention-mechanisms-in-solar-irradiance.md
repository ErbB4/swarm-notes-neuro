---
# CSL-compatible fields
title: "Outperforming Self-Attention Mechanisms in Solar Irradiance Forecasting via Physics-Guided Neural Networks"
author:
  - literal: "Mohammed Ezzaldin Babiker Abdullah"
  - literal: "R. R Mohammed"
issued:
  date-parts:
    - [2026, 4, 15]
url: "https://arxiv.org/abs/2604.13455"

# Custom fields
paper_id: "2604.13455"
paper_source: "openalex"
domain: "time-series"
tags:
  - "time-series-forecasting"
  - "physics-informed-ml"
  - "neural-networks"
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-18T05:34:53Z"
created_at: "2026-04-18T05:34:53Z"
---

# Outperforming Self-Attention Mechanisms in Solar Irradiance Forecasting via Physics-Guided Neural Networks

**Authors**: Mohammed Ezzaldin Babiker Abdullah, R. R Mohammed
**Date**: 2026-04-15
**Paper ID**: [openalex:2604.13455](https://arxiv.org/abs/2604.13455)

## Summary

This paper challenges the trend of using complex, computation-heavy Transformer architectures for solar irradiance forecasting by introducing a physics-informed hybrid CNN-BiLSTM model. By incorporating domain-specific physical constraints and engineered features like the Solar Zenith Angle, the proposed framework achieves superior performance in high-noise environments compared to self-attention mechanisms. The authors demonstrate that integrating domain knowledge is more effective than architectural scaling for real-time renewable energy management, providing a significant reduction in RMSE on NASA POWER data.

## Key Contributions

- Introduces a physics-informed hybrid CNN-BiLSTM architecture that integrates 15 domain-specific features (e.g., Clear-Sky indices) to outperform Transformer-based models in GHI forecasting.
- Demonstrates the 'Complexity Paradox' in meteorological forecasting, showing that explicit physical constraints provide superior accuracy (RMSE 19.53 W/m^2) and efficiency compared to high-complexity self-attention mechanisms.
- Validates the proposed approach using NASA POWER solar radiation datasets in Sudan, establishing a new baseline for high-noise, arid-region irradiance forecasting.

## Links

- [Abstract](https://arxiv.org/abs/2604.13455)
- [PDF](https://arxiv.org/pdf/2604.13455)

