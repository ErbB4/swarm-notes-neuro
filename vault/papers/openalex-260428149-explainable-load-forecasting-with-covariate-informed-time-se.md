---
# CSL-compatible fields
title: "Explainable Load Forecasting with Covariate-Informed Time Series Foundation Models"
author:
  - literal: "Matthias Hertel"
  - literal: "Alexandra Nikoltchovska"
  - literal: "Sebastian Pütz"
  - literal: "Ralf Mikut"
  - literal: "Benjamin Schäfer"
  - literal: "Veit Hagenmeyer"
issued:
  date-parts:
    - [2026, 4, 30]
url: "https://arxiv.org/abs/2604.28149"

# Custom fields
paper_id: "2604.28149"
paper_source: "openalex"
domain: "nlp"
tags:
  - "time-series-question-answering-tsqa"
  - "patch-based-information-fusion-network"
architectures:
  []
datasets:
  []
concept_slugs:
  - "shap-for-time-series-foundation-models"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-03T06:02:28Z"
created_at: "2026-05-03T06:02:28Z"
---

# Explainable Load Forecasting with Covariate-Informed Time Series Foundation Models

**Authors**: Matthias Hertel, Alexandra Nikoltchovska, Sebastian Pütz, Ralf Mikut, Benjamin Schäfer, Veit Hagenmeyer
**Date**: 2026-04-30
**Paper ID**: [openalex:2604.28149](https://arxiv.org/abs/2604.28149)

## Summary

This paper addresses the transparency gap in using Time Series Foundation Models (TSFMs) for critical infrastructure by proposing an efficient SHAP-based explanation algorithm. By leveraging the flexible context window and covariate inputs of models like Chronos-2 and TabPFN-TS, the approach enables scalable model interpretability. The framework is evaluated on day-ahead load forecasting, where it demonstrates competitive zero-shot performance and aligns with expert domain knowledge regarding weather and calendar dependencies.

## Key Contributions

- Introduces an efficient SHAP-based explanation algorithm tailored for Time Series Foundation Models (TSFMs) by utilizing their ability to handle varying context lengths and covariates.
- Demonstrates that Chronos-2 and TabPFN-TS, in a zero-shot setting, achieve performance competitive with domain-specific Transformer models on TSO day-ahead load forecasting.
- Validates that the proposed explanation framework successfully recovers domain-consistent insights, specifically confirming the importance of weather and calendar features for power load prediction.

## Open Questions & Future Work

- [[efficient-shap-tsfm-computation]]

## Key Concepts

- [[shap-for-time-series-foundation-models]]: An algorithm for computing SHAP values for time series foundation models by exploiting their inherent flexibility in input context length and covariate handling.

## Archivist Review

I have approved the SHAP-for-TSFM concept and the open question regarding its computational efficiency. These represent a methodological contribution to the intersection of foundation models and interpretability in time series, and a clear, non-trivial research bottleneck. I rejected the generalizability question as it is a typical request for further empirical validation rather than a core research problem.

### Approved Concepts
- SHAP for Time Series Foundation Models: Addresses the critical need for explainability in black-box foundation models applied to high-stakes infrastructure like power grids.

### Approved Open Questions
- Efficient SHAP for TSFMs: Developing more efficient SHAP computation methods is critical for the practical deployment of high-performance TSFMs in real-time, resource-constrained energy infrastructure monitoring.

### Rejected Candidates
- [open_question] Generalizability of TSFM Explainability (`generalizability-tsfm-explainability`) - low_impact: This is a standard application request for broader evaluation, not a fundamental technical or methodological bottleneck for the vault.

## Links

- [Abstract](https://arxiv.org/abs/2604.28149)
- [PDF](https://arxiv.org/pdf/2604.28149)

