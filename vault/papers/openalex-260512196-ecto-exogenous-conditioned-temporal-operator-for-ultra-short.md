---
# CSL-compatible fields
title: "ECTO: Exogenous-Conditioned Temporal Operator for Ultra-Short-Term Wind Power Forecasting"
author:
  - literal: "Cao Yuan"
  - literal: "Junjun Wang"
issued:
  date-parts:
    - [2026, 5, 12]
url: "https://arxiv.org/abs/2605.12196"

# Custom fields
paper_id: "2605.12196"
paper_source: "openalex"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "physically-grounded-variable-selection-pgvs"
  - "exogenous-conditioned-regime-refinement-ecrr"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-15T06:15:03Z"
created_at: "2026-05-15T06:15:03Z"
---

# ECTO: Exogenous-Conditioned Temporal Operator for Ultra-Short-Term Wind Power Forecasting

**Authors**: Cao Yuan, Junjun Wang
**Date**: 2026-05-12
**Paper ID**: [openalex:2605.12196](https://arxiv.org/abs/2605.12196)

## Summary

ECTO is a novel forecasting framework designed for ultra-short-term wind power prediction that addresses the non-stationary and condition-dependent nature of meteorological exogenous inputs. By decomposing the task into Physically-Grounded Variable Selection (PGVS) and Exogenous-Conditioned Regime Refinement (ECRR), the model captures site-specific variable importance and applies adaptive regime-aware corrections. Experiments demonstrate that ECTO consistently outperforms baseline deep learning approaches across diverse wind farm settings, particularly as forecasting horizons extend.

## Key Contributions

- Introduced ECTO, a unified framework for wind power forecasting that decomposes exogenous modeling into physically-informed selection and regime-specific refinement.
- Proposed PGVS, which utilizes physical priors and sparsemax to perform condition-adaptive, hierarchical selection of exogenous meteorological variables.
- Proposed ECRR, a mixture-of-experts module that provides horizon-specific gain-bias corrections, improving MSE by up to 8.6% for long horizons.

## Open Questions & Future Work

- [[automated-exogenous-group-discovery]]
- [[spatial-dependency-integration]]

## Key Concepts

- [[physically-grounded-variable-selection-pgvs]]: A hierarchical, group-aware sparse selection module that utilizes physical priors to extract condition-adaptive exogenous contexts.
- [[exogenous-conditioned-regime-refinement-ecrr]]: A mixture-of-experts framework that applies gain-bias calibration and horizon-specific corrections conditioned on exogenous inputs.

## Archivist Review

I approved the two proposed mechanisms (PGVS and ECRR) as they represent reusable, distinct architectures for exogenous-conditioned forecasting. The open questions regarding automated variable grouping and spatial dependency integration address significant, recurring bottlenecks in time-series forecasting research. I applied strict criteria to ensure only foundational, reusable ideas were included.

### Approved Concepts
- Physically-Grounded Variable Selection (PGVS): Provides a novel, physically-informed approach to feature selection in time-series forecasting, addressing the limitations of generic channel mixing or PCA.
- Exogenous-Conditioned Regime Refinement (ECRR): Introduces a specialized regime-based mixture-of-experts approach to refine forecasts based on exogenous conditioning, specifically for non-stationary dynamics.

### Approved Open Questions
- Automated Exogenous Group Discovery: Automated grouping is crucial for reducing engineering effort and improving the generalizability of forecasting models.
- Integration of Spatial Dependencies: Spatio-temporal modeling is essential for improving accuracy when observations are highly coupled due to environmental factors.

## Links

- [Abstract](https://arxiv.org/abs/2605.12196)
- [PDF](https://arxiv.org/pdf/2605.12196)

