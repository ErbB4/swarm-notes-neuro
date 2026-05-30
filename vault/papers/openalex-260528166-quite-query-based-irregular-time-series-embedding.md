---
# CSL-compatible fields
title: "QuITE: Query-Based Irregular Time Series Embedding"
author:
  - literal: "JungHoon Lim"
issued:
  date-parts:
    - [2026, 5, 27]
url: "https://arxiv.org/abs/2605.28166"

# Custom fields
paper_id: "2605.28166"
paper_source: "openalex"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "quite-embedding"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-30T06:07:58Z"
created_at: "2026-05-30T06:07:58Z"
---

# QuITE: Query-Based Irregular Time Series Embedding

**Authors**: JungHoon Lim
**Date**: 2026-05-27
**Paper ID**: [openalex:2605.28166](https://arxiv.org/abs/2605.28166)

## Summary

QuITE addresses the challenge of modeling irregularly sampled multivariate time series (IMTS) by replacing standard uniform-sampling-based embedding layers with a query-based mechanism. By utilizing learnable query tokens and self-attention, QuITE aggregates irregular observations into a regular latent space, allowing standard MTS backbone architectures to be used without modification. This approach avoids the temporal distortions often introduced by interpolation-based preprocessing. Experimental results confirm that QuITE provides consistent performance gains across diverse forecasting and classification benchmarks.

## Key Contributions

- Introduces QuITE, a plug-and-play embedding module that maps irregular multivariate time series to regular latent representations without artificial interpolation.
- Eliminates the need for backbone-specific architectures for irregular time series by providing a unified, architecture-agnostic input-embedding layer.
- Demonstrates significant performance improvements, achieving up to 54.7% relative gain in forecasting and 15.8% in classification across multiple datasets.

## Key Concepts

- [[quite-embedding]]: A plug-and-play embedding module for irregular multivariate time series that uses learnable query tokens and self-attention to generate backbone-compatible latent representations.

## Archivist Review

I approved the core embedding mechanism as it offers a reusable, architecture-agnostic approach to handle irregular temporal data, which is a common bottleneck in time series modeling. No datasets were approved because the paper relies on a collection of standard benchmarks rather than introducing a novel or uniquely significant dataset. I did not identify any substantial, novel open questions beyond the broad challenges already tracked in the vault.

### Approved Concepts
- Query-Based Irregular Time Series Embedding: It provides a model-agnostic mechanism to convert irregular time series into regular latent representations, overcoming the typical reliance on interpolation or specialized architectures.

### Rejected Candidates
- [concept] QuITE (`quite-embedding`) - duplicate_existing: The slug was renamed to Query-Based Irregular Time Series Embedding for better clarity, and the original was rejected as a duplicate.

## Links

- [Abstract](https://arxiv.org/abs/2605.28166)
- [PDF](https://arxiv.org/pdf/2605.28166)

