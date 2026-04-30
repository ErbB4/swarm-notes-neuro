---
# CSL-compatible fields
title: "Fisher Information and Dynamical Sampling I"
author:
  - literal: "Mattia Carrino"
  - literal: "Stefan Hohenegger"
issued:
  date-parts:
    - [2026, 4, 27]
url: "https://arxiv.org/abs/2604.24499"

# Custom fields
paper_id: "2604.24499"
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
processed_at: "2026-04-30T06:04:08Z"
created_at: "2026-04-30T06:04:08Z"
---

# Fisher Information and Dynamical Sampling I

**Authors**: Mattia Carrino, Stefan Hohenegger
**Date**: 2026-04-27
**Paper ID**: [openalex:2604.24499](https://arxiv.org/abs/2604.24499)

## Summary

This paper investigates the information-theoretic limitations of reconstructing dynamical system trajectories from finite time-series measurements. The authors derive the asymptotic bias of Fisher information for these reconstructions, establishing a quantitative link between measurement size and trajectory estimation accuracy. Furthermore, they demonstrate that clustering degrees of freedom effectively mitigates this bias, offering a principled approach to evaluating information loss in reduced-order models of complex dynamical systems.

## Key Contributions

- Derives the large-sample bias of Fisher information for reconstructing dynamical system trajectories from discrete measurements.
- Demonstrates that clustering degrees of freedom systematically reduces reconstruction bias and improves estimation accuracy.
- Provides a quantitative framework for assessing information loss in dimensionality-reduced dynamical models.

## Open Questions & Future Work

- [[optimal-clustering-dynamical-sampling-tradeoff]]

## Archivist Review

The paper provides a rigorous information-theoretic analysis of dynamical system reconstruction bias. I approved the open question regarding the optimal trade-off between clustering-induced bias reduction and information loss, as this is a fundamental bottleneck in high-dimensional time-series modeling. Other candidates were rejected as they were either too specific to the paper's analytical derivation or lacked the generality to serve as vault-level concepts.

### Approved Open Questions
- Optimal Clustering for Dynamical Sampling: Understanding this trade-off is critical for applying information-theoretic analysis to real-world dynamical systems where data is often limited, noisy, and high-dimensional.

### Rejected Candidates
- [concept] Fisher Information Bias for Dynamical Sampling (`fisher-information-bias-estimation`) - not_reusable: This is a theoretical analysis of a specific estimator rather than a general methodological concept suitable for the vault.
- [concept] Information Loss Framework for Dimensionality Reduction (`information-loss-quantification-framework`) - not_novel: This describes the application of Fisher information in a specific context; it is not a distinct architectural or algorithmic framework that would recur in future papers.

## Links

- [Abstract](https://arxiv.org/abs/2604.24499)
- [PDF](https://arxiv.org/pdf/2604.24499)

