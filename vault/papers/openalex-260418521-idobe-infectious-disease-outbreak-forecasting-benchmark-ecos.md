---
# CSL-compatible fields
title: "IDOBE: Infectious Disease Outbreak forecasting Benchmark Ecosystem"
author:
  - literal: "Aniruddha Adiga"
  - literal: "Jingyuan Chou"
  - literal: "Anshul Chiranth"
  - literal: "Bryan Lewis"
  - literal: "Ana I. Bento"
  - literal: "Shaun Truelove"
  - literal: "Geoffrey Fox"
  - literal: "Madhav Marathe"
  - literal: "Harry Hochheiser"
  - literal: "Srini Venkatramanan"
issued:
  date-parts:
    - [2026, 4, 20]
url: "https://arxiv.org/abs/2604.18521"

# Custom fields
paper_id: "2604.18521"
paper_source: "openalex"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "idobe-benchmark-ecosystem"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-23T05:47:07Z"
created_at: "2026-04-23T05:47:07Z"
---

# IDOBE: Infectious Disease Outbreak forecasting Benchmark Ecosystem

**Authors**: Aniruddha Adiga, Jingyuan Chou, Anshul Chiranth, Bryan Lewis, Ana I. Bento, Shaun Truelove, Geoffrey Fox, Madhav Marathe, Harry Hochheiser, Srini Venkatramanan
**Date**: 2026-04-20
**Paper ID**: [openalex:2604.18521](https://arxiv.org/abs/2604.18521)

## Summary

IDOBE is a novel benchmark ecosystem for infectious disease outbreak forecasting, addressing the lack of standardized evaluation frameworks in epidemiology. The repository aggregates over a century of surveillance data across multiple global locations, generating over 10,000 outbreak segments for multi-horizon short-term forecasting. The authors provide a comprehensive analysis of 11 baseline models, demonstrating that MLP-based approaches offer robust performance while statistical models perform competitively during pre-peak phases.

## Key Contributions

- Introduces IDOBE, a standardized benchmark ecosystem containing over 10,000 curated epidemic outbreaks across 13 diseases to facilitate reproducible research.
- Evaluates 11 diverse baseline models (statistical vs. machine learning) across multiple horizons (1-4 weeks) using both point and probabilistic metrics (NWIS).
- Quantifies epidemiological diversity using information-theoretic and distributional measures to characterize dataset complexity for outbreak forecasting.

## Open Questions & Future Work

- [[multivariate-mechanistic-outbreak-forecasting]]

## Key Concepts

- [[idobe-benchmark-ecosystem]]: A standardized methodology for curating, segmenting, and benchmarking multi-horizon epidemiological outbreak time series.

## Archivist Review

I have approved the IDOBE methodology as a reusable concept for epidemic time-series segmentation and benchmarking. I also approved the open question regarding the transition from univariate forecasting to multivariate, mechanistically-informed epidemic models. The dataset itself is a collection rather than a single, atomic repository, so I have excluded it from the dataset list to maintain the vault's focus on high-impact, individual benchmarks.

### Approved Concepts
- IDOBE Benchmark Ecosystem: Provides a standard, reproducible methodological framework for segmenting and evaluating epidemic outbreak time series, which is currently lacking in the field.

### Approved Open Questions
- Multivariate Mechanistic Outbreak Forecasting: Bridging the gap between empirical univariate benchmarks and real-world, multivariate, and mechanistically-informed forecasting is a central challenge for future outbreak response.

## Links

- [Abstract](https://arxiv.org/abs/2604.18521)
- [PDF](https://arxiv.org/pdf/2604.18521)

