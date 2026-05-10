---
# CSL-compatible fields
title: "Scalable model selection for count time series with structural breaks: application to solid-organ transplantation during and after COVID-19 in the USA and Italy"
author:
  - literal: "Tobia Filosi"
  - literal: "Emiliano Ceccarelli"
  - literal: "Emilio Porcu"
  - literal: "Elena Del Sordo"
  - literal: "Libia Lara-Carrión"
  - literal: "Giuseppe Iuppa"
  - literal: "Francesca Puoti"
  - literal: "Silvia Trapani"
  - literal: "Silvia Testa"
  - literal: "Giovanna Jona Lasinio"
issued:
  date-parts:
    - [2026, 5, 7]
url: "https://arxiv.org/abs/2605.06168"

# Custom fields
paper_id: "2605.06168"
paper_source: "openalex"
domain: "time-series"
tags:
  - "time-series"
  - "forecasting"
  - "count-data"
  - "structural-breaks"
  - "model-selection"
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-10T06:03:33Z"
created_at: "2026-05-10T06:03:33Z"
---

# Scalable model selection for count time series with structural breaks: application to solid-organ transplantation during and after COVID-19 in the USA and Italy

**Authors**: Tobia Filosi, Emiliano Ceccarelli, Emilio Porcu, Elena Del Sordo, Libia Lara-Carrión, Giuseppe Iuppa, Francesca Puoti, Silvia Trapani, Silvia Testa, Giovanna Jona Lasinio
**Date**: 2026-05-07
**Paper ID**: [openalex:2605.06168](https://arxiv.org/abs/2605.06168)

## Summary

This paper proposes a systematic approach for model selection in count time series data characterized by temporal dependence and structural shifts, such as those induced by the COVID-19 pandemic. The authors employ an expanding-window evaluation protocol to compare Poisson and negative-binomial models across multiple transplant strata in the USA and Italy. Results indicate that while structural break indicators are crucial, external auxiliary covariates provide negligible predictive gains over simpler autoregressive structures, supporting the use of more parsimonious, unconditional forecasting models.

## Key Contributions

- Develops a scalable model selection framework for count time series featuring structural breaks, specifically addressing healthcare activity disruptions.
- Validates the approach on solid organ transplantation (SOT) data in the USA and Italy (2014-2024), utilizing Poisson and negative-binomial specifications with holiday and pandemic-period indicators.
- Demonstrates that unconditional autoregressive modeling often outperforms models augmented with external COVID-19 burden covariates in predicting transplant activity.

## Open Questions & Future Work

- [[scalable-model-selection-count-time-series-shocks]]

## Archivist Review

The paper addresses count time series with structural breaks, but does not propose a sufficiently novel architectural or algorithmic concept beyond standard model selection practices for generalized linear models. The open question was approved for its focus on the methodological challenge of handling structural breaks in count data, which is a significant bottleneck in time-series forecasting. No new datasets were identified as they were not clearly defined or provided as reusable research assets.

### Approved Open Questions
- Scalable Model Selection for Count Time Series with Shocks: This reflects a critical methodological bottleneck in applying time-series analysis to non-stationary count data, where intervention indicators often serve as opaque proxies for complex dynamical shifts. Improving these frameworks is essential for reliable decision-making in healthcare and other systemically sensitive domains.

### Rejected Candidates
- [open_question] Scalable Model Selection for Count Time Series with Shocks (`scalable-model-selection-count-time-series-shocks`) - duplicate_existing: This was already captured as an open question.

## Links

- [Abstract](https://arxiv.org/abs/2605.06168)
- [PDF](https://arxiv.org/pdf/2605.06168)

