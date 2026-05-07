---
# CSL-compatible fields
title: "PDRS : A Linear O(N) Algorithm for Segmentation of High-Activity Regions in Irregularly Sampled Time Series"
author:
  - literal: "Atal Agrawal"
issued:
  date-parts:
    - [2026, 5, 4]
url: "https://arxiv.org/abs/2605.02843"

# Custom fields
paper_id: "2605.02843"
paper_source: "openalex"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "peak-driven-region-segmentation"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-07T06:04:15Z"
created_at: "2026-05-07T06:04:15Z"
---

# PDRS : A Linear O(N) Algorithm for Segmentation of High-Activity Regions in Irregularly Sampled Time Series

**Authors**: Atal Agrawal
**Date**: 2026-05-04
**Paper ID**: [openalex:2605.02843](https://arxiv.org/abs/2605.02843)

## Summary

PDRS addresses the computational bottleneck of identifying transient high-activity episodes in irregularly sampled astronomical time series by reducing complexity from O(N^2) to O(N). The algorithm utilizes a gradient-aware multi-source breadth-first search seeded at local maxima, supplemented by saddle-point merging to refine segments. PDRS serves as an efficient pre-processing tool for high-volume surveys, providing performance equivalent to Bayesian-based methods with significant speedups. Its domain-agnostic nature allows for potential application across various fields involving irregular signal monitoring, such as biomedical and industrial sensing.

## Key Contributions

- Introduces PDRS, a linear-time O(N) algorithm for segmenting high-activity regions in irregularly sampled time series.
- Replaces computationally expensive quadratic search methods with a gradient-aware multi-source breadth-first search.
- Validates PDRS on astronomical light curves, demonstrating performance comparable to Bayesian Blocks at a significantly reduced computational cost.

## Open Questions & Future Work

- [[automated-pdrs-parameter-tuning]]

## Key Concepts

- [[peak-driven-region-segmentation]]: A linear-time O(N) algorithm for identifying transient high-activity regions in irregularly sampled time series using seed-based breadth-first search and gradient-aware expansion.

## Archivist Review

The paper introduces a computationally efficient O(N) segmentation algorithm, PDRS, which is a significant practical improvement over existing O(N^2) methods. I approved the algorithm as a concept due to its clear reusability and potential impact on large-scale time-series processing. The open question regarding automated parameter tuning was approved as it directly addresses a known limitation in achieving fully autonomous deployment of the proposed method. The datasets were rejected as they are domain-specific and routine benchmarks for astronomy.

### Approved Concepts
- Peak-Driven Region Segmentation: It offers a linear-time approach to a common time-series segmentation problem, replacing expensive quadratic methods, and is designed to be domain-agnostic.

### Approved Open Questions
- Automated PDRS Parameter Selection: Crucial for enabling fully autonomous data-processing pipelines in large-scale surveys where manual tuning is not feasible.

### Rejected Candidates
- [dataset] SDSS Stripe 82 (`sdss-stripe-82`) - low_impact: Routine domain-specific dataset used for demonstration, not a critical architectural or foundational resource.
- [dataset] ZTF DR23 (`ztf-dr23`) - low_impact: Routine domain-specific dataset used for demonstration, not a critical architectural or foundational resource.

## Links

- [Abstract](https://arxiv.org/abs/2605.02843)
- [PDF](https://arxiv.org/pdf/2605.02843)

