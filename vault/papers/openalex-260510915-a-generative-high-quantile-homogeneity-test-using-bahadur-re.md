---
# CSL-compatible fields
title: "A Generative High Quantile Homogeneity Test Using Bahadur Representation for Heteroskedastic High Quantile Regression of Tail Dependent Time Series"
author:
  - literal: "Ting Zhang"
  - literal: "Fangwei Wu"
  - literal: "Jingying Gao"
issued:
  date-parts:
    - [2026, 5, 11]
url: "https://arxiv.org/abs/2605.10915"

# Custom fields
paper_id: "2605.10915"
paper_source: "openalex"
domain: "time-series"
tags:
  - "time-series"
  - "statistical-inference"
  - "quantile-regression"
architectures:
  []
datasets:
  []
concept_slugs:
  - "bahadur-representation-high-quantile-regression"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-14T06:09:54Z"
created_at: "2026-05-14T06:09:54Z"
---

# A Generative High Quantile Homogeneity Test Using Bahadur Representation for Heteroskedastic High Quantile Regression of Tail Dependent Time Series

**Authors**: Ting Zhang, Fangwei Wu, Jingying Gao
**Date**: 2026-05-11
**Paper ID**: [openalex:2605.10915](https://arxiv.org/abs/2605.10915)

## Summary

This paper introduces a formal framework for testing the homogeneity of covariate effects across different high quantiles in tail-dependent time series. The authors derive a novel Bahadur representation, which enables the reduction of nonlinear high quantile regression estimators to linear forms with controlled error bounds. This representation facilitates the construction of a generative homogeneity test capable of handling both homoscedastic and heteroskedastic conditions. The method is validated through comprehensive experiments on both synthetic and real-world datasets.

## Key Contributions

- Develops a novel Bahadur representation for high quantile regression estimators under heteroskedasticity and tail dependence.
- Proposes a generative high quantile homogeneity test that assesses whether explanatory variables have uniform effects across tail quantiles.
- Establishes theoretical foundations for converting nonlinear high quantile regression inference into linear form analysis with explicit error bounds.

## Open Questions & Future Work

- [[unified-inference-high-quantile-regression]]

## Key Concepts

- [[bahadur-representation-high-quantile-regression]]: A technique that decomposes nonlinear high quantile regression estimators into linear forms with explicit error bounds for tail-dependent time series.

## Archivist Review

The approved concepts and open questions address fundamental theoretical bottlenecks in extreme value statistics and quantile regression. I have limited approvals to the central theoretical contribution (Bahadur representation) and the primary unresolved inferential limitation noted in the paper, ensuring these entries remain high-level and broadly relevant for future statistical time series research.

### Approved Concepts
- Bahadur representation for high quantile regression: It provides the theoretical foundation for reducing complex nonlinear high quantile regression estimator problems into manageable linear forms.

### Approved Open Questions
- Unified Inference in High Quantile Regression: This is a fundamental bottleneck in high quantile statistics where asymptotic validity often depends on specific, often unverifiable, assumptions about the rate of extremeness, hindering the reliability of automated or general-purpose statistical software for tail analysis.

## Links

- [Abstract](https://arxiv.org/abs/2605.10915)
- [PDF](https://arxiv.org/pdf/2605.10915)

