---
# CSL-compatible fields
title: "A Comparative Study on how Data Normalization Affects Zero-Shot Generalization in Time Series Foundation Models"
author:
  - literal: "Ihab Ahmed"
  - literal: "Denis Krompaß"
  - literal: "Cheng Feng"
  - literal: "Volker Tresp"
issued:
  date-parts:
    - [2026, 4, 21]
url: "https://arxiv.org/abs/2512.02833"

# Custom fields
paper_id: "2512.02833"
paper_source: "openalex"
domain: "time-series"
tags:
  - "time-series-foundation-models"
  - "normalization"
  - "zero-shot-learning"
  - "time-series-forecasting"
  - "generalization"
architectures:
  []
datasets:
  []
concept_slugs:
  - "revin"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-24T05:50:29Z"
created_at: "2026-04-24T05:50:29Z"
---

# A Comparative Study on how Data Normalization Affects Zero-Shot Generalization in Time Series Foundation Models

**Authors**: Ihab Ahmed, Denis Krompaß, Cheng Feng, Volker Tresp
**Date**: 2026-04-21
**Paper ID**: [openalex:2512.02833](https://arxiv.org/abs/2512.02833)

## Summary

This paper investigates the role of input normalization in time series foundation models (TSFMs) to address challenges posed by scale variation and non-stationarity. By evaluating four diverse TSFM architectures, the study determines that RevIN consistently achieves superior zero-shot performance and efficiency without requiring dataset-specific preprocessing. The findings highlight the critical interaction between normalization methods, model architecture, and training objectives in determining the effectiveness of zero-shot generalization.

## Key Contributions

- Identifies RevIN as the most efficient normalization strategy for TSFMs, reducing zero-shot MASE by 89% against raw baselines.
- Demonstrates that optimal normalization for TSFMs is highly dependent on architectural choices (point-forecast vs. distribution vs. LLM-based) and loss functions.
- Provides an empirical analysis of how input normalization affects zero-shot generalization and accuracy-efficiency trade-offs in time series foundation models.

## Open Questions & Future Work

- [[tsfm-normalization-architectural-sensitivity]]

## Key Concepts

- [[revin]]: A reversible instance normalization technique designed to handle non-stationarity and scale variation in time series data.

## Archivist Review

I approved 'RevIN' as a central concept because the paper establishes its efficacy in the context of TSFMs, shifting it from a standard preprocessing step to a key architectural consideration. I also added an open question regarding the sensitivity of foundation model architectures to different normalization techniques, as this addresses a specific research bottleneck in zero-shot time-series forecasting. I rejected no candidates because the user only provided one concept and no open questions.

### Approved Concepts
- RevIN: The study provides empirical validation that RevIN, originally for traditional time-series models, is highly effective for improving zero-shot generalization in Foundation Models.

### Approved Open Questions
- TSFM Normalization Architectural Sensitivity: Clarifying this architectural sensitivity is critical for designing future time-series foundation models that robustly handle distribution shifts.

## Links

- [Abstract](https://arxiv.org/abs/2512.02833)
- [PDF](https://arxiv.org/pdf/2512.02833)

