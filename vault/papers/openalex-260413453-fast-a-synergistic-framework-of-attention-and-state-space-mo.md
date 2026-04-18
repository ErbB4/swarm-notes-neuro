---
# CSL-compatible fields
title: "FAST: A Synergistic Framework of Attention and State-space Models for Spatiotemporal Traffic Prediction"
author:
  - literal: "Xinjin Li"
  - literal: "Jinghan Cao"
  - literal: "Mengyue Wang"
  - literal: "Yue Wu"
  - literal: "Longxiang Yan"
  - literal: "Yeyang Zhou"
  - literal: "Ziqi Sha"
  - literal: "Yu Ma"
issued:
  date-parts:
    - [2026, 4, 15]
url: "https://arxiv.org/abs/2604.13453"

# Custom fields
paper_id: "2604.13453"
paper_source: "openalex"
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
skill: "TimeSeriesSkill"
processed_at: "2026-04-18T05:35:06Z"
created_at: "2026-04-18T05:35:06Z"
---

# FAST: A Synergistic Framework of Attention and State-space Models for Spatiotemporal Traffic Prediction

**Authors**: Xinjin Li, Jinghan Cao, Mengyue Wang, Yue Wu, Longxiang Yan, Yeyang Zhou, Ziqi Sha, Yu Ma
**Date**: 2026-04-15
**Paper ID**: [openalex:2604.13453](https://arxiv.org/abs/2604.13453)

## Summary

FAST is a unified spatiotemporal framework designed for scalable traffic forecasting by combining temporal attention with selective state-space modeling. The model utilizes a Temporal-Spatial-Temporal architecture to efficiently capture both complex temporal patterns and long-range spatial dependencies across large sensor networks. By integrating a Mamba-based spatial module, FAST maintains linear complexity while achieving superior predictive accuracy compared to existing Transformer and GNN-based baselines across standard traffic benchmarks.

## Key Contributions

- Introduces FAST, a Temporal-Spatial-Temporal architecture that synthesizes attention mechanisms with state-space models for scalable traffic forecasting.
- Employs a Mamba-based spatial module to model inter-sensor dependencies with linear complexity, overcoming efficiency limitations of traditional Transformer architectures.
- Achieves state-of-the-art performance on PeMS04, PeMS07, and PeMS08 datasets, outperforming existing Transformer, GNN, and Mamba-based approaches.

## Open Questions & Future Work

- [[adaptive-spatiotemporal-forecasting-scalability]]

## Archivist Review

The paper introduces a hybrid architecture combining attention and state-space models. While effective, the individual components and the specific architecture are variations of existing paradigms. I have consolidated the suggested open question into a more precise formulation regarding adaptive spatial modeling and scale, as the original was too broad. Standard benchmarks like PeMS were rejected as they are routine in this domain.

### Approved Open Questions
- Adaptive Spatiotemporal Forecasting Scalability: This addresses the fundamental transition from controlled benchmark forecasting to reliable deployment in complex, evolving urban infrastructure.

### Rejected Candidates
- [dataset] PeMS datasets (`pems04-pems07-pems08`) - not_novel: These are standard, routine traffic forecasting benchmarks rather than unique or novel datasets.
- [concept] Temporal-Spatial-Temporal architecture (`temporal-spatial-temporal-architecture`) - subcomponent_of_broader_mechanism: This is a specific architectural composition (sandwich structure) for this paper that is not sufficiently generalizable as a standalone concept.
- [concept] Mamba-based spatial module (`mamba-based-spatial-module`) - subcomponent_of_broader_mechanism: This is a straightforward application of Mamba to a specific domain subcomponent rather than a novel conceptual contribution.

## Links

- [Abstract](https://arxiv.org/abs/2604.13453)
- [PDF](https://arxiv.org/pdf/2604.13453)

