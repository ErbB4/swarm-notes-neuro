---
# CSL-compatible fields
title: "Inferring bifurcation diagrams of two distinct chaotic systems by a single machine"
author:
  - literal: "Jianmin Guo"
  - literal: "Yao Du"
  - literal: "Yizhen Yu"
  - literal: "Yong Zou"
  - literal: "Xingang Wang"
issued:
  date-parts:
    - [2026, 4, 29]
url: "https://arxiv.org/abs/2604.26632"

# Custom fields
paper_id: "2604.26632"
paper_source: "openalex"
domain: "time-series"
tags:
  - "time-series"
architectures:
  []
datasets:
  []
concept_slugs:
  - "dual-channel-reservoir-computing"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-02T05:49:54Z"
created_at: "2026-05-02T05:49:54Z"
---

# Inferring bifurcation diagrams of two distinct chaotic systems by a single machine

**Authors**: Jianmin Guo, Yao Du, Yizhen Yu, Yong Zou, Xingang Wang
**Date**: 2026-04-29
**Paper ID**: [openalex:2604.26632](https://arxiv.org/abs/2604.26632)

## Summary

This paper presents a dual-channel reservoir computing architecture capable of inferring the bifurcation diagrams of two distinct chaotic systems simultaneously. By integrating system-label and parameter-control channels into a standard reservoir, the machine learns to map disparate dynamics to a unified latent space. The approach is validated on both simulated Lorenz/Rössler systems and physical circuit experiments, demonstrating superior ability to reproduce long-term statistical properties from partial data. Functional-network analysis reveals that the machine successfully encodes separate target systems into distinct dynamical patterns within the reservoir.

## Key Contributions

- Introduces a dual-channel reservoir computing scheme that employs system-label and parameter-control channels to generalize across multiple chaotic systems.
- Demonstrates the ability to reconstruct long-term bifurcation diagrams of distinct systems (Lorenz, Rössler) using only sparse time-series observations.
- Validates the proposed scheme through both numerical simulations and hardware implementation using Chua and Rössler circuits.

## Open Questions & Future Work

- [[mfrc-scalability-limits]]
- [[mfrc-dimensionality-extensibility]]

## Key Concepts

- [[dual-channel-reservoir-computing]]: A reservoir computing architecture augmented with system-label and parameter-control channels to learn and infer bifurcation diagrams of multiple distinct chaotic systems.

## Archivist Review

I approved the core architectural concept of dual-channel reservoir computing as it provides a reusable mechanism for multifunctional dynamics modeling. I also approved two research questions regarding scaling and dimensional heterogeneity, which represent significant theoretical and practical bottlenecks for this class of models. No datasets were approved as the experimental data used are standard benchmarks for chaotic system literature and not novel or central enough for independent vault status.

### Approved Concepts
- Dual-channel reservoir computing: Enables a single reservoir model to multitask across different chaotic dynamical systems.

### Approved Open Questions
- Scalability of multifunctional reservoir computing: Understanding scalability limits is critical for transitioning MFRC from laboratory demonstrations to practical, real-world applications involving complex systems with many potential dynamical states.
- Extending MFRC to heterogeneous dimensions: Real-world systems rarely exhibit uniform dimensionality; therefore, enabling cross-dimensional inference is essential for the generalization of MFRC to heterogeneous dynamical environments.

## Links

- [Abstract](https://arxiv.org/abs/2604.26632)
- [PDF](https://arxiv.org/pdf/2604.26632)

