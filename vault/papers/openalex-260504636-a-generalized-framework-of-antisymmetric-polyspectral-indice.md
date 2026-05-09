---
# CSL-compatible fields
title: "A Generalized Framework of Antisymmetric Polyspectral Indices for Identifying High-Order Neural Interactions"
author:
  - literal: "Alessio Basti"
  - literal: "Rikkert Hindriks"
  - literal: "Ruggero Freddi"
  - literal: "Gian Luca Romani"
  - literal: "Vittorio Pizzella"
  - literal: "Guido Nolte"
  - literal: "Laura Marzetti"
issued:
  date-parts:
    - [2026, 5, 6]
url: "https://arxiv.org/abs/2605.04636"

# Custom fields
paper_id: "2605.04636"
paper_source: "openalex"
domain: "neuroscience"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "antisymmetric-cross-polyspectral-indices"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-09T05:58:11Z"
created_at: "2026-05-09T05:58:11Z"
---

# A Generalized Framework of Antisymmetric Polyspectral Indices for Identifying High-Order Neural Interactions

**Authors**: Alessio Basti, Rikkert Hindriks, Ruggero Freddi, Gian Luca Romani, Vittorio Pizzella, Guido Nolte, Laura Marzetti
**Date**: 2026-05-06
**Paper ID**: [openalex:2605.04636](https://arxiv.org/abs/2605.04636)

## Summary

This paper proposes a generalized framework of antisymmetric cross-polyspectral indices to characterize high-order neural interactions defined by frequency-sum relationships (fN = sum(fi)). These indices address the limitations of conventional metrics by providing inherent robustness against volume conduction and zero-lag artifacts. The authors validate the framework through cubic nonlinearity simulations and reveal novel high-order interactions in human EEG data with potential applications for personalized TMS modulation.

## Key Contributions

- Introduces a generalized family of antisymmetric cross-polyspectral indices to quantify N-order harmonic dependencies in time series.
- Provides theoretical proofs that these indices are intrinsically robust to instantaneous mixing/volume conduction artifacts.
- Demonstrates significant high-order neural interactions in empirical EEG recordings that are not captured by standard spectral metrics.

## Open Questions & Future Work

- [[multivariate-multidimensional-polyspectral-frameworks-bottleneck]]

## Key Concepts

- [[antisymmetric-cross-polyspectral-indices]]: A family of spectral indices that quantify high-order harmonic dependencies in time series while maintaining intrinsic robustness to instantaneous linear mixing artifacts.

## Archivist Review

I have approved the core method as a new concept because it addresses a fundamental problem (volume conduction/instantaneous mixing) in multivariate time-series analysis using a formal polyspectral approach. I have approved one open question concerning the multivariate/multidimensional generalization bottleneck, while rejecting the clinical validation request as it represents standard experimental follow-up rather than a structural research question.

### Approved Concepts
- Antisymmetric Cross-Polyspectral Indices: This provides a formal, robust mathematical framework for analyzing nonlinear multi-frequency interactions in time series while explicitly solving the volume conduction artifact problem prevalent in neuroimaging and related sensors.

### Approved Open Questions
- Multivariate Polyspectral Framework Bottleneck: Advancing from univariate-frequency-centric analysis to full multivariate/multidimensional source-level connectivity is essential for high-resolution neuroimaging and complex sensor array processing.

### Rejected Candidates
- [open_question] Stability and Clinical Validation (`validation-and-stability-of-polyspectral-indices`) - low_impact: This is a boilerplate request for clinical validation, larger studies, and signal-to-noise ratio optimization, which fails to identify a specific, unresolved theoretical or mechanistic bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2605.04636)
- [PDF](https://arxiv.org/pdf/2605.04636)

