---
# CSL-compatible fields
title: "Toward Scalable SDN for LEO Mega-Constellations: A Graph Learning Approach"
author:
  - literal: "Sivaram Krishnan"
  - literal: "Bassel Al Homssi"
  - literal: "Zhouyou Gu"
  - literal: "Jihong Park"
  - literal: "Sung-Min Oh"
  - literal: "Jinho Choi"
issued:
  date-parts:
    - [2026, 4, 30]
url: "https://arxiv.org/abs/2604.27478"

# Custom fields
paper_id: "2604.27478"
paper_source: "openalex"
domain: "time-series"
tags:
  - "time-series-forecasting"
  - "graph-neural-networks"
  - "sdn"
  - "satellite-networks"
architectures:
  []
datasets:
  []
concept_slugs:
  - "graph-koopman-autoencoder"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-03T06:03:14Z"
created_at: "2026-05-03T06:03:14Z"
---

# Toward Scalable SDN for LEO Mega-Constellations: A Graph Learning Approach

**Authors**: Sivaram Krishnan, Bassel Al Homssi, Zhouyou Gu, Jihong Park, Sung-Min Oh, Jinho Choi
**Date**: 2026-04-30
**Paper ID**: [openalex:2604.27478](https://arxiv.org/abs/2604.27478)

## Summary

This paper addresses the scalability challenges of software-defined networking (SDN) in large-scale low Earth orbit (LEO) satellite constellations. The authors introduce a hierarchical architecture that utilizes Graph Koopman Autoencoders (GKAE) to model and forecast complex, nonlinear spatio-temporal network dynamics within simplified linear subspaces. By aggregating these shell-level predictions at a central controller, the framework achieves efficient, coordinated network control. Experimental results on Starlink demonstrate superior spatial compression and temporal forecasting performance with a reduced model footprint compared to existing baselines.

## Key Contributions

- Proposes a hierarchical SDN framework for LEO mega-constellations to mitigate network management bottlenecks.
- Introduces the Graph Koopman Autoencoder (GKAE) to model constellation spatio-temporal dynamics in a reduced linear subspace.
- Achieves 42.8% improvement in spatial compression and 10.81% improvement in temporal forecasting accuracy on Starlink constellation simulations.

## Open Questions & Future Work

- [[sdn-controller-placement-tradeoffs]]

## Key Concepts

- [[graph-koopman-autoencoder]]: A GNN-based autoencoder that utilizes Koopman theory to project non-linear spatio-temporal dynamics into a linear subspace for scalable forecasting.

## Archivist Review

I approved the Graph Koopman Autoencoder as it represents a sophisticated, reusable approach to dimensionality reduction in temporal graph signals. I also approved the SDN controller placement question, as it highlights a concrete trade-off between control hierarchy and physical hardware limitations. Other candidates were rejected due to overly broad scope or lack of specific research focus.

### Approved Concepts
- Graph Koopman Autoencoder: It provides a novel, reusable mechanism for compressing non-linear, high-dimensional spatio-temporal graph dynamics into a linear subspace for efficient forecasting.

### Approved Open Questions
- SDN Controller Placement Trade-offs: This is a critical architectural bottleneck for scaling SDN to massive, highly dynamic constellations, as it directly impacts control latency and network robustness.

### Rejected Candidates
- [open_question] Heterogeneous Graphs in 6G (`heterogeneous-graphs-6g-ntn`) - low_impact: The proposal is a broad vision for 6G integration rather than a specific, well-defined research bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2604.27478)
- [PDF](https://arxiv.org/pdf/2604.27478)

