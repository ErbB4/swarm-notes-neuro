---
# CSL-compatible fields
title: "ProbRes: Volatility Learning for Probabilistic Time-Series Forecasting"
author:
  - literal: "Tingting Wang"
  - literal: "Yunyi Zhang"
  - literal: "Benyou Wang"
issued:
  date-parts:
    - [2026, 6, 1]
url: "https://arxiv.org/abs/2606.02117"

# Custom fields
paper_id: "2606.02117"
paper_source: "openalex"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "probres"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-06-04T06:33:37Z"
created_at: "2026-06-04T06:33:37Z"
---

# ProbRes: Volatility Learning for Probabilistic Time-Series Forecasting

**Authors**: Tingting Wang, Yunyi Zhang, Benyou Wang
**Date**: 2026-06-01
**Paper ID**: [openalex:2606.02117](https://arxiv.org/abs/2606.02117)

## Summary

ProbRes is a post-hoc probabilistic calibration method designed to improve the reliability of time-series forecasts by explicitly modeling volatility dynamics. By separating the learning of conditional mean and conditional volatility, the framework effectively addresses challenges posed by heteroskedastic and non-Gaussian data. During inference, ProbRes generates well-calibrated predictive distributions through a residual resampling process that is agnostic to the underlying point-forecasting architecture. Experimental results confirm that the method achieves superior calibration of prediction intervals across both synthetic and real-world financial datasets.

## Key Contributions

- Introduced ProbRes, a post-hoc calibration framework that explicitly decouples conditional mean and volatility modeling for robust probabilistic forecasting.
- Demonstrated that ProbRes effectively handles heteroskedasticity and non-Gaussian error distributions in both univariate and multivariate settings.
- Provided theoretical validity for the approach and showed superior calibration of prediction intervals compared to standard techniques on various benchmarks.

## Key Concepts

- [[probres]]: A post-hoc probabilistic calibration framework that decouples conditional mean and volatility modeling to handle heteroskedasticity in time series.

## Archivist Review

I approved ProbRes as it provides a distinct, architecture-agnostic approach to probabilistic calibration via volatility-mean decoupling. The proposed method represents a reusable mechanism for addressing heteroskedasticity in time-series forecasting, aligning with the criteria for archival. No open questions or datasets met the rigorous standards for novelty and standalone importance.

### Approved Concepts
- ProbRes: Introduces a decoupling strategy for mean and volatility in probabilistic forecasting, offering a flexible post-hoc calibration mechanism.

## Links

- [Abstract](https://arxiv.org/abs/2606.02117)
- [PDF](https://arxiv.org/pdf/2606.02117)

