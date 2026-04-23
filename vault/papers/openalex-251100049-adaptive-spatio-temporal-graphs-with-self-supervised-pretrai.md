---
# CSL-compatible fields
title: "Adaptive spatio-temporal graphs with self-supervised pretraining for multi-horizon weather forecasting"
author:
  - literal: "Y. A. Liu"
issued:
  date-parts:
    - [2026, 4, 20]
url: "https://arxiv.org/abs/2511.00049"

# Custom fields
paper_id: "2511.00049"
paper_source: "openalex"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  - "era5"
  - "merra-2"
concept_slugs:
  []
dataset_slugs:
  - "era5"
  - "merra-2"
skill: "TimeSeriesSkill"
processed_at: "2026-04-23T05:47:40Z"
created_at: "2026-04-23T05:47:40Z"
---

# Adaptive spatio-temporal graphs with self-supervised pretraining for multi-horizon weather forecasting

**Authors**: Y. A. Liu
**Date**: 2026-04-20
**Paper ID**: [openalex:2511.00049](https://arxiv.org/abs/2511.00049)

## Summary

This paper addresses the complexity of multi-horizon weather forecasting by proposing a self-supervised learning framework that incorporates graph neural networks for spatial reasoning. By integrating a spatio-temporal adaptation mechanism, the model improves generalization across various time scales and meteorological variables. Empirical evaluations on the ERA5 and MERRA-2 datasets demonstrate superior performance over traditional numerical weather prediction and existing deep learning benchmarks. The approach provides a scalable and label-efficient solution for fine-grained atmospheric pattern prediction.

## Key Contributions

- Introduces a self-supervised pretraining framework for learning spatio-temporal representations in weather data.
- Develops a spatio-temporal adaptation mechanism that enhances predictive accuracy across multiple forecasting horizons.
- Outperforms traditional numerical weather prediction and current deep learning baselines on ERA5 and MERRA-2 benchmarks.

## Open Questions & Future Work

- [[extreme-weather-forecasting-performance]]

## Archivist Review

The paper provides solid benchmark results on standard climate datasets but lacks novel, reusable architectural innovations; therefore, no new concepts were approved. ERA5 and MERRA-2 were approved as they are foundational, widely used datasets in this domain. The open question regarding extreme weather performance was approved as it identifies a critical, distinct bottleneck in data-driven forecasting that persists across various architectures.

### Approved Open Questions
- Extreme Weather Event Forecasting: Improving performance on extreme weather events is vital for the societal utility of forecasting systems, specifically for disaster preparedness and climate risk management.

### Rejected Candidates
- [open_question] Dynamic Graph Construction Methods (`dynamic-graph-construction-weather`) - generic: The question of dynamic vs. static graph construction is a well-known, generic architectural challenge in GNN-based spatiotemporal forecasting rather than a specific research gap highlighted as a priority by the paper.

## Datasets

- [[era5]]
- [[merra-2]]

## Links

- [Abstract](https://arxiv.org/abs/2511.00049)
- [PDF](https://arxiv.org/pdf/2511.00049)

