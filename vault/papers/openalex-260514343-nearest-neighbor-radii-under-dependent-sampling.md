---
# CSL-compatible fields
title: "Nearest-Neighbor Radii under Dependent Sampling"
author:
  - literal: "Yuanyuan Gao"
  - literal: "Yilong Hou"
  - literal: "Zhexiao Lin"
issued:
  date-parts:
    - [2026, 5, 14]
url: "https://arxiv.org/abs/2605.14343"

# Custom fields
paper_id: "2605.14343"
paper_source: "openalex"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "nearest-neighbor-radii-dependent-sampling"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-17T06:08:26Z"
created_at: "2026-05-17T06:08:26Z"
---

# Nearest-Neighbor Radii under Dependent Sampling

**Authors**: Yuanyuan Gao, Yilong Hou, Zhexiao Lin
**Date**: 2026-05-14
**Paper ID**: [openalex:2605.14343](https://arxiv.org/abs/2605.14343)

## Summary

This paper provides a theoretical foundation for the behavior of nearest-neighbor radii when observations are sampled dependently rather than independently. The authors derive convergence results and non-asymptotic moment bounds that account for mixing properties of the underlying process. Crucially, these bounds are shown to depend on local intrinsic dimensionality, validating the robustness of nearest-neighbor methods in high-dimensional settings under dependent sampling such as time series.

## Key Contributions

- Establishes distribution-free almost sure convergence of nearest-neighbor radii under polynomial mixing conditions.
- Derives sharp non-asymptotic moment bounds for nearest-neighbor radii under geometric mixing, sensitive to local intrinsic dimension rather than ambient dimension.
- Demonstrates that nearest-neighbor geometry remains statistically informative for high-dimensional data on lower-dimensional manifolds under dependent sampling regimes.

## Open Questions & Future Work

- [[uniform-convergence-of-nn-radii-dependent-sampling]]

## Key Concepts

- [[nearest-neighbor-radii-dependent-sampling]]: A theoretical framework describing the behavior of nearest-neighbor neighborhoods under strong mixing dependence conditions.

## Archivist Review

I approved the fundamental framework of NN radii under dependent sampling as a concept because it provides a necessary theoretical bridge for distance-based methods in time series. The open question regarding uniform convergence was also approved as it represents a significant technical hurdle for obtaining global performance guarantees in these settings. No datasets were approved as none were central to the paper's contribution.

### Approved Concepts
- Nearest-Neighbor Radii under Dependent Sampling: It provides a theoretical justification for applying distance-based learning techniques to time series, where temporal dependence typically violates i.i.d. assumptions.

### Approved Open Questions
- Uniform Convergence of NN Radii: Global performance guarantees for nearest-neighbor-based learning procedures such as regression, classification, and graph construction fundamentally rely on uniform control of the local neighborhood geometry.

## Links

- [Abstract](https://arxiv.org/abs/2605.14343)
- [PDF](https://arxiv.org/pdf/2605.14343)

