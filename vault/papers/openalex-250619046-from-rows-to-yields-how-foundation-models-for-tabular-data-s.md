---
# CSL-compatible fields
title: "From rows to yields: how foundation models for tabular data simplify crop yield prediction"
author:
  - literal: "Filip Sabo"
  - literal: "Michele Meroni"
  - literal: "María Piles"
  - literal: "Martin Claverie"
  - literal: "Fanie Ferreira"
  - literal: "Elna Van Den Berg"
  - literal: "Francesco Collivignarelli"
  - literal: "Felix Rembold"
issued:
  date-parts:
    - [2026, 4, 24]
url: "https://arxiv.org/abs/2506.19046"

# Custom fields
paper_id: "2506.19046"
paper_source: "openalex"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "tabpfn"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-27T06:02:04Z"
created_at: "2026-04-27T06:02:04Z"
---

# From rows to yields: how foundation models for tabular data simplify crop yield prediction

**Authors**: Filip Sabo, Michele Meroni, María Piles, Martin Claverie, Fanie Ferreira, Elna Van Den Berg, Francesco Collivignarelli, Felix Rembold
**Date**: 2026-04-24
**Paper ID**: [openalex:2506.19046](https://arxiv.org/abs/2506.19046)

## Summary

This paper evaluates the performance of the TabPFN foundation model for sub-national crop yield forecasting in South Africa using multitemporal Earth Observation and weather data. By benchmarking against traditional ML and statistical models over a 23-year period, the authors demonstrate that while TabPFN achieves accuracy comparable to supervised learners, it offers significant practical advantages in reduced feature engineering and rapid model configuration. The findings highlight the potential of in-context learning tabular models to simplify predictive workflows in agricultural monitoring.

## Key Contributions

- Demonstrated the application of TabPFN for sub-national crop yield forecasting (maize, soybeans, sunflowers) in South Africa using EO and weather data.
- Compared TabPFN against six standard ML models and two baselines, showing competitive performance (8.8% rRMSEp) while significantly reducing feature engineering and tuning overhead.
- Validated model generalizability using a leave-one-year-out cross-validation framework over a 23-year span.

## Key Concepts

- [[tabpfn]]: A foundation model architecture for small- to medium-sized tabular data that enables in-context learning, eliminating the need for traditional per-task fine-tuning or heavy feature engineering.

## Archivist Review

I approved TabPFN as a central concept because it is a distinct, reusable paradigm for tabular forecasting that is being increasingly applied in time-series domains. The proposed application to crop yields was rejected as a concept to keep the vault focused on methods rather than specific use-case adaptations. No new datasets or open questions met the high bar for permanent archival.

### Approved Concepts
- TabPFN: The paper demonstrates the efficacy of using prior-data fitted networks for agricultural forecasting, specifically highlighting the trade-off between absolute accuracy and engineering overhead.

### Rejected Candidates
- [concept] TabPFN for Crop Yield Forecasting (`tabpfn-crop-yield-adaptation`) - subcomponent_of_broader_mechanism: This is a specific application instance rather than a foundational concept, and it is covered by the broader TabPFN entry.

## Links

- [Abstract](https://arxiv.org/abs/2506.19046)
- [PDF](https://arxiv.org/pdf/2506.19046)

