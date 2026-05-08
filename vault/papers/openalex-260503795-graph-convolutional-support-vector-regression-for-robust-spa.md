---
# CSL-compatible fields
title: "Graph Convolutional Support Vector Regression for Robust Spatiotemporal Forecasting of Urban Air Pollution"
author:
  - literal: "Nourin Jahan"
  - literal: "Madhurima Panja"
  - literal: "M. T."
  - literal: "Tanujit Chakraborty"
issued:
  date-parts:
    - [2026, 5, 5]
url: "https://arxiv.org/abs/2605.03795"

# Custom fields
paper_id: "2605.03795"
paper_source: "openalex"
domain: "time-series"
tags:
  - "forecasting"
  - "spatiotemporal-modeling"
  - "uncertainty-quantification"
  - "graph-neural-networks"
architectures:
  []
datasets:
  []
concept_slugs:
  - "gcsvr-framework"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-08T05:43:57Z"
created_at: "2026-05-08T05:43:57Z"
---

# Graph Convolutional Support Vector Regression for Robust Spatiotemporal Forecasting of Urban Air Pollution

**Authors**: Nourin Jahan, Madhurima Panja, M. T., Tanujit Chakraborty
**Date**: 2026-05-05
**Paper ID**: [openalex:2605.03795](https://arxiv.org/abs/2605.03795)

## Summary

This paper presents the Graph Convolutional Support Vector Regression (GCSVR) framework to address the complexities of urban air quality forecasting, including spatiotemporal dependencies and non-stationary data. By combining graph convolutional layers for spatial feature extraction with support vector regression for robust temporal modeling, the approach effectively mitigates the impact of outliers in pollution datasets. The framework provides calibrated uncertainty estimates through integrated conformal prediction, demonstrating improved predictive reliability across diverse urban environments.

## Key Contributions

- Introduces GCSVR (Graph Convolutional Support Vector Regression) for robust spatiotemporal forecasting of urban air pollution.
- Demonstrates superior predictive accuracy and stability over established benchmarks using air quality datasets from Delhi and Mumbai.
- Integrates conformal prediction to provide calibrated uncertainty intervals for decision-making.

## Open Questions & Future Work

- [[exogenous-dynamic-spatiotemporal-graph-integration]]

## Key Concepts

- [[gcsvr-framework]]: A hybrid spatiotemporal forecasting framework that uses graph convolutional layers for spatial feature extraction and support vector regression for robust temporal modeling.

## Archivist Review

I approved the GCSVR framework as it represents a clear, reusable hybrid of graph neural networks and robust regression for time-series. The open question regarding the integration of dynamic graphs and exogenous variables was refined to be more concise and aligned with the existing vault's standard of focusing on high-level unresolved bottlenecks. No datasets were approved as they were location-specific subsets rather than global benchmarks.

### Approved Concepts
- Graph Convolutional Support Vector Regression (GCSVR): Combines spectral spatial aggregation with the robustness properties of SVR for time-series forecasting, offering a distinct alternative to pure deep learning approaches for noisy, outlier-prone sensor networks.

### Approved Open Questions
- Exogenous and Dynamic Graphs: Moving from purely univariate/historical-only graph models to multidimensional, dynamic spatiotemporal representations is essential for practical urban monitoring accuracy.

### Rejected Candidates
- [open_question] Incorporating Exogenous Covariates and Dynamic Graphs (`incorporating-exogenous-covariates-and-dynamic-graphs`) - other: The title was renamed for brevity and the description was refined for clarity.

## Links

- [Abstract](https://arxiv.org/abs/2605.03795)
- [PDF](https://arxiv.org/pdf/2605.03795)

