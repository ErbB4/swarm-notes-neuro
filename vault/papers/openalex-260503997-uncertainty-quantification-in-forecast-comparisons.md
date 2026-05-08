---
# CSL-compatible fields
title: "Uncertainty Quantification in Forecast Comparisons"
author:
  - literal: "Marc‐Oliver Pohle"
  - literal: "Tanja Zahn"
  - literal: "Sebastian Lerch"
issued:
  date-parts:
    - [2026, 5, 5]
url: "https://arxiv.org/abs/2605.03997"

# Custom fields
paper_id: "2605.03997"
paper_source: "openalex"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "simultaneous-confidence-bands-for-forecast-scores"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-08T05:43:38Z"
created_at: "2026-05-08T05:43:38Z"
---

# Uncertainty Quantification in Forecast Comparisons

**Authors**: Marc‐Oliver Pohle, Tanja Zahn, Sebastian Lerch
**Date**: 2026-05-05
**Paper ID**: [openalex:2605.03997](https://arxiv.org/abs/2605.03997)

## Summary

This paper addresses the lack of rigorous uncertainty quantification in multivariate forecast evaluation by proposing simultaneous confidence bands for expected and skill scores. The proposed framework enables valid joint inference across multiple dimensions such as forecasting horizons, variables, and spatial locations, overcoming the inflated Type I error rates associated with traditional pairwise tests. The approach is versatile, supporting various forecast types including distributional forecasts, and is validated through a bootstrap implementation and empirical case studies.

## Key Contributions

- Introduces a framework for simultaneous confidence bands to quantify uncertainty in expected and skill scores across multivariate forecast evaluations.
- Addresses the multiple comparison problem in multi-dimensional forecast evaluation (across horizons, variables, and locations) which traditional Diebold-Mariano tests fail to resolve.
- Demonstrates practical applicability for both mean/quantile and full distributional forecasts in macroeconomic and weather forecasting case studies.

## Open Questions & Future Work

- [[high-dimensional-asymptotics-forecast-evaluation]]
- [[multivariate-bootstrap-block-length-selection]]

## Key Concepts

- [[simultaneous-confidence-bands-for-forecast-scores]]: A statistical framework for performing valid joint inference on forecast skill scores across multiple horizons, variables, and spatial dimensions.

## Archivist Review

The paper provides a rigorous statistical foundation for addressing the multiple comparison problem in forecast evaluation. I approved the simultaneous confidence bands concept as it offers a reusable methodological improvement over standard Diebold-Mariano tests. The open questions regarding high-dimensional asymptotics and data-driven bootstrap tuning were approved as they identify fundamental bottlenecks in scaling statistical inference for modern complex time-series benchmarks.

### Approved Concepts
- Simultaneous Confidence Bands for Forecast Scores: It provides a statistically rigorous framework for multi-dimensional forecast comparison, addressing the multiple comparison problem that plagues standard pairwise tests in time series evaluation.

### Approved Open Questions
- Asymptotics for Growing Dimensions: Addressing high-dimensional asymptotics is essential for validating the reliability of forecast comparisons in large-scale spatio-temporal and multivariate domains.
- Multivariate Bootstrap Block Selection: Establishing objective criteria for block length selection is necessary to transition from heuristic-based bootstrap implementations to robust, plug-and-play statistical tools.

## Links

- [Abstract](https://arxiv.org/abs/2605.03997)
- [PDF](https://arxiv.org/pdf/2605.03997)

