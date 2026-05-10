---
# CSL-compatible fields
title: "Consistent Geometric Deep Learning via Hilbert Bundles and Cellular Sheaves"
author:
  - literal: "Kartik Tandon"
  - literal: "Julian Gould"
  - literal: "Tanishq Bhatia"
  - literal: "Francesca Dominici"
  - literal: "Alejandro Ribeiro"
  - literal: "Claudio Battiloro"
issued:
  date-parts:
    - [2026, 5, 7]
url: "https://arxiv.org/abs/2605.06395"

# Custom fields
paper_id: "2605.06395"
paper_source: "openalex"
domain: "geometric-learning"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "hilbnets"
  - "hilbert-cellular-sheaf"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-10T06:05:59Z"
created_at: "2026-05-10T06:05:59Z"
---

# Consistent Geometric Deep Learning via Hilbert Bundles and Cellular Sheaves

**Authors**: Kartik Tandon, Julian Gould, Tanishq Bhatia, Francesca Dominici, Alejandro Ribeiro, Claudio Battiloro
**Date**: 2026-05-07
**Paper ID**: [openalex:2605.06395](https://arxiv.org/abs/2605.06395)

## Summary

This paper introduces HilbNets, a geometric deep learning framework designed to process infinite-dimensional signals supported on manifolds. By leveraging Hilbert bundles and connection Laplacians, the authors extend convolutional operators to signals where each point resides in a unique Hilbert space. They provide theoretical guarantees for discretization, showing that their sheaf-based approach converges to continuous architectures and offers cross-sampling transferability.

## Key Contributions

- Introduces HilbNets, a convolutional learning framework for infinite-dimensional signals on manifolds using connection Laplacians.
- Proves that sampling a manifold with a Hilbert bundle induces a Hilbert Cellular Sheaf whose sheaf Laplacian converges to the connection Laplacian.
- Demonstrates that discretized HilbNets are consistent and transferable across different samplings of the same bundle.

## Open Questions & Future Work

- [[geometric-learning-infinite-dim-signals]]

## Key Concepts

- [[hilbnets]]: A convolutional neural network framework designed for infinite-dimensional signals supported on manifolds using Hilbert bundle connection Laplacians.
- [[hilbert-cellular-sheaf]]: A graph-based discretization framework for Hilbert bundles that preserves geometric consistency via sheaf Laplacians.

## Archivist Review

I approved the two core architectural concepts (HilbNets and Hilbert Cellular Sheaf) as they establish a foundational mechanism for geometric deep learning on infinite-dimensional fiber spaces. The open question was approved for articulating the specific theoretical bottleneck of extending graph-to-manifold convergence results to infinite-dimensional Hilbert bundles. No datasets were approved as none were central to the methodology or sufficiently distinct.

### Approved Concepts
- HilbNets: Represents the primary architectural innovation for processing infinite-dimensional signals via connection Laplacians.
- Hilbert Cellular Sheaf: Formally bridges continuous manifold-based signal processing with discrete graph-based implementations.

### Approved Open Questions
- Geometric Learning for Infinite-Dimensional Signals: Addressing this gap is necessary to provide theoretical guarantees, such as consistency and transferability, for deep learning models operating on complex data structures like time series and measure-valued representations.

## Links

- [Abstract](https://arxiv.org/abs/2605.06395)
- [PDF](https://arxiv.org/pdf/2605.06395)

