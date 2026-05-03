---
# CSL-compatible fields
title: "Probabilistic Circuits for Irregular Multivariate Time Series Forecasting"
author:
  - literal: "Christian Klötergens"
  - literal: "Vijaya Krishna Yalavarthi"
  - literal: "Lars Schmidt-Thieme"
issued:
  date-parts:
    - [2026, 4, 30]
url: "https://arxiv.org/abs/2604.27814"

# Custom fields
paper_id: "2604.27814"
paper_source: "openalex"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "probabilistic-circuits-time-series"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-03T06:02:12Z"
created_at: "2026-05-03T06:02:12Z"
---

# Probabilistic Circuits for Irregular Multivariate Time Series Forecasting

**Authors**: Christian Klötergens, Vijaya Krishna Yalavarthi, Lars Schmidt-Thieme
**Date**: 2026-04-30
**Paper ID**: [openalex:2604.27814](https://arxiv.org/abs/2604.27814)

## Summary

CircuITS is a novel architecture for irregular multivariate time series (IMTS) forecasting that utilizes probabilistic circuits to model joint probability distributions. By leveraging the structural properties of probabilistic circuits, the model maintains consistent marginalization while capturing complex inter-channel dependencies. It addresses the common challenge of unreliable uncertainty quantification in IMTS by guaranteeing valid joint distributions, outperforming existing state-of-the-art baselines in density estimation tasks.

## Key Contributions

- Introduces CircuITS, a probabilistic circuit architecture designed specifically for irregular multivariate time series (IMTS) forecasting.
- Ensures structurally valid joint probability distributions, enabling consistent marginalization for multi-channel dependencies.
- Demonstrates superior joint and marginal density estimation performance against state-of-the-art baselines across four real-world datasets.

## Open Questions & Future Work

- [[variable-ordering-complexity-bottleneck]]

## Key Concepts

- [[probabilistic-circuits-time-series]]: An architectural framework using probabilistic circuits to guarantee consistent marginalization and valid joint density estimation in multivariate time series forecasting.

## Archivist Review

The paper introduces an architectural approach to multivariate forecasting using probabilistic circuits to address the marginalization consistency problem. I approved the concept of using probabilistic circuits for time series and a generalized version of the open question regarding the variable ordering bottleneck, which is a significant structural challenge in high-dimensional probabilistic modeling. Other candidates were rejected to prioritize clarity and broader applicability in the vault.

### Approved Concepts
- Probabilistic Circuits for Time Series: Probabilistic circuits offer a principled way to maintain exact marginalization and valid joint density estimation in multivariate settings, which is a major bottleneck in standard neural forecasting.

### Approved Open Questions
- Variable Ordering Complexity Bottleneck: This is a fundamental limitation for any structural probabilistic forecasting model that relies on sequential variable decomposition, affecting both accuracy and generalizability.

### Rejected Candidates
- [open_question] Optimal Channel Ordering in SPNs (`optimal-channel-ordering-spn`) - duplicate_existing: The candidate was renamed to a more generalized and descriptive slug to better reflect its broader relevance beyond just SPNs.

## Links

- [Abstract](https://arxiv.org/abs/2604.27814)
- [PDF](https://arxiv.org/pdf/2604.27814)

