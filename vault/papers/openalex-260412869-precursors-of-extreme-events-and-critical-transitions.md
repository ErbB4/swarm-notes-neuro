---
# CSL-compatible fields
title: "Precursors of extreme events and critical transitions"
author:
  - literal: "Riccardo Consonni"
  - literal: "Luca Magri"
issued:
  date-parts:
    - [2026, 4, 14]
url: "https://arxiv.org/abs/2604.12869"

# Custom fields
paper_id: "2604.12869"
paper_source: "openalex"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "fast-slow-clv-cascade"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-17T05:46:49Z"
created_at: "2026-04-17T05:46:49Z"
---

# Precursors of extreme events and critical transitions

**Authors**: Riccardo Consonni, Luca Magri
**Date**: 2026-04-14
**Paper ID**: [openalex:2604.12869](https://arxiv.org/abs/2604.12869)

## Summary

This paper introduces a dynamical systems theory to identify and predict extreme events and critical transitions in fast-slow nonlinear systems. By analyzing the evolution of fast and slow covariant Lyapunov vectors (CLVs), the authors describe a three-stage cascade: a slow regime, a transition regime, and a critical regime characterized by spectral gaps and broken subspace transversality. Based on this cascade, they propose two mathematically grounded precursors that achieve perfect predictive performance in numerical simulations. This approach provides a rigorous foundation for time-forecasting critical events in complex nonlinear systems.

## Key Contributions

- Identified a theoretical cascade of dynamical system properties involving covariant Lyapunov vectors (CLVs) that consistently precedes extreme events and critical transitions.
- Proposed two novel, theoretically grounded precursors for extreme event prediction derived from the identified dynamical cascade.
- Demonstrated 100% precision and recall in predicting extreme events across numerical tests in low- and higher-dimensional nonlinear systems.

## Open Questions & Future Work

- [[high-dimensional-multiscale-scaling]]

## Key Concepts

- [[fast-slow-clv-cascade]]: A sequence of changes in covariant Lyapunov vector stability and transversality in fast-slow systems that serves as a precursor to extreme events and critical transitions.

## Archivist Review

I approved the concept of the fast-slow CLV cascade as it introduces a rigorous dynamical systems framework for event forecasting that is distinct from standard statistical or deep learning approaches. I approved the open question regarding scaling to higher-dimensional systems because the transition from low-dimensional numerical testing to complex, high-degree-of-freedom systems is a primary bottleneck for this theoretical approach. The review followed strict scarcity guidelines, focusing on core theoretical contributions rather than implementation details.

### Approved Concepts
- Fast-slow covariant Lyapunov vector cascade: Provides a novel, theoretically grounded dynamical systems mechanism for identifying precursors to extreme events by analyzing the alignment and stability of covariant Lyapunov vectors.

### Approved Open Questions
- Scaling to higher-dimensional systems: Confirming the applicability in high-dimensional multiscale systems is critical for practical utility and ensuring that the identified geometric mechanisms hold when the number of degrees of freedom significantly increases.

## Links

- [Abstract](https://arxiv.org/abs/2604.12869)
- [PDF](https://arxiv.org/pdf/2604.12869)

