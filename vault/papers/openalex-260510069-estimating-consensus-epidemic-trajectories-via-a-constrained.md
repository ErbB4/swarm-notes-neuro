---
# CSL-compatible fields
title: "Estimating Consensus Epidemic Trajectories via a Constrained Power Fréchet Mean with Functional Registration"
author:
  - literal: "Yui Tomo"
  - literal: "Shu Tamano"
  - literal: "Daisuke Yoneoka"
issued:
  date-parts:
    - [2026, 5, 11]
url: "https://arxiv.org/abs/2605.10069"

# Custom fields
paper_id: "2605.10069"
paper_source: "openalex"
domain: "time-series"
tags:
  - "time-series"
  - "time-series-forecasting"
  - "bayesian-inference"
architectures:
  []
datasets:
  []
concept_slugs:
  - "constrained-power-frechet-mean"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-14T06:10:45Z"
created_at: "2026-05-14T06:10:45Z"
---

# Estimating Consensus Epidemic Trajectories via a Constrained Power Fréchet Mean with Functional Registration

**Authors**: Yui Tomo, Shu Tamano, Daisuke Yoneoka
**Date**: 2026-05-11
**Paper ID**: [openalex:2605.10069](https://arxiv.org/abs/2605.10069)

## Summary

This paper addresses the challenge of summarizing multiple stochastic or ensemble-based solutions from SEIR-type compartmental models by computing a constrained power Fréchet mean on a functional space. By incorporating differential equation and population constraints into the optimization process, the method ensures that the resulting consensus trajectory maintains mechanistic interpretability. The approach uses functional registration to align epidemic dynamics, providing a flexible framework for model averaging and ensemble forecasting. The methodology is validated through applications to simulated and empirical epidemiological data related to the early COVID-19 pandemic.

## Key Contributions

- Introduces a constrained power Fréchet mean method for summarizing functional outputs of SEIR compartmental models while preserving mechanistic interpretability.
- Develops a block-optimization algorithm that integrates differential equation and population constraints into the Fréchet mean calculation.
- Demonstrates the utility of the framework for generating consensus trajectories and model averaging in epidemiological contexts using COVID-19 data.

## Open Questions & Future Work

- [[mechanistic-fidelity-vs-scalability-seir-averaging]]

## Key Concepts

- [[constrained-power-frechet-mean]]: A functional data analysis method for computing consensus trajectories of SEIR models using Fréchet means under differential equation and population constraints.

## Archivist Review

The concept of a constrained Fréchet mean for functional trajectory aggregation in compartmental systems is a reusable methodological advancement for model averaging. The open question regarding the trade-off between strict mechanistic adherence and computational feasibility is a significant, ongoing challenge in epidemiological forecasting. I have approved these as they represent a robust formalization of ensemble consensus in constrained systems rather than mere application-specific implementation.

### Approved Concepts
- Constrained Power Fréchet Mean: It provides a formal geometric framework for summarizing functional epidemiological dynamics while maintaining mechanistic consistency.

### Approved Open Questions
- Mechanistic Fidelity vs Scalability: This addresses the fundamental tension between mathematical rigor (fully obeying differential equations) and practical scalability, which is critical for ensemble forecasting in infectious disease modeling.

## Links

- [Abstract](https://arxiv.org/abs/2605.10069)
- [PDF](https://arxiv.org/pdf/2605.10069)

