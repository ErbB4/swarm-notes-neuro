---
# CSL-compatible fields
title: "Scalable inference of spatial regions and temporal signatures from time series"
author:
  - literal: "Jiayu Weng"
  - literal: "Alec Kirkley"
issued:
  date-parts:
    - [2026, 5, 6]
url: "https://arxiv.org/abs/2605.05008"

# Custom fields
paper_id: "2605.05008"
paper_source: "openalex"
domain: "time-series"
tags:
  - "time-series"
  - "spatial-modeling"
  - "clustering"
architectures:
  []
datasets:
  []
concept_slugs:
  - "minimum-description-length-spatial-regionalization"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-09T05:56:55Z"
created_at: "2026-05-09T05:56:55Z"
---

# Scalable inference of spatial regions and temporal signatures from time series

**Authors**: Jiayu Weng, Alec Kirkley
**Date**: 2026-05-06
**Paper ID**: [openalex:2605.05008](https://arxiv.org/abs/2605.05008)

## Summary

This paper introduces a scalable, nonparametric framework for the spatial regionalization of time series by leveraging the minimum description length principle. Unlike existing methods that often rely on static snapshots or ad hoc spatial regularization, this approach jointly learns both the contiguous spatial partitions and a set of representative temporal drivers. The model effectively recovers underlying structure in spatiotemporal data with log-linear computational complexity, demonstrating its utility in analyzing complex, large-scale datasets.

## Key Contributions

- Proposes a nonparametric regionalization framework for spatial time series based on the minimum description length (MDL) principle.
- Jointly infers contiguous spatial partitions and representative temporal archetypes ("drivers") without requiring a priori constraints on the number of regions.
- Achieves log-linear runtime scaling, enabling effective analysis of large-scale spatiotemporal datasets like air quality and vegetation indices.

## Open Questions & Future Work

- [[multivariate-spatiotemporal-regionalization-bottleneck]]

## Key Concepts

- [[minimum-description-length-spatial-regionalization]]: A framework for partitioning spatial domains into contiguous regions by jointly optimizing for spatial contiguity and compression of temporal archetypes using the Minimum Description Length (MDL) principle.

## Archivist Review

The paper presents a robust MDL-based approach to spatial regionalization. I have approved the framework as a core concept because it shifts the focus from ad-hoc regularization to information-theoretic compression. I also approved one open question concerning the extension to multivariate settings, as this is a fundamental bottleneck for expanding such regionalization techniques to holistic system analysis. Other candidates were rejected for being either too generic or less impactful than the approved items.

### Approved Concepts
- Minimum Description Length Spatial Regionalization: This provides a principled, non-parametric, and scalable alternative to ad-hoc spatial regularization for partitioning spatiotemporal data, offering a unique compression-based perspective on clustering.

### Approved Open Questions
- Multivariate Spatiotemporal Regionalization Bottleneck: Environmental and social phenomena are inherently multivariate; restricting analysis to a single time series can obscure important cross-variable spatial regularities.

### Rejected Candidates
- [open_question] Capturing Complex Temporal Dependencies (`temporal-dependency-encoding`) - low_impact: The proposed question is quite generic regarding temporal representation learning and lacks the specific mechanism-level focus of the other selected questions.

## Links

- [Abstract](https://arxiv.org/abs/2605.05008)
- [PDF](https://arxiv.org/pdf/2605.05008)

