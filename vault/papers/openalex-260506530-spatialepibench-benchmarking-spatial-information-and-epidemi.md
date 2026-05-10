---
# CSL-compatible fields
title: "SpatialEpiBench: Benchmarking Spatial Information and Epidemic Priors in Forecasting"
author:
  - literal: "Ruiqi Lyu"
  - literal: "Alistair Turcan"
  - literal: "Bryan Wilder"
issued:
  date-parts:
    - [2026, 5, 7]
url: "https://arxiv.org/abs/2605.06530"

# Custom fields
paper_id: "2605.06530"
paper_source: "openalex"
domain: "time-series"
tags:
  - "time-series-forecasting"
  - "epidemic-forecasting"
  - "spatiotemporal-modeling"
  - "benchmarking"
architectures:
  []
datasets:
  []
concept_slugs:
  - "spatialepibench"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-10T06:04:03Z"
created_at: "2026-05-10T06:04:03Z"
---

# SpatialEpiBench: Benchmarking Spatial Information and Epidemic Priors in Forecasting

**Authors**: Ruiqi Lyu, Alistair Turcan, Bryan Wilder
**Date**: 2026-05-07
**Paper ID**: [openalex:2605.06530](https://arxiv.org/abs/2605.06530)

## Summary

SpatialEpiBench addresses the lack of standardized evaluation frameworks in epidemic forecasting by providing a benchmark with 11 datasets and rolling evaluation protocols that reflect real-time public health practice. The study evaluates diverse models incorporating geographic adjacency and epidemiological priors, revealing a significant performance gap compared to simple persistence baselines. The authors categorize model failures into poor outbreak anticipation, sensitivity to data noise, and ineffective use of spatial graph structures.

## Key Contributions

- Introduces SpatialEpiBench, a benchmark for spatiotemporal epidemic forecasting across 11 datasets using realistic rolling evaluation protocols.
- Demonstrates that existing adjacency-informed models and epidemic priors frequently underperform simple last-value baselines across various forecasting horizons.
- Identifies three critical failure modes in current models: poor outbreak anticipation, limited robustness to data sparsity/noise, and weak utility of simple geographic adjacency for epidemiological modeling.

## Open Questions & Future Work

- [[geographic-adjacency-utility-in-epidemiology]]

## Key Concepts

- [[spatialepibench]]: A benchmark for spatiotemporal epidemic forecasting incorporating 11 datasets and standardized rolling evaluations.

## Archivist Review

I approved the benchmark as a foundational contribution to standardized evaluation in the domain and the open question regarding the validity of geographic priors in epidemiology, as these address significant, recurring issues in spatiotemporal forecasting. I rejected the request to label the 11 datasets individually as they are aggregate components of the benchmark, adhering to the scarcity policy for datasets.

### Approved Concepts
- SpatialEpiBench: It is a primary, standardized benchmark for spatiotemporal epidemic forecasting designed to reflect realistic public-health practices.

### Approved Open Questions
- Utility of Geographic Adjacency: This is a fundamental failure mode in the field that limits the effectiveness of current spatiotemporal modeling approaches in public health.

## Links

- [Abstract](https://arxiv.org/abs/2605.06530)
- [PDF](https://arxiv.org/pdf/2605.06530)

