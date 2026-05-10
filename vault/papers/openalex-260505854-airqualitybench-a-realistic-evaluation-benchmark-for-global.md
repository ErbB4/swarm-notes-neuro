---
# CSL-compatible fields
title: "AirQualityBench: A Realistic Evaluation Benchmark for Global Air Quality Forecasting"
author:
  - literal: "Xing Xu"
  - literal: "Xu Wang"
  - literal: "Yudong Zhang"
  - literal: "Huilin Zhao"
  - literal: "Zhengyang Zhou"
  - literal: "Yang Wang"
issued:
  date-parts:
    - [2026, 5, 7]
url: "https://arxiv.org/abs/2605.05854"

# Custom fields
paper_id: "2605.05854"
paper_source: "openalex"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  - "AirQualityBench"
concept_slugs:
  - "airqualitybench"
dataset_slugs:
  - "airqualitybench"
skill: "TimeSeriesSkill"
processed_at: "2026-05-10T06:04:18Z"
created_at: "2026-05-10T06:04:18Z"
---

# AirQualityBench: A Realistic Evaluation Benchmark for Global Air Quality Forecasting

**Authors**: Xing Xu, Xu Wang, Yudong Zhang, Huilin Zhao, Zhengyang Zhou, Yang Wang
**Date**: 2026-05-07
**Paper ID**: [openalex:2605.05854](https://arxiv.org/abs/2605.05854)

## Summary

AirQualityBench is a comprehensive benchmark designed to shift air-quality forecasting evaluation toward real-world deployment scenarios. By preserving native observation masks and pollutant-specific scales from 3,720 global stations, it addresses the limitations of current practices that rely on heavily preprocessed and imputed datasets. The study highlights a performance gap, showing that existing spatio-temporal models struggle when faced with realistic levels of missingness and heterogeneity.

## Key Contributions

- Introduces AirQualityBench, a global dataset covering 3,720 stations and six pollutants with native observation masks.
- Establishes an evaluation protocol that forces models to handle structured missingness instead of relying on data imputation or sanitized tensors.
- Demonstrates that high performance on preprocessed datasets fails to generalize to realistic, fragmented monitoring streams.

## Open Questions & Future Work

- [[harmonized-air-quality-unit-conversion]]
- [[region-stratified-evaluation-bias]]

## Key Concepts

- [[airqualitybench]]: A global multi-pollutant benchmark for air quality forecasting that preserves native missingness and pollutant-specific scales.

## Archivist Review

I have approved the AirQualityBench benchmark and its associated dataset note, as it proposes a significant shift in evaluation protocols for air quality time series to include realistic, un-sanitized missingness. I have also approved two open questions that address critical limitations in current environmental monitoring benchmarks: unit harmonization and the evaluation of geographic bias. These reflect substantial, non-trivial challenges for the domain of time-series forecasting.

### Approved Concepts
- AirQualityBench: It introduces a new paradigm for evaluating air quality forecasting that forces models to handle native missingness and heterogeneous scales rather than sanitized data.

### Approved Open Questions
- Harmonization of Monitoring Units: Critical for ensuring researchers can reliably compare forecasting performance across different geographic regions and monitoring providers without being confounded by unit mismatches.
- Region-Stratified Performance Evaluation: Vital to ensure that air-quality forecasting models are equitable and effective globally, rather than just being optimized for wealthy, well-monitored urban centers.

## Datasets

- [[airqualitybench]]

## Links

- [Abstract](https://arxiv.org/abs/2605.05854)
- [PDF](https://arxiv.org/pdf/2605.05854)

