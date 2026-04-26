---
# CSL-compatible fields
title: "Modeling dependency between operational risk losses and macroeconomic variables using Hidden Markov Models"
author:
  - literal: "Nikeethan Selvaratnam"
  - literal: "Dorinel Bastide"
  - literal: "Clément Fernandes"
  - literal: "Wojciech Pieczynski"
issued:
  date-parts:
    - [2026, 4, 23]
url: "https://arxiv.org/abs/2604.21734"

# Custom fields
paper_id: "2604.21734"
paper_source: "openalex"
domain: "time-series"
tags:
  - "time-series"
  - "forecasting"
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-26T05:52:42Z"
created_at: "2026-04-26T05:52:42Z"
---

# Modeling dependency between operational risk losses and macroeconomic variables using Hidden Markov Models

**Authors**: Nikeethan Selvaratnam, Dorinel Bastide, Clément Fernandes, Wojciech Pieczynski
**Date**: 2026-04-23
**Paper ID**: [openalex:2604.21734](https://arxiv.org/abs/2604.21734)

## Summary

This paper addresses the difficulty of modeling operational risk losses by extending Hidden Markov Models (HMMs) to a multivariate framework that incorporates macroeconomic covariates. By introducing a third auxiliary variable to capture economic influences, the model provides a more robust approach to stress testing and dependency analysis. The authors utilize an Expectation-Maximization algorithm for model calibration and evaluate the approach across diverse operational risk-event categories.

## Key Contributions

- Introduces a multivariate Hidden Markov Model (HMM) extension to model the relationship between operational risk losses and macroeconomic covariates.
- Develops an Expectation-Maximization (EM) calibration framework specifically adapted for operational risk event data.
- Demonstrates the relevance and performance impact of integrating macroeconomic variables into risk loss forecasting through empirical analysis across various risk-event types.

## Open Questions & Future Work

- [[heavy-tailed-hmm-operational-risk]]
- [[covariate-selection-operational-risk]]

## Archivist Review

The paper proposes a specific extension of HMMs for operational risk management. I have approved the two open questions as they address fundamental limitations in modeling tail risk and covariate relevance, which are central research challenges in financial time-series forecasting. No new concepts were approved as the proposed HMM extension is a specific application of existing methodology rather than a generalized reusable mechanism.

### Approved Open Questions
- Heavy-tailed HMM for operational risk: This extension is critical for financial risk management where the underestimation of extreme losses (tail risk) leads to significant capital inadequacy.
- Event-specific covariate selection for risk: Identifying the correct covariates for different risk categories is essential for accurate stress testing and capital planning in financial institutions.

## Links

- [Abstract](https://arxiv.org/abs/2604.21734)
- [PDF](https://arxiv.org/pdf/2604.21734)

