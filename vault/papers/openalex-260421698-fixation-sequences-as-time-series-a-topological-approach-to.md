---
# CSL-compatible fields
title: "Fixation Sequences as Time Series: A Topological Approach to Dyslexia Detection"
author:
  - literal: "Marius Huber"
  - literal: "David R. Reich"
  - literal: "Lena A. Jäger"
issued:
  date-parts:
    - [2026, 4, 23]
url: "https://arxiv.org/abs/2604.21698"

# Custom fields
paper_id: "2604.21698"
paper_source: "openalex"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  - "copenhagen-corpus"
concept_slugs:
  - "topological-filtration-time-series"
dataset_slugs:
  - "copenhagen-corpus"
skill: "TimeSeriesSkill"
processed_at: "2026-04-26T05:51:54Z"
created_at: "2026-04-26T05:51:54Z"
---

# Fixation Sequences as Time Series: A Topological Approach to Dyslexia Detection

**Authors**: Marius Huber, David R. Reich, Lena A. Jäger
**Date**: 2026-04-23
**Paper ID**: [openalex:2604.21698](https://arxiv.org/abs/2604.21698)

## Summary

This paper explores the application of topological data analysis (TDA), specifically persistent homology, to detect dyslexia from eye-tracking fixation sequences. The authors construct novel filtrations for time series to extract robust, multi-scale features and combine them with traditional statistical metrics to form hybrid models. Empirical results on the Copenhagen Corpus indicate that these hybrid models significantly improve detection performance over standard baselines by capturing hidden topological structures in reader eye-movements.

## Key Contributions

- Introduced novel topological filtrations for time series analysis of eye-tracking data.
- Demonstrated that hybrid models (topology + statistics) outperform traditional statistical-only models in dyslexia detection.
- Validated that topological features from persistent homology capture complementary information in reading-related fixation sequences.

## Open Questions & Future Work

- [[multivariate-topological-eye-tracking-bottleneck]]

## Key Concepts

- [[topological-filtration-time-series]]: A specialized topological technique for extracting multi-scale, robust features from time series data via novel filtration construction.

## Archivist Review

I approved the topological filtration concept because it provides a distinct, reusable mechanism for feature extraction from temporal signals. I also approved a refined open question regarding the transition from univariate to multivariate topological analysis, as this represents a significant structural hurdle in current TDA for time series. The Copenhagen Corpus was approved as a specific, well-defined dataset relevant to the authors' evaluation.

### Approved Concepts
- Topological Filtration for Time Series: The paper introduces new filtration methods specifically designed for time series, extending beyond standard topological data analysis techniques.

### Approved Open Questions
- Multivariate Topological Time Series: This is a fundamental bottleneck in the current topological approach to eye-tracking; addressing it would allow researchers to analyze the full, coordinated trajectory of eye movements rather than treating them as independent signals.

## Datasets

- [[copenhagen-corpus]]

## Links

- [Abstract](https://arxiv.org/abs/2604.21698)
- [PDF](https://arxiv.org/pdf/2604.21698)

