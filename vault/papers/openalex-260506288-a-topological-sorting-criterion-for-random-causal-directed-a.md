---
# CSL-compatible fields
title: "A Topological Sorting Criterion for Random Causal Directed Acyclic Graphs"
author:
  - literal: "Alexander G. Reisach"
  - literal: "Antoine Chambaz"
  - literal: "Gilles Blanchard"
  - literal: "Sebastian Weichwald"
issued:
  date-parts:
    - [2026, 5, 7]
url: "https://arxiv.org/abs/2605.06288"

# Custom fields
paper_id: "2605.06288"
paper_source: "openalex"
domain: "nlp"
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
processed_at: "2026-05-10T06:05:09Z"
created_at: "2026-05-10T06:05:09Z"
---

# A Topological Sorting Criterion for Random Causal Directed Acyclic Graphs

**Authors**: Alexander G. Reisach, Antoine Chambaz, Gilles Blanchard, Sebastian Weichwald
**Date**: 2026-05-07
**Paper ID**: [openalex:2605.06288](https://arxiv.org/abs/2605.06288)

## Summary

This paper investigates the properties of random causal DAGs commonly used in causal discovery evaluations. The authors show that a node's number of reachable neighbors, or 'relatives', tends to increase monotonically along the causal ordering in standard synthetic graph models. They demonstrate that this property can be exploited to recover the causal order via simple sorting, and argue that this behavior often leads to degenerate Markov equivalence classes. Consequently, they caution against current synthetic evaluation practices and suggest time-series DAGs as a more robust alternative.

## Key Contributions

- Identifies that the set of nodes reachable via open paths (relatives) in synthetic DAGs increases monotonically along the causal order.
- Proposes a sorting-based causal order recovery method using the estimated number of relatives.
- Demonstrates that strict monotonicity of relatives implies a singular Markov equivalence class, challenging the validity of certain synthetic benchmarks.

## Links

- [Abstract](https://arxiv.org/abs/2605.06288)
- [PDF](https://arxiv.org/pdf/2605.06288)

