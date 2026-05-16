---
# CSL-compatible fields
title: "Scenario generation of intraday electricity price paths for optimal trading in continuous markets"
author:
  - literal: "Andrzej Puć"
  - literal: "Joanna Janczura"
issued:
  date-parts:
    - [2026, 5, 13]
url: "https://arxiv.org/abs/2605.13446"

# Custom fields
paper_id: "2605.13446"
paper_source: "openalex"
domain: "time-series"
tags:
  - "forecast-reconciliation"
architectures:
  []
datasets:
  []
concept_slugs:
  - "support-vector-sorting"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-16T06:01:54Z"
created_at: "2026-05-16T06:01:54Z"
---

# Scenario generation of intraday electricity price paths for optimal trading in continuous markets

**Authors**: Andrzej Puć, Joanna Janczura
**Date**: 2026-05-13
**Paper ID**: [openalex:2605.13446](https://arxiv.org/abs/2605.13446)

## Summary

This paper presents an ensemble forecasting framework for intraday electricity prices that moves beyond point estimates to probabilistic trajectory generation. The authors propose a novel Support Vector Sorting procedure to select representative scenarios, enabling more efficient decision-making in continuous markets. The approach is evaluated using German intraday transaction data, showing that incorporating fundamental scenario-based errors and dynamic reweighting improves both forecast accuracy and trading profitability compared to naive benchmarks. The methodology bridges the gap between statistical point prediction and adaptive economic strategy in volatile energy markets.

## Key Contributions

- Introduces an ensemble forecasting framework that extends SVR-based point predictions to probabilistic trajectory scenarios.
- Develops Support Vector Sorting to efficiently distill representative price path scenarios for adaptive trading.
- Demonstrates superior statistical and economic performance against standard benchmarks in the German intraday electricity market.
- Validates that scenario-based dynamic reweighting increases profitability while maintaining robust risk management.

## Open Questions & Future Work

- [[weather-informed-scenario-generation]]

## Key Concepts

- [[support-vector-sorting]]: A method for selecting representative scenarios from probabilistic price path forecasts to improve trading decision-making.

## Archivist Review

I approved the concept of 'Support Vector Sorting' as a reusable mechanism for scenario reduction in time-series forecasting. I also approved one open question concerning weather-informed generation, as it identifies a clear limitation in current electricity market forecasting frameworks. Other candidates were rejected for being either incremental or too tied to the specific domain application.

### Approved Concepts
- Support Vector Sorting: This procedure is the core technical innovation for selecting representative scenarios from probabilistic trajectory forecasts.

### Approved Open Questions
- Weather-informed scenario generation: External weather data is a primary driver of renewable energy production and thus electricity price dynamics; integrating it could significantly enhance the predictive power and realism of generated scenarios.

### Rejected Candidates
- [open_question] Volatility-aware scenario reweighting (`volatility-aware-scenario-reweighting`) - low_impact: The question is a incremental improvement on the current mechanism rather than a substantial research bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2605.13446)
- [PDF](https://arxiv.org/pdf/2605.13446)

