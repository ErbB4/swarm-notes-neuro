---
# CSL-compatible fields
title: "Anomaly detection in smart power grids with graph-regularized MS-SVDD: a multimodal subspace learning approach"
author:
  - literal: "Thomas Debelle"
  - literal: "Fahad Sohrab"
  - literal: "Pekka Abrahamsson"
  - literal: "Moncef Gabbouj"
issued:
  date-parts:
    - [2026, 4, 24]
url: "https://arxiv.org/abs/2502.15793"

# Custom fields
paper_id: "2502.15793"
paper_source: "openalex"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "graph-regularized-multimodal-subspace-learning"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-27T06:02:21Z"
created_at: "2026-04-27T06:02:21Z"
---

# Anomaly detection in smart power grids with graph-regularized MS-SVDD: a multimodal subspace learning approach

**Authors**: Thomas Debelle, Fahad Sohrab, Pekka Abrahamsson, Moncef Gabbouj
**Date**: 2026-04-24
**Paper ID**: [openalex:2502.15793](https://arxiv.org/abs/2502.15793)

## Summary

This paper introduces a generalized Multimodal Subspace Support Vector Data Description (MS-SVDD) framework designed for anomaly detection in complex, heterogeneous smart grid data. By incorporating Laplacian graph-embedded regularization, the model maps multiple sensor modalities into a shared low-dimensional subspace while maintaining modality-specific relational structures. Empirical evaluation on a multi-modality smart grid dataset shows that this structural approach significantly enhances robustness over traditional one-class classification methods. The work provides a systematic methodology for embedding relational graph priors into subspace-based anomaly detection models.

## Key Contributions

- Proposed a Generalized Multimodal Subspace Support Vector Data Description (MS-SVDD) model for anomaly detection in smart grids.
- Integrated Laplacian-based graph regularization into MS-SVDD to explicitly preserve multimodal structural dependencies.
- Demonstrated improved event detection robustness on a three-modality smart grid dataset compared to conventional subspace learning approaches.

## Open Questions & Future Work

- [[real-time-deployment-scalability-infrastructure-monitoring]]

## Key Concepts

- [[graph-regularized-multimodal-subspace-learning]]: A framework for anomaly detection that embeds modality-specific structural priors via Laplacian regularizers into a shared low-dimensional subspace.

## Archivist Review

The proposed model represents a specific, reusable approach to multimodal anomaly detection by integrating graph priors into subspace learning. I have approved this as a concept. I have also approved the open question regarding real-time deployment scalability after renaming it to be more specific to critical infrastructure. Other potential candidates were rejected for being either too generic, local to the specific implementation, or redundant.

### Approved Concepts
- Graph-Regularized Multimodal Subspace Learning: This represents a novel, reusable approach to integrating graph priors into subspace-based anomaly detection, which is broadly applicable to heterogeneous time-series data.

### Approved Open Questions
- Real-time infrastructure deployment scalability: Crucial for transitioning from high-dimensional latent modeling to reliable, time-sensitive operation in real-world critical infrastructure.

### Rejected Candidates
- [open_question] Real-time deployment and scalability (`real-time-deployment-scalability`) - duplicate_existing: The title is too generic and conflicts with existing patterns in the vault.

## Links

- [Abstract](https://arxiv.org/abs/2502.15793)
- [PDF](https://arxiv.org/pdf/2502.15793)

