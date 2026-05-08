---
# CSL-compatible fields
title: "Bayesian Modelling of Nonstationary Extreme Values Using a Nonparametric Hawkes Process"
author:
  - literal: "Gordon J. Ross"
  - literal: "Dean Markwick"
issued:
  date-parts:
    - [2026, 5, 5]
url: "https://arxiv.org/abs/2605.03331"

# Custom fields
paper_id: "2605.03331"
paper_source: "openalex"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "nonparametric-hawkes-extreme-value-modeling"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-08T05:44:52Z"
created_at: "2026-05-08T05:44:52Z"
---

# Bayesian Modelling of Nonstationary Extreme Values Using a Nonparametric Hawkes Process

**Authors**: Gordon J. Ross, Dean Markwick
**Date**: 2026-05-05
**Paper ID**: [openalex:2605.03331](https://arxiv.org/abs/2605.03331)

## Summary

This paper introduces a Bayesian nonparametric framework for modeling nonstationary extreme value processes by combining self-exciting Hawkes processes with hierarchical Extreme Value Theory. By utilizing a Dirichlet process to capture temporal excitation patterns and a Generalized Pareto Distribution with partial pooling for event magnitudes, the model effectively handles clustered and sparse extreme event data. Empirical results across four real-world datasets confirm the approach's effectiveness in predictive performance for extreme events.

## Key Contributions

- Proposes a Bayesian point process model that integrates a self-exciting Hawkes process with nonparametric Dirichlet process learning to capture nonstationary event rates.
- Integrates Extreme Value Theory via a Generalised Pareto Distribution with a hierarchical mark structure, enabling partial pooling for robust magnitude estimation in sparse clusters.
- Demonstrates superior predictive performance on four real-world datasets compared to existing extreme value modeling baselines.

## Open Questions & Future Work

- [[nonstationary-extreme-value-extensions]]

## Key Concepts

- [[nonparametric-hawkes-extreme-value-modeling]]: A Bayesian nonparametric framework that models extreme event sequences as clustered processes with magnitudes governed by a hierarchically-pooled Generalized Pareto Distribution.

## Archivist Review

The paper presents a coherent framework for handling nonstationary extremes using Bayesian point processes. I have approved the overarching model as a key concept, as it represents a significant, reusable paradigm in time series analysis for extremes. The open question was approved for its focus on addressing real-world complexities (covariates, nonstationarity, and multivariate dependencies) in extreme event forecasting. No datasets were approved as none were specifically named as persistent research benchmarks.

### Approved Concepts
- Nonparametric Hawkes Extreme Value Modeling: Combines point process self-excitation with extreme value theory to handle nonstationarity in extreme event occurrence and magnitude, providing a robust Bayesian alternative to stationary extremes modeling.

### Approved Open Questions
- Extending Nonstationary Extreme Models: These extensions are critical for moving from idealized, self-contained data analysis toward robust, real-world forecasting systems that can account for exogenous drivers and interconnected risk events.

### Rejected Candidates
- [concept] Hierarchical Generalized Pareto Pooling (`nonparametric-hawkes-process-mark-pooling`) - subcomponent_of_broader_mechanism: This is a specific subcomponent of the broader nonparametric Hawkes extreme value modeling framework which is being approved as a single concept.

## Links

- [Abstract](https://arxiv.org/abs/2605.03331)
- [PDF](https://arxiv.org/pdf/2605.03331)

