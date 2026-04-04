---
# CSL-compatible fields
title: "Selective State-Space Models for Koopman-based Data-driven Distribution System State Estimation"
author:
  - literal: "Bader Alabdulrazzaq"
  - literal: "Bri-Mathias Hodge"
issued:
  date-parts:
    - [2026, 4, 2]
url: "https://arxiv.org/abs/2604.02273"

# Custom fields
paper_id: "2604.02273"
paper_source: "arxiv"
domain: "time-series"
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
skill: "GeneralMLSkill"
processed_at: "2026-04-04T20:08:19Z"
created_at: "2026-04-04T20:08:19Z"
---

# Selective State-Space Models for Koopman-based Data-driven Distribution System State Estimation

**Authors**: Bader Alabdulrazzaq, Bri-Mathias Hodge
**Date**: 2026-04-02
**Paper ID**: [arxiv:2604.02273](https://arxiv.org/abs/2604.02273)

## Summary

This paper introduces MambaDSSE, a novel data-driven framework designed to address the scalability and generalization challenges in Distribution System State Estimation (DSSE). By integrating Koopman-theoretic probabilistic filtering with selective state-space models, the approach effectively learns to infer time-varying grid behaviors from observation data. The model excels in capturing long-range dependencies, demonstrating superior robustness to irregular sampling and high DER penetration compared to traditional machine learning baselines.

## Key Contributions

- Introduces MambaDSSE, a novel model-free framework for distribution system state estimation combining Koopman-theoretic probabilistic filtering and selective state-space models (SSMs).
- Demonstrates that the Mamba-based SSM architecture effectively captures long-range dependencies in time-varying grid data, improving estimation performance.
- Provides empirical evidence that the framework outperforms existing machine learning baselines in scalability, robustness to data sampling rate irregularities, and resilience to varying DER penetration levels.

## Limitations

The paper focuses on model-free data-driven performance; explicit comparisons to high-fidelity physics-based models or deployment challenges in real-time operational environments remain as future work.

## Archivist Review

I have rejected MambaDSSE because it represents a specific application of the broader Mamba/SSM architecture to a power systems problem, rather than a novel foundational concept. The vault should prioritize generalizable architectural patterns and mechanisms over task-specific system instantiations. No other concepts or open questions met the bar for inclusion as standalone, long-lived entries.

### Rejected Candidates
- [concept] MambaDSSE (`mambadsse`) - subcomponent_of_broader_mechanism: MambaDSSE is a domain-specific application of Mamba (selective SSMs) rather than a general methodological contribution; it is effectively a specific instance of applying SSMs to a control task.

## Links

- [Abstract](https://arxiv.org/abs/2604.02273)
- [PDF](https://arxiv.org/pdf/2604.02273)

