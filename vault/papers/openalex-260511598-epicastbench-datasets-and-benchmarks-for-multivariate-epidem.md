---
# CSL-compatible fields
title: "EpiCastBench: Datasets and Benchmarks for Multivariate Epidemic Forecasting"
author:
  - literal: "Madhurima Panja"
  - literal: "Danny D’Agostino"
  - literal: "Huitao Li, Tanujit Chakraborty"
  - literal: "Nan Liu"
issued:
  date-parts:
    - [2026, 5, 12]
url: "https://arxiv.org/abs/2605.11598"

# Custom fields
paper_id: "2605.11598"
paper_source: "openalex"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  - "epicastbench"
concept_slugs:
  - "epicastbench"
dataset_slugs:
  - "epicastbench"
skill: "TimeSeriesSkill"
processed_at: "2026-05-15T06:14:42Z"
created_at: "2026-05-15T06:14:42Z"
---

# EpiCastBench: Datasets and Benchmarks for Multivariate Epidemic Forecasting

**Authors**: Madhurima Panja, Danny D’Agostino, Huitao Li, Tanujit Chakraborty, Nan Liu
**Date**: 2026-05-12
**Paper ID**: [openalex:2605.11598](https://arxiv.org/abs/2605.11598)

## Summary

EpiCastBench addresses the scarcity of robust benchmarks for multivariate epidemic forecasting by providing a curated, diverse suite of 40 infectious disease datasets. The framework enforces standardized evaluation procedures, including consistent preprocessing and comparative metrics, to facilitate reliable model development and testing. Through an extensive evaluation of 15 distinct architectures, the paper offers insights into the performance landscape of current statistical, deep learning, and foundation models in public health applications.

## Key Contributions

- Introduces EpiCastBench, a benchmark framework with 40 curated multivariate datasets representing various infectious diseases and geographical regions.
- Provides standardized evaluation protocols including unified forecasting horizons, consistent preprocessing, and performance metrics for epidemic forecasting.
- Presents a comprehensive benchmarking study comparing 15 multivariate models, ranging from traditional statistical baselines to modern deep learning and foundation models.

## Open Questions & Future Work

- [[spatiotemporal-epidemic-forecasting-bottleneck]]
- [[probabilistic-epidemic-forecasting-bottleneck]]

## Key Concepts

- [[epicastbench]]: A large-scale benchmarking framework for multivariate epidemic forecasting comprising 40 curated, geographically and disease-diverse datasets.

## Archivist Review

I have approved EpiCastBench as a foundational benchmarking concept and dataset, as it fills a significant gap in the evaluation of multivariate epidemic forecasting. The open questions have been renamed to include 'bottleneck' to better align with the vault's standard of tracking unresolved research challenges rather than just topic areas. These choices prioritize the infrastructure needed for robust epidemic forecasting development.

### Approved Concepts
- EpiCastBench: Establishes a standardized, large-scale framework for the fragmented field of multivariate epidemic forecasting.

### Approved Open Questions
- Spatiotemporal Epidemic Forecasting Bottleneck: Spatial spread is the fundamental nature of epidemics; current multivariate benchmarks remain limited by their focus on temporal correlations over spatial mechanisms.
- Probabilistic Epidemic Forecasting Bottleneck: Decision-making under uncertainty is the primary application of epidemic modeling, requiring a shift in benchmark standards toward probabilistic evaluation.

## Datasets

- [[epicastbench]]

## Links

- [Abstract](https://arxiv.org/abs/2605.11598)
- [PDF](https://arxiv.org/pdf/2605.11598)

