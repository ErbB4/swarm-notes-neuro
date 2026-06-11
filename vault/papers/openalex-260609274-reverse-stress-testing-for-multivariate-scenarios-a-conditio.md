---
# CSL-compatible fields
title: "Reverse Stress Testing for Multivariate Scenarios: A Conditional Framework for Stressed Time Series"
author:
  - literal: "Michele Sparviero"
  - literal: "Lorenzo Viola"
issued:
  date-parts:
    - [2026, 6, 8]
url: "https://arxiv.org/abs/2606.09274"

# Custom fields
paper_id: "2606.09274"
paper_source: "openalex"
domain: "time-series"
tags:
  - "probabilistic-forecasting"
  - "risk-modeling"
architectures:
  []
datasets:
  []
concept_slugs:
  - "reverse-stress-testing-framework"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-06-11T06:35:44Z"
created_at: "2026-06-11T06:35:44Z"
---

# Reverse Stress Testing for Multivariate Scenarios: A Conditional Framework for Stressed Time Series

**Authors**: Michele Sparviero, Lorenzo Viola
**Date**: 2026-06-08
**Paper ID**: [openalex:2606.09274](https://arxiv.org/abs/2606.09274)

## Summary

This paper introduces a conditional framework for reverse stress testing (RST) that reconstructs multivariate time series scenarios consistent with market dependence structures from a specific exogenous shock. The approach is formulated as a conditional density maximization problem and implemented across three distinct tiers: parametric (Gaussian), semiparametric (empirical likelihood), and nonparametric (inverse-distance resampling). Validation on real market data confirms that the framework produces economically coherent scenarios capable of capturing complex risk-reward asymmetries typical of stressed market conditions.

## Key Contributions

- Develops a formal framework for Reverse Stress Testing (RST) that reconstructs coherent multivariate scenarios from single exogenous asset shocks via conditional density maximization.
- Provides a hierarchy of solutions across parametric, semiparametric (empirical likelihood), and fully nonparametric (inverse-distance resampling) distributional assumptions.
- Demonstrates that the generated stress scenarios effectively replicate market risk-reward asymmetries observed in empirical historical regimes.

## Key Concepts

- [[reverse-stress-testing-framework]]: A methodological framework for reconstructing coherent multivariate time series scenarios by maximizing the conditional density given a prescribed exogenous shock.

## Archivist Review

I approved the Reverse Stress Testing (RST) framework as the central contribution of this work, as it defines a reusable formalization for generating multivariate scenarios from specific shocks. The tiered implementation variants (parametric, semiparametric, nonparametric) were rejected as they represent subcomponents or specific instantiations of this broader methodological framework rather than distinct, reusable concepts in their own right.

### Approved Concepts
- Reverse Stress Testing (RST) Framework: The paper formalizes RST as a conditional density maximization problem, providing a structured approach to generating multivariate scenarios consistent with empirical dependencies rather than simple linear perturbations.

### Rejected Candidates
- [concept] Parametric Stress Testing Variant (`parametric-stress-testing`) - subcomponent_of_broader_mechanism: This is a specific implementation variant of the broader RST framework.
- [concept] Semiparametric Empirical Likelihood Stressing (`semiparametric-empirical-likelihood-stressing`) - subcomponent_of_broader_mechanism: This is a specific implementation variant of the broader RST framework.
- [concept] Nonparametric Inverse-Distance Resampling (`nonparametric-inverse-distance-resampling`) - subcomponent_of_broader_mechanism: This is a specific implementation variant of the broader RST framework.

## Links

- [Abstract](https://arxiv.org/abs/2606.09274)
- [PDF](https://arxiv.org/pdf/2606.09274)

