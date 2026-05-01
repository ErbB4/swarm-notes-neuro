---
# CSL-compatible fields
title: "Deflation-Free Optimal Scoring"
author:
  - literal: "Sharmin Afroz"
  - literal: "Brendan Ames"
issued:
  date-parts:
    - [2026, 4, 28]
url: "https://arxiv.org/abs/2604.25664"

# Custom fields
paper_id: "2604.25664"
paper_source: "openalex"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "deflation-free-sparse-optimal-scoring"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-01T06:04:49Z"
created_at: "2026-05-01T06:04:49Z"
---

# Deflation-Free Optimal Scoring

**Authors**: Sharmin Afroz, Brendan Ames
**Date**: 2026-04-28
**Paper ID**: [openalex:2604.25664](https://arxiv.org/abs/2604.25664)

## Summary

Sparse Optimal Scoring (SOS) methods for high-dimensional feature selection typically rely on sequential deflation, which often leads to suboptimal results and error accumulation. This paper proposes Deflation-Free Sparse Optimal Scoring (DFSOS), which reformulates the problem to estimate all discriminant vectors simultaneously under a global orthogonality constraint. The approach employs Bregman iteration to decouple the optimization into tractable subproblems for scoring and discriminant vectors. Experimental results on synthetic and time series datasets confirm that DFSOS achieves more robust classification performance compared to traditional deflationary approaches.

## Key Contributions

- Introduces Deflation-Free Sparse Optimal Scoring (DFSOS) to eliminate error propagation associated with sequential discriminant vector computation.
- Utilizes a novel combination of Bregman iteration and global orthogonality-constrained optimization to solve sparse discriminant analysis problems.
- Provides convergence guarantees to stationary points of the augmented Lagrangian under mild conditions.
- Demonstrates superior or comparable classification accuracy against deflation-based benchmarks on synthetic and real-world time series datasets.

## Open Questions & Future Work

- [[dfsos-convergence-rate-theoretical-characterization]]

## Key Concepts

- [[deflation-free-sparse-optimal-scoring]]: A sparse discriminant analysis framework that estimates all discriminant vectors simultaneously using an explicit global orthogonality constraint.

## Archivist Review

The paper introduces a significant methodological shift for sparse discriminant analysis by moving from sequential deflation to simultaneous estimation with global orthogonality constraints. I approved the DFSOS concept as it addresses a well-known structural limitation in high-dimensional feature selection. The open question regarding convergence rates was refined to emphasize the theoretical gap, while the empirical benchmarking request was rejected as routine experimentation.

### Approved Concepts
- Deflation-Free Sparse Optimal Scoring: It provides a solution to the error propagation issue inherent in sequential, deflation-based discriminant analysis methods.

### Approved Open Questions
- DFSOS convergence rate characterization: Characterizing the convergence rate is essential for comparing DFSOS efficiency with other manifold optimization methods and for setting practical stopping criteria in large-scale applications.

### Rejected Candidates
- [open_question] Efficiency of manifold optimization (`manifold-optimization-efficiency`) - other: The proposal for empirical benchmarking of existing manifold optimization algorithms is a routine future work item rather than a fundamental theoretical bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2604.25664)
- [PDF](https://arxiv.org/pdf/2604.25664)

