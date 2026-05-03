---
# CSL-compatible fields
title: "FoReco and FoRecoML: A Unified Toolbox for Forecast Reconciliation in R"
author:
  - literal: "Daniele Girolimetto"
  - literal: "Jeroen Rombouts"
  - literal: "Ines Wilms"
  - literal: "Yangzhuoran Fin Yang"
issued:
  date-parts:
    - [2026, 4, 30]
url: "https://arxiv.org/abs/2604.27696"

# Custom fields
paper_id: "2604.27696"
paper_source: "openalex"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "forecast-reconciliation"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-03T06:02:47Z"
created_at: "2026-05-03T06:02:47Z"
---

# FoReco and FoRecoML: A Unified Toolbox for Forecast Reconciliation in R

**Authors**: Daniele Girolimetto, Jeroen Rombouts, Ines Wilms, Yangzhuoran Fin Yang
**Date**: 2026-04-30
**Paper ID**: [openalex:2604.27696](https://arxiv.org/abs/2604.27696)

## Summary

The FoReco and FoRecoML R packages provide a unified, comprehensive framework for reconciling forecasts of linearly constrained time series, including hierarchical and grouped structures. The tools cover the entire spectrum of cross-sectional, temporal, and cross-temporal reconciliation techniques, integrating both classical linear methodologies and modern machine learning-based approaches. By balancing ease-of-use with advanced configurability, these packages facilitate the application of state-of-the-art reconciliation techniques in both academic research and industry practice.

## Key Contributions

- Introduction of FoReco and FoRecoML, an R toolbox providing a unified framework for cross-sectional, temporal, and cross-temporal forecast reconciliation.
- Provides a comprehensive implementation of both classical linear and modern regression-based/non-linear machine learning reconciliation approaches.
- Designed with a dual-layer API: sensible defaults for rapid application and deep configuration options for expert-driven research and advanced modeling.

## Key Concepts

- [[forecast-reconciliation]]: A mathematical framework to ensure that independent forecasts of linearly constrained time series (hierarchical or grouped) are mutually coherent.

## Archivist Review

I approved 'Forecast Reconciliation' as it is a foundational, non-trivial concept in time series analysis that encompasses cross-sectional, temporal, and cross-temporal coherence. I rejected the R packages themselves as they are software implementations rather than conceptual or methodological breakthroughs for the vault. No open questions were proposed, and the paper focuses on tooling rather than unresolved theoretical bottlenecks.

### Approved Concepts
- Forecast Reconciliation: It is the fundamental process of enforcing coherence in hierarchical and grouped forecasting, which is critical for real-world time series applications.

## Links

- [Abstract](https://arxiv.org/abs/2604.27696)
- [PDF](https://arxiv.org/pdf/2604.27696)

