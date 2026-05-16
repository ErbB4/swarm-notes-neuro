---
# CSL-compatible fields
title: "Quantifying information flow along a stochastic trajectory"
author:
  - literal: "Yongjae Oh"
  - literal: "Euijoon Kwon"
  - literal: "Yongjoo Baek"
issued:
  date-parts:
    - [2026, 5, 13]
url: "https://arxiv.org/abs/2605.13509"

# Custom fields
paper_id: "2605.13509"
paper_source: "openalex"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "stochastic-information-flow"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-16T06:02:26Z"
created_at: "2026-05-16T06:02:26Z"
---

# Quantifying information flow along a stochastic trajectory

**Authors**: Yongjae Oh, Euijoon Kwon, Yongjoo Baek
**Date**: 2026-05-13
**Paper ID**: [openalex:2605.13509](https://arxiv.org/abs/2605.13509)

## Summary

This paper addresses the computational intractability of Stochastic Information Flow (SIF) by introducing a scalable deep-learning estimation framework suitable for general time-series data. Unlike traditional ensemble-averaged metrics, SIF operates at the individual trajectory level, enabling more granular analysis of directed information dynamics. The authors demonstrate the efficacy of their approach by applying it to both simulated dynamical systems and complex biological movement trajectories, establishing it as a robust tool for detecting cooperative behaviors.

## Key Contributions

- Develops a scalable deep-learning-based estimation framework for Stochastic Information Flow (SIF) from time-series data.
- Demonstrates empirical utility of SIF in identifying cooperative structures in Kuramoto oscillators and biological motility data.
- Provides an empirical validation of SIF on an exactly solvable two-particle model to establish ground-truth reliability.

## Open Questions & Future Work

- [[sif-transient-states]]

## Key Concepts

- [[stochastic-information-flow]]: A trajectory-level measure of directed information transfer that captures non-equilibrium dynamical dependencies.

## Archivist Review

I have approved the core concept of Stochastic Information Flow (SIF) as it represents a shift from ensemble-based metrics to trajectory-level modeling, which is highly relevant to modern time-series analysis. I also approved the open question regarding SIF in transient states, as it identifies a critical boundary condition for the practical application of this estimator in non-equilibrium settings. No other candidates were provided, so the selection is intentionally focused and high-impact.

### Approved Concepts
- Stochastic Information Flow (SIF): It is the core theoretical construct the paper aims to operationalize through deep learning for trajectory-level analysis.

### Approved Open Questions
- Estimating SIF in transient states: Many real-world systems, such as biological signaling pathways or responding neural networks, operate in transient, non-equilibrium regimes. Extending the SIF estimator to these states would enable more accurate analysis of information dynamics in time-varying environments.

## Links

- [Abstract](https://arxiv.org/abs/2605.13509)
- [PDF](https://arxiv.org/pdf/2605.13509)

