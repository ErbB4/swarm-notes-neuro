---
# CSL-compatible fields
title: "Reduced-order modeling of a viscoelastic turbulent jet with hybrid machine learning models"
author:
  - literal: "Christian Amor"
  - literal: "Adrián Corrochano"
  - literal: "Marco Edoardo Rosti"
  - literal: "Soledad Le Clainche"
issued:
  date-parts:
    - [2026, 4, 29]
url: "https://arxiv.org/abs/2604.26240"

# Custom fields
paper_id: "2604.26240"
paper_source: "openalex"
domain: "fluid-dynamics"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-02T05:50:22Z"
created_at: "2026-05-02T05:50:22Z"
---

# Reduced-order modeling of a viscoelastic turbulent jet with hybrid machine learning models

**Authors**: Christian Amor, Adrián Corrochano, Marco Edoardo Rosti, Soledad Le Clainche
**Date**: 2026-04-29
**Paper ID**: [openalex:2604.26240](https://arxiv.org/abs/2604.26240)

## Summary

This paper presents a hybrid reduced-order modeling approach to address the high computational cost of simulating viscoelastic turbulent jets. By combining proper orthogonal decomposition (POD) with neural network predictors for mode coefficients, the model produces a compact, accelerated representation of complex viscoelastic fluid dynamics. Experimental results indicate that this framework effectively reconstructs long-term statistics, with deep neural architectures utilizing skip connections providing the best performance for multiscale dynamics.

## Key Contributions

- Proposes a hybrid reduced-order model (ROM) integrating proper orthogonal decomposition (POD) and neural networks for efficient viscoelastic turbulent jet simulation.
- Demonstrates that neural network-based mode coefficient prediction successfully captures the long-term statistical behavior of viscoelastic turbulent flows.
- Establishes that while smaller models capture large-scale dynamics effectively, deeper models with skip connections are essential for accurately forecasting small-scale turbulent structures.

## Open Questions & Future Work

- [[multi-scale-turbulent-dynamics-rom-bottleneck]]

## Archivist Review

I approved the open question regarding the multi-scale turbulent dynamics bottleneck, as it captures a fundamental research challenge in fluid dynamics ROMs that persists despite the hybrid approach. The proposed hybrid methodology itself was rejected as a concept because it represents a domain-specific application of existing, well-understood hybrid ROM architectures.

### Approved Open Questions
- Multi-scale turbulent dynamics bottleneck: Understanding how to effectively represent multi-scale turbulent dynamics in ROMs is essential for balancing predictive accuracy, model interpretability, and computational cost, especially for high-Weissenberg number viscoelastic flows where simulation is prohibitively expensive.

### Rejected Candidates
- [concept] Hybrid reduced-order modeling for viscoelastic jets (`hybrid-reduced-order-modeling-viscoelastic-jet`) - not_novel: The proposed method is a domain-specific application of well-established hybrid ROM (POD + NN) techniques and does not constitute a sufficiently novel, reusable architectural concept.

## Links

- [Abstract](https://arxiv.org/abs/2604.26240)
- [PDF](https://arxiv.org/pdf/2604.26240)

