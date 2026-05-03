---
# CSL-compatible fields
title: "ITS-Mina: A Harris Hawks Optimization-Based All-MLP Framework with Iterative Refinement and External Attention for Multivariate Time Series Forecasting"
author:
  - literal: "Pourya Zamanvaziri"
  - literal: "Amirhossein Sadr"
  - literal: "Aida Pakniyat"
  - literal: "Dara Rahmati"
issued:
  date-parts:
    - [2026, 4, 30]
url: "https://arxiv.org/abs/2604.27981"

# Custom fields
paper_id: "2604.27981"
paper_source: "openalex"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "iterative-refinement-mechanism-ts"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-03T06:02:43Z"
created_at: "2026-05-03T06:02:43Z"
---

# ITS-Mina: A Harris Hawks Optimization-Based All-MLP Framework with Iterative Refinement and External Attention for Multivariate Time Series Forecasting

**Authors**: Pourya Zamanvaziri, Amirhossein Sadr, Aida Pakniyat, Dara Rahmati
**Date**: 2026-04-30
**Paper ID**: [openalex:2604.27981](https://arxiv.org/abs/2604.27981)

## Summary

ITS-Mina is an all-MLP architecture designed for multivariate time series forecasting that addresses the limitations of standard self-attention through linear-complexity external attention and shared-parameter iterative refinement. By incorporating a Harris Hawks Optimization (HHO) routine for automatic dropout tuning, the model adapts its regularization strategy dynamically to various datasets. Empirical evaluation across six standard benchmarks demonstrates that this approach achieves state-of-the-art accuracy with improved computational efficiency over transformer-based models.

## Key Contributions

- Introduces ITS-Mina, an all-MLP framework for multivariate time series forecasting leveraging iterative refinement and external attention.
- Implements an iterative refinement mechanism to enhance model depth and representational capacity without increasing parameter count.
- Utilizes a Harris Hawks Optimization (HHO) algorithm for automated, dataset-specific dropout tuning.

## Open Questions & Future Work

- [[adaptive-halting-iterative-refinement]]

## Key Concepts

- [[iterative-refinement-mechanism-ts]]: An iterative refinement process that repeatedly applies a shared-parameter residual mixer stack to improve temporal representations.

## Archivist Review

The iterative refinement mechanism is an interesting architectural pattern for MLP-based forecasting that warrants tracking. External attention was rejected as it is a known technique in the literature, not a novel contribution of this paper. I also included a focused open question regarding adaptive halting for these refinement loops, while rejecting the auxiliary covariate question as being too generic.

### Approved Concepts
- Iterative Refinement Mechanism (Time Series): Provides a mechanism to increase effective depth and temporal representational power in MLP architectures without increasing parameter count.

### Approved Open Questions
- Adaptive Halting for Iterative Refinement: This is a significant potential optimization for computational efficiency and representational flexibility, as it allows the model to trade off compute time against prediction difficulty on a per-sample basis.

### Rejected Candidates
- [concept] External Attention (Time Series) (`external-attention`) - not_novel: External attention is an established mechanism in broader sequence modeling (e.g., Liu et al. 2021) and not a novel contribution of this paper specific to time series.
- [open_question] Integrating Auxiliary Forecasting Covariates (`integrating-auxiliary-covariates-forecasting`) - generic: This is a generic limitation of sequence modeling architectures and not a specific, tractable research question for this framework.

## Links

- [Abstract](https://arxiv.org/abs/2604.27981)
- [PDF](https://arxiv.org/pdf/2604.27981)

