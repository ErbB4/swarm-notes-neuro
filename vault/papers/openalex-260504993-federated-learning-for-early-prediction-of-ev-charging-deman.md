---
# CSL-compatible fields
title: "Federated Learning for Early Prediction of EV Charging Demand"
author:
  - literal: "Vasilis Perifanis"
  - literal: "Foteini Nikolaidou"
  - literal: "Nikolaos Pavlidis"
  - literal: "Panagiotis Thomakos"
  - literal: "Andreas Sendros"
issued:
  date-parts:
    - [2026, 5, 6]
url: "https://arxiv.org/abs/2605.04993"

# Custom fields
paper_id: "2605.04993"
paper_source: "openalex"
domain: "time-series"
tags:
  - "federated-learning"
  - "energy-forecasting"
  - "privacy-preserving-ml"
  - "ev-charging-demand"
architectures:
  []
datasets:
  - "acn-data"
concept_slugs:
  []
dataset_slugs:
  - "acn-data"
skill: "TimeSeriesSkill"
processed_at: "2026-05-09T05:58:24Z"
created_at: "2026-05-09T05:58:24Z"
---

# Federated Learning for Early Prediction of EV Charging Demand

**Authors**: Vasilis Perifanis, Foteini Nikolaidou, Nikolaos Pavlidis, Panagiotis Thomakos, Andreas Sendros
**Date**: 2026-05-06
**Paper ID**: [openalex:2605.04993](https://arxiv.org/abs/2605.04993)

## Summary

This paper addresses the challenge of early electric vehicle charging demand prediction by estimating total session energy using only initial data available at plug-in and the first few minutes of charging. The authors leverage a federated learning framework to train models across distributed charging infrastructure, specifically testing on the Adaptive Charging Network (ACN) dataset. Their results demonstrate that federated models effectively balance data privacy with predictive accuracy, providing a scalable solution for EV network operators.

## Key Contributions

- Formulates the problem of early EV charging demand prediction using only plug-in data and initial charging measurements.
- Demonstrates that federated learning models achieve predictive performance comparable to centralized baselines for charging demand estimation.
- Introduces a session-level feature engineering approach for EV infrastructure that captures user intent and initial charging behaviors.

## Open Questions & Future Work

- [[cross-depot-federated-learning-scalability]]

## Archivist Review

The paper provides a localized application of Federated Learning to a specific EV charging problem. I have approved the open question regarding cross-depot FL scalability as it addresses a substantive bottleneck in distributed time-series infrastructure. The dataset was approved for its role as a specific, named benchmark for this domain. Other concepts were rejected as either application-specific or routine methodology.

### Approved Open Questions
- Cross-Depot Federated Learning Scalability: Scaling FL from a single depot to multiple depots introduces significant challenges related to data distribution shifts, varying connectivity, and communication efficiency across heterogeneous site-level infrastructures.

### Rejected Candidates
- [concept] Early EV charging demand prediction (`early-ev-charging-demand-prediction`) - not_reusable: This is an application-specific framing rather than a reusable methodological mechanism for the vault.
- [concept] Session-level feature engineering approach (`session-level-feature-engineering`) - not_novel: Feature engineering techniques are highly domain-specific and routine rather than foundational architectural contributions.

## Datasets

- [[acn-data]]

## Links

- [Abstract](https://arxiv.org/abs/2605.04993)
- [PDF](https://arxiv.org/pdf/2605.04993)

