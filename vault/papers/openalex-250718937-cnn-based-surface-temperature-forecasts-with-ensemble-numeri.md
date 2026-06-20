---
# CSL-compatible fields
title: "CNN-based Surface Temperature Forecasts with Ensemble Numerical Weather Prediction"
author:
  - literal: "Takuya Inoue"
  - literal: "Takuya Kawabata"
issued:
  date-parts:
    - [2026, 6, 17]
url: "https://arxiv.org/abs/2507.18937"

# Custom fields
paper_id: "2507.18937"
paper_source: "openalex"
domain: "time-series"
tags:
  - "time-series"
  - "forecasting"
architectures:
  []
datasets:
  []
concept_slugs:
  - "cnn-based-ensemble-post-processing"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-06-20T06:32:39Z"
created_at: "2026-06-20T06:32:39Z"
---

# CNN-based Surface Temperature Forecasts with Ensemble Numerical Weather Prediction

**Authors**: Takuya Inoue, Takuya Kawabata
**Date**: 2026-06-17
**Paper ID**: [openalex:2507.18937](https://arxiv.org/abs/2507.18937)

## Summary

This paper introduces a CNN-based post-processing method to enhance medium-range surface temperature forecasts by integrating low-resolution ensemble NWP models. Unlike traditional averaging, which smooths out spatial information, the proposed member-wise CNN correction effectively reduces systematic biases and increases spatial resolution from 40 km to 5 km. The resulting system demonstrates improved deterministic accuracy and superior probabilistic reliability with better spread-skill performance, offering a practical alternative for resource-constrained operational weather forecasting.

## Key Contributions

- Introduces a CNN-based post-processing framework that simultaneously performs bias correction and spatial downscaling on 40-km NWP ensemble members to produce 5-km surface temperature forecasts.
- Demonstrates that member-wise CNN correction improves probabilistic reliability and the spread-skill ratio compared to traditional ensemble averaging techniques.
- Provides a scalable solution for operational medium-range weather forecasting under limited computational constraints.

## Key Concepts

- [[cnn-based-ensemble-post-processing]]: A framework that applies convolutional neural networks individually to numerical weather prediction ensemble members to correct bias and perform spatial downscaling.

## Archivist Review

The paper presents a specific strategy for member-wise post-processing of NWP ensembles using CNNs to achieve simultaneous bias correction and spatial downscaling. I approved this concept as it offers a reusable paradigm that moves beyond simple ensemble averaging. Other candidates were rejected for being standard domain terminology.

### Approved Concepts
- CNN-based Ensemble Post-processing: It introduces a member-wise correction paradigm for NWP ensembles that achieves both downscaling and bias correction simultaneously, improving the spread-skill ratio.

### Rejected Candidates
- [concept] Numerical Weather Prediction Ensemble Forecasting (`nwp-ensemble-forecasting`) - not_novel: This is a broad, pre-existing domain concept rather than a specific, novel contribution of the paper.

## Links

- [Abstract](https://arxiv.org/abs/2507.18937)
- [PDF](https://arxiv.org/pdf/2507.18937)

