---
# CSL-compatible fields
title: "ManifoldFormer: Geometric Deep Learning for Neural Dynamics on Riemannian Manifolds"
author:
  - literal: "Yihang Fu"
  - literal: "Lifang He"
  - literal: "Qingyu Chen"
issued:
  date-parts:
    - [2026, 4, 21]
url: "https://arxiv.org/abs/2511.16828"

# Custom fields
paper_id: "2511.16828"
paper_source: "openalex"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "manifoldformer"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-24T05:52:27Z"
created_at: "2026-04-24T05:52:27Z"
---

# ManifoldFormer: Geometric Deep Learning for Neural Dynamics on Riemannian Manifolds

**Authors**: Yihang Fu, Lifang He, Qingyu Chen
**Date**: 2026-04-21
**Paper ID**: [openalex:2511.16828](https://arxiv.org/abs/2511.16828)

## Summary

ManifoldFormer addresses the mismatch between generic Euclidean-based time series models and the intrinsic manifold structure of neural dynamics in EEG signals. The architecture combines RiemannianVAE for manifold embedding, a GeometricTransformer with geodesic-aware attention, and Neural ODEs for manifold-constrained temporal evolution. This approach enables more robust cross-subject generalization and aligns model representations with neurophysiological principles. Empirical results on four datasets demonstrate that incorporating these geometric constraints significantly outperforms traditional Euclidean-based state-of-the-art methods.

## Key Contributions

- Introduces ManifoldFormer, a geometric deep learning framework that explicitly enforces Riemannian manifold constraints on EEG signal representations.
- Proposes a geodesic-aware attention mechanism within a transformer architecture to better capture intrinsic neural dynamics compared to Euclidean-space models.
- Achieves 4.6-4.8% accuracy gains and 6.2-10.2% improvements in Cohen’s Kappa across four public EEG datasets.

## Open Questions & Future Work

- [[optimal-neural-manifold-discovery]]

## Key Concepts

- [[manifoldformer]]: A geometric deep learning framework that leverages Riemannian manifold embedding and geodesic-aware attention for temporal dynamics modeling.

## Archivist Review

The paper introduces a coherent framework for handling non-Euclidean signal data by combining manifold embedding, geodesic-aware attention, and neural ODEs. I approved the framework itself and the open question regarding the automation of manifold discovery, as these reflect the core architectural shift away from Euclidean-only time series modeling. Specific subcomponents like the geodesic-aware attention mechanism were rejected as they are integral parts of the primary framework rather than standalone concepts.

### Approved Concepts
- ManifoldFormer: It is the central framework of the paper, demonstrating a novel integration of geometric deep learning with neural signal analysis to overcome Euclidean limitations.

### Approved Open Questions
- Optimal Neural Manifold Discovery: The geometric structure significantly influences model performance, and transitioning from manual selection to automated/learned manifold discovery is critical for model scalability and robustness.

### Rejected Candidates
- [concept] Geodesic-aware Attention Mechanism (`geodesic-aware-attention-mechanism`) - subcomponent_of_broader_mechanism: This is a specific subcomponent of the ManifoldFormer framework.

## Links

- [Abstract](https://arxiv.org/abs/2511.16828)
- [PDF](https://arxiv.org/pdf/2511.16828)

