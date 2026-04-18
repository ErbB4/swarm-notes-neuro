---
# CSL-compatible fields
title: "Minimax Optimality and Spectral Routing for Majority-Vote Ensembles under Markov Dependence"
author:
  - literal: "Ibne Farabi Shihab"
  - literal: "Sanjeda Akter"
  - literal: "Anuj Sharma"
issued:
  date-parts:
    - [2026, 4, 15]
url: "https://arxiv.org/abs/2604.13414"

# Custom fields
paper_id: "2604.13414"
paper_source: "openalex"
domain: "time-series"
tags:
  - "time-series"
  - "ensemble-learning"
  - "markov-dependence"
  - "minimax-optimality"
architectures:
  []
datasets:
  []
concept_slugs:
  - "adaptive-spectral-routing"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-18T05:35:00Z"
created_at: "2026-04-18T05:35:00Z"
---

# Minimax Optimality and Spectral Routing for Majority-Vote Ensembles under Markov Dependence

**Authors**: Ibne Farabi Shihab, Sanjeda Akter, Anuj Sharma
**Date**: 2026-04-15
**Paper ID**: [openalex:2604.13414](https://arxiv.org/abs/2604.13414)

## Summary

This paper investigates the performance degradation of majority-vote ensembles when training data exhibits Markov dependence. The authors derive minimax information-theoretic lower bounds for classification risk in stationary, geometrically ergodic Markov chains and prove that traditional uniform bagging is suboptimal by a factor of √Tmix. To bridge this gap, the authors propose adaptive spectral routing, an algorithm that partitions data based on the Fiedler eigenvector of the dependency graph to achieve minimax optimality without prior knowledge of the mixing time. Experimental validation is provided across synthetic Markov chains, spatial grids, the UCR archive, and Atari DQN ensembles.

## Key Contributions

- Established an information-theoretic lower bound of Ω(sqrt(Tmix/n)) for classification risk under Markov dependence.
- Demonstrated that standard uniform bagging is suboptimal under Markov dependence with a lower bound of Ω(Tmix/sqrt(n)), creating a √Tmix gap.
- Introduced adaptive spectral routing, which partitions training data using the Fiedler eigenvector to achieve the minimax optimal rate of O(sqrt(Tmix/n)).

## Open Questions & Future Work

- [[finite-width-rl-ensemble-covariance]]

## Key Concepts

- [[adaptive-spectral-routing]]: A data partitioning technique for ensemble learning that uses the empirical Fiedler eigenvector to account for Markovian dependency structures.

## Archivist Review

I have approved 'Adaptive Spectral Routing' as a novel ensemble partitioning method that addresses Markovian data dependence, and the open question regarding 'Finite-width RL ensemble covariance' as it identifies a clear theoretical gap in applying ensemble theory to deep learning. The UCR archive was rejected as it is a standard, widely-known benchmark repository.

### Approved Concepts
- Adaptive Spectral Routing: Provides a theoretically grounded method to mitigate the impact of Markov dependence in ensemble learning by leveraging spectral graph properties.

### Approved Open Questions
- Finite-width RL ensemble covariance: This is a central limitation for applying the theoretical results to practical deep RL, as the current proof relies on NTK to bridge the gap between simple linear models and complex neural networks. Extending this would provide a more robust theoretical foundation for ensemble methods in deep learning.

### Rejected Candidates
- [dataset] UCR archive (`ucr-archive`) - not_novel: The UCR archive is a massive, widely-used, and mature benchmark for time-series classification that does not require a standalone vault entry; it is a general-purpose repository rather than a novel or highly specific contribution of this paper.

## Links

- [Abstract](https://arxiv.org/abs/2604.13414)
- [PDF](https://arxiv.org/pdf/2604.13414)

