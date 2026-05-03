---
# CSL-compatible fields
title: "Reorganizing Quantum Measurement Records Improves Time-Series Prediction"
author:
  - literal: "Markus Baumann"
  - literal: "Maximilian Zorn"
  - literal: "Thomas Gabor"
  - literal: "Claudia Linnhoff-Popien"
  - literal: "Jonas Stein"
issued:
  date-parts:
    - [2026, 4, 30]
url: "https://arxiv.org/abs/2604.28160"

# Custom fields
paper_id: "2604.28160"
paper_source: "openalex"
domain: "time-series"
tags:
  - "time-series"
  - "quantum-computing"
architectures:
  []
datasets:
  []
concept_slugs:
  - "split-ensemble-training"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-03T06:02:53Z"
created_at: "2026-05-03T06:02:53Z"
---

# Reorganizing Quantum Measurement Records Improves Time-Series Prediction

**Authors**: Markus Baumann, Maximilian Zorn, Thomas Gabor, Claudia Linnhoff-Popien, Jonas Stein
**Date**: 2026-04-30
**Paper ID**: [openalex:2604.28160](https://arxiv.org/abs/2604.28160)

## Summary

This paper addresses the data-efficiency bottleneck in quantum reservoir computing caused by averaging measurement shots into single expectation values. The authors introduce 'split-ensemble training,' which partitions quantum measurement shots into smaller groups, generating multiple feature vectors per time step instead of one. This approach effectively increases the training dataset size without requiring additional circuit executions. Experimental results on forecasting tasks demonstrate improved predictive performance, particularly on real quantum hardware where finite-shot noise and sampling limitations are most pronounced.

## Key Contributions

- Introduces split-ensemble training to increase the effective training sample size in quantum reservoir computing without increasing the measurement budget.
- Demonstrates that partial averaging of quantum measurement shots improves predictive performance on time-series benchmarks where full expectation-value averaging suffers from data sparsity.
- Provides empirical evidence of performance gains across both simulated and real quantum hardware scenarios, particularly highlighting robustness to hardware-induced noise.

## Open Questions & Future Work

- [[adaptive-shot-organization-strategy]]

## Key Concepts

- [[split-ensemble-training]]: A data reorganization strategy for quantum reservoir computing that partitions measurement shots into multiple feature vectors to increase training sample size.

## Archivist Review

I have approved the core methodological concept of 'Split-Ensemble Training' as a reusable technique for quantum-classical hybrid learning. The associated open question regarding the adaptive selection of hyperparameters (group size) is also approved as it addresses a key bottleneck for the practical deployment of this technique. No datasets were approved as none were specifically named or featured as novel contributions.

### Approved Concepts
- Split-Ensemble Training: It is the core methodological contribution, enabling better training data utilization from fixed quantum measurement budgets.

### Approved Open Questions
- Adaptive Shot-Organization Selection: This is a critical unresolved bottleneck in the practical deployment of quantum reservoir computing, as the current reliance on exhaustive empirical search for the hyperparameter 'group size' is computationally costly and prevents automated, efficient tuning in real-world applications.

## Links

- [Abstract](https://arxiv.org/abs/2604.28160)
- [PDF](https://arxiv.org/pdf/2604.28160)

