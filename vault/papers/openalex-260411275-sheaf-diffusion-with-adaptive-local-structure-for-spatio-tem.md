---
# CSL-compatible fields
title: "Sheaf Diffusion with Adaptive Local Structure for Spatio-Temporal Forecasting"
author:
  - literal: "Abeer Mostafa"
  - literal: "Raneen Younis"
  - literal: "Zahra Ahmadi"
issued:
  date-parts:
    - [2026, 4, 13]
url: "https://arxiv.org/abs/2604.11275"

# Custom fields
paper_id: "2604.11275"
paper_source: "openalex"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "st-sheaf-gnn"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-16T05:46:30Z"
created_at: "2026-04-16T05:46:30Z"
---

# Sheaf Diffusion with Adaptive Local Structure for Spatio-Temporal Forecasting

**Authors**: Abeer Mostafa, Raneen Younis, Zahra Ahmadi
**Date**: 2026-04-13
**Paper ID**: [openalex:2604.11275](https://arxiv.org/abs/2604.11275)

## Summary

This paper proposes ST-Sheaf GNN, a novel framework for spatio-temporal forecasting that replaces global message passing with information flow over locally structured sheaf-theoretic vector spaces. By utilizing dynamic restriction maps that adapt to local spatio-temporal patterns, the model effectively captures heterogeneous interactions while avoiding the oversmoothing typical of deep graph architectures. Experimental results across multiple real-world benchmarks demonstrate that this sheaf-theoretic approach consistently outperforms conventional GNN models.

## Key Contributions

- Introduces ST-Sheaf GNN, a framework that models information flow via dynamic restriction maps within sheaf-theoretic vector spaces.
- Enables expressive modeling of non-intuitive, localized spatio-temporal interactions that are often missed by traditional message-passing GNNs.
- Achieves state-of-the-art forecasting performance by mitigating oversmoothing through the explicit learning of local spatio-temporal topological structures.

## Open Questions & Future Work

- [[sheaf-diffusion-heterogeneous-graphs]]

## Key Concepts

- [[st-sheaf-gnn]]: A graph neural network framework for spatio-temporal forecasting that models information flow via dynamic restriction maps within sheaf-theoretic vector spaces.

## Archivist Review

Approved the central model framework as a reusable concept for sheaf-based topological graph learning and a scoped open question regarding the extension of this theory to heterogeneous graph structures. All other candidates were rejected as either too paper-specific or covered by the selected items. I maintained a high bar for inclusion, ensuring only foundational theoretical contributions that transcend the specific forecasting task were admitted.

### Approved Concepts
- Spatio-temporal sheaf diffusion (ST-Sheaf GNN): It provides a novel topological approach to spatio-temporal modeling that addresses the limitations of standard message passing and oversmoothing.

### Approved Open Questions
- Sheaf Diffusion for Heterogeneous Graphs: Moving beyond simple graph structures is essential for applying sheaf-based topological modeling to more realistic, high-dimensional, and multi-typed real-world data systems.

## Links

- [Abstract](https://arxiv.org/abs/2604.11275)
- [PDF](https://arxiv.org/pdf/2604.11275)

