---
# CSL-compatible fields
title: "Modelling Time Series of Counts with Hysteresis"
author:
  - literal: "Xuanye Ma"
  - literal: "Dong Li"
  - literal: "Howell Tong"
issued:
  date-parts:
    - [2026, 4, 13]
url: "https://arxiv.org/abs/2509.15508"

# Custom fields
paper_id: "2509.15508"
paper_source: "openalex"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-16T05:46:15Z"
created_at: "2026-04-16T05:46:15Z"
---

# Modelling Time Series of Counts with Hysteresis

**Authors**: Xuanye Ma, Dong Li, Howell Tong
**Date**: 2026-04-13
**Paper ID**: [openalex:2509.15508](https://arxiv.org/abs/2509.15508)

## Summary

This paper presents the Hysteretic Poisson Autoregressive (HPART) model, a novel approach for modelling count-valued time series that incorporates scientifically grounded hysteresis into a piecewise linear structure. By extending traditional Poisson autoregressive dynamics, the model improves upon the existing Buffered Poisson Autoregressive (BPART) model by offering more nuanced regime-switching capabilities. The authors provide a rigorous statistical foundation for estimation and testing and demonstrate superior interpretability and out-of-sample forecasting performance on real-world datasets.

## Key Contributions

- Introduces the Hysteretic Poisson Autoregressive (HPART) model, a nonlinear extension of linear Poisson autoregressive models incorporating genuine hysteresis via a controlling factor.
- Establishes a unified framework for maximum likelihood estimation and asymptotic property derivation for both HPART and Buffered Poisson Autoregressive (BPART) models.
- Develops hypothesis tests for non-nested model comparison between BPART and HPART models to guide empirical selection.

## Open Questions & Future Work

- [[intercept-variance-count-models]]

## Archivist Review

I have approved the open question regarding intercept variance in count models because it identifies a concrete, persistent theoretical gap that transcends the specific HPART model introduced here. The proposed model itself (HPART) was rejected because it is a specific, specialized statistical architecture that does not meet the criteria for a high-level, reusable concept or paradigm.

### Approved Open Questions
- Intercept parameter variance in count models: Understanding this persistent estimation issue is crucial for improving the robustness and interpretability of count time series models, which are widely used in financial and public health forecasting.

### Rejected Candidates
- [concept] Hysteretic Poisson Autoregressive (HPART) model (`hpart-model`) - not_reusable: This is a specific, narrow statistical model rather than a general-purpose concept likely to recur as a primary research topic across future domains.

## Links

- [Abstract](https://arxiv.org/abs/2509.15508)
- [PDF](https://arxiv.org/pdf/2509.15508)

