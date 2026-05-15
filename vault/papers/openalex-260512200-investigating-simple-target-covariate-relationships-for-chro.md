---
# CSL-compatible fields
title: "Investigating simple target-covariate relationships for Chronos-2 and TabPFN-TS"
author:
  - literal: "Gaspard Berthelier"
  - literal: "Mariia Baranova"
  - literal: "Andrei-Tiberiu Pantea"
  - literal: "Etienne Le Naour"
  - literal: "Adrien Petralia"
  - literal: "Tahar Nabil"
  - literal: "Themis Palpanas"
issued:
  date-parts:
    - [2026, 5, 12]
url: "https://arxiv.org/abs/2605.12200"

# Custom fields
paper_id: "2605.12200"
paper_source: "openalex"
domain: "time-series"
tags:
  - "forecasting"
  - "time-series-foundation-models"
  - "benchmarking"
architectures:
  []
datasets:
  []
concept_slugs:
  - "tabpfn-ts"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-15T06:15:29Z"
created_at: "2026-05-15T06:15:29Z"
---

# Investigating simple target-covariate relationships for Chronos-2 and TabPFN-TS

**Authors**: Gaspard Berthelier, Mariia Baranova, Andrei-Tiberiu Pantea, Etienne Le Naour, Adrien Petralia, Tahar Nabil, Themis Palpanas
**Date**: 2026-05-12
**Paper ID**: [openalex:2605.12200](https://arxiv.org/abs/2605.12200)

## Summary

This paper investigates the ability of state-of-the-art Time Series Foundation Models (TSFMs), specifically Chronos-2 and TabPFN-TS, to capture fundamental target-covariate relationships. Through controlled diagnostic experiments, the authors reveal that while both models excel in broader benchmarks, TabPFN-TS significantly outperforms Chronos-2 in capturing these dependencies, particularly for short-term forecasting. The findings highlight that general zero-shot performance does not necessarily equate to robust modeling of explicit feature-target interactions.

## Key Contributions

- Conducts controlled diagnostic experiments to evaluate the target-covariate integration capabilities of Chronos-2 and TabPFN-TS.
- Demonstrates that TabPFN-TS outperforms Chronos-2 in modeling simple target-covariate dependencies, particularly over short forecasting horizons.
- Challenges the assumption that superior general benchmark performance in TSFMs guarantees effective modeling of fundamental covariate-target relationships.

## Open Questions & Future Work

- [[hybrid-temporal-tabular-foundation-models]]

## Key Concepts

- [[tabpfn-ts]]: A Transformer-based foundation model for tabular and time series data that treats forecasting as an in-context regression problem.

## Archivist Review

The analysis correctly highlights the contrast between generative TSFMs and in-context learners. I approved TabPFN-TS as a distinct architectural paradigm for time series, but rejected Chronos-2 as it is a specific model instance rather than a generic category. The open question is well-framed and reflects a significant ongoing challenge in the field.

### Approved Concepts
- TabPFN-TS: The paper identifies it as a distinct model class for covariate-target relationship modeling in TSFMs compared to autoregressive foundations.

### Approved Open Questions
- Unified Temporal-Tabular Foundation Architectures: Current time series foundation models typically excel at either univariate temporal modeling or feature-target regression, creating a performance gap in domains where both patterns are crucial for accuracy.

### Rejected Candidates
- [concept] Chronos-2 (`chronos-2`) - paper_local: Chronos-2 is a specific model implementation rather than a foundational methodological concept.

## Links

- [Abstract](https://arxiv.org/abs/2605.12200)
- [PDF](https://arxiv.org/pdf/2605.12200)

