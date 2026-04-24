---
# CSL-compatible fields
title: "Improvements to the post-processing of weather forecasts using machine learning and feature selection"
author:
  - literal: "Kazuma Iwase"
  - literal: "Tomoyuki Takenawa"
issued:
  date-parts:
    - [2026, 4, 21]
url: "https://arxiv.org/abs/2604.19340"

# Custom fields
paper_id: "2604.19340"
paper_source: "openalex"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  - "msm-dataset"
concept_slugs:
  []
dataset_slugs:
  - "msm-dataset"
skill: "TimeSeriesSkill"
processed_at: "2026-04-24T05:51:13Z"
created_at: "2026-04-24T05:51:13Z"
---

# Improvements to the post-processing of weather forecasts using machine learning and feature selection

**Authors**: Kazuma Iwase, Tomoyuki Takenawa
**Date**: 2026-04-21
**Paper ID**: [openalex:2604.19340](https://arxiv.org/abs/2604.19340)

## Summary

This study improves weather forecast post-processing for temperature, wind speed, and precipitation by using LightGBM-based models on the Japan Meteorological Agency's Mesoscale Model (MSM) data. The authors utilize feature selection based on grid-point correlations to enhance model input, consistently outperforming standard neural-network baselines and official guidance. Additionally, they address the challenges of precipitation skewness and zero-inflation by implementing Tweedie loss functions and event-weighted training strategies.

## Key Contributions

- Developed LightGBM-based post-processing models for precipitation, temperature, and wind speed that outperform raw MSM forecasts and MSMG guidance.
- Introduced a feature selection approach using correlation analysis on surrounding grid points to enhance predictive input relevance.
- Evaluated Tweedie-based loss functions and event-weighted training strategies to address skewness and zero-inflation in precipitation forecasting.

## Open Questions & Future Work

- [[ml-precipitation-post-processing-site-dependence]]

## Archivist Review

The paper offers incremental improvements to standard weather post-processing tasks. I approved one open question concerning the site-dependence of precipitation forecasting, which is a known challenge in time-series meteorology. I am registering the 'msm-dataset' for tracking, though it is a specialized regional product. No new concepts were approved as the methods described (LightGBM, Tweedie loss, correlation-based feature selection) are standard techniques rather than novel contributions to the field.

### Approved Open Questions
- ML Precipitation Post-processing Site-dependence: Addressing the site-dependence of ML precipitation models is critical for moving beyond simplistic local adjustments and achieving generalizable meteorological forecasting performance.

### Rejected Candidates
- [dataset] MSM (Mesoscale Model) dataset (`msm-dataset`) - other: The dataset itself is regional and proprietary-adjacent to JMA; I will approve it as 'msm-dataset' for reusability, but note it is highly specialized.

## Datasets

- [[msm-dataset]]

## Links

- [Abstract](https://arxiv.org/abs/2604.19340)
- [PDF](https://arxiv.org/pdf/2604.19340)

