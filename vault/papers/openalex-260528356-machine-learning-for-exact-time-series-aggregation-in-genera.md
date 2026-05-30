---
# CSL-compatible fields
title: "Machine Learning for Exact Time Series Aggregation in Generation Expansion Planning with Energy Storage"
author:
  - literal: "Jakub Rybka"
  - literal: "Luca Santosuosso"
  - literal: "Thomas Klatzer"
  - literal: "Sonja Wogrin"
issued:
  date-parts:
    - [2026, 5, 27]
url: "https://arxiv.org/abs/2605.28356"

# Custom fields
paper_id: "2605.28356"
paper_source: "openalex"
domain: "energy-systems"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "exact-time-series-aggregation"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-30T06:08:29Z"
created_at: "2026-05-30T06:08:29Z"
---

# Machine Learning for Exact Time Series Aggregation in Generation Expansion Planning with Energy Storage

**Authors**: Jakub Rybka, Luca Santosuosso, Thomas Klatzer, Sonja Wogrin
**Date**: 2026-05-27
**Paper ID**: [openalex:2605.28356](https://arxiv.org/abs/2605.28356)

## Summary

This paper addresses the computational complexity of generation expansion planning (GEP) by proposing a machine learning-enhanced iterative time series aggregation (TSA) method. Unlike heuristic aggregation approaches, this technique uses marginal cost estimates as clustering features to construct a reduced model that preserves the active constraints of the original full-scale optimization. By targeting constraint preservation, the method enables the calculation of an optimality gap, providing a rigorous framework for model reduction in energy planning scenarios involving storage and renewables. Empirical results demonstrate superior aggregation performance over conventional data-driven clustering techniques.

## Key Contributions

- Introduces an iterative time series aggregation (TSA) method for generation expansion planning that allows for precise optimality gap assessment.
- Proposes using machine learning-based marginal cost estimates as clustering features to ensure the aggregation process preserves the active constraints of the full-scale model.
- Demonstrates that incorporating marginal costs significantly improves aggregation quality compared to traditional methods that rely only on input data statistics.

## Key Concepts

- [[exact-time-series-aggregation]]: A time series aggregation methodology for optimization models that uses marginal cost estimations to ensure active constraint preservation and exact temporal aggregation.

## Archivist Review

I have approved 'Exact Time Series Aggregation' as it introduces a rigorous, optimization-informed framework for temporal reduction that distinguishes itself from standard heuristic clustering. No other candidates were proposed, and the contribution is clearly reusable within the energy planning and complex optimization domain.

### Approved Concepts
- Exact Time Series Aggregation: The paper moves beyond standard heuristic TSA methods by linking cluster selection to marginal costs, enabling an explicit optimality gap assessment for GEP problems.

## Links

- [Abstract](https://arxiv.org/abs/2605.28356)
- [PDF](https://arxiv.org/pdf/2605.28356)

