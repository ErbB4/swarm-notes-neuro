---
# CSL-compatible fields
title: "Neyman Jackknife: Design-Based Variance Estimation for Causal Inference under Interference"
author:
  - literal: "Bryan Park"
  - literal: "Stefan Wager"
issued:
  date-parts:
    - [2026, 4, 27]
url: "https://arxiv.org/abs/2604.24017"

# Custom fields
paper_id: "2604.24017"
paper_source: "openalex"
domain: "statistics-and-causal-inference"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "neyman-jackknife"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-30T06:03:49Z"
created_at: "2026-04-30T06:03:49Z"
---

# Neyman Jackknife: Design-Based Variance Estimation for Causal Inference under Interference

**Authors**: Bryan Park, Stefan Wager
**Date**: 2026-04-27
**Paper ID**: [openalex:2604.24017](https://arxiv.org/abs/2604.24017)

## Summary

This paper introduces the Neyman Jackknife, a flexible variance estimation framework designed for causal inference in finite populations where interference exists. By recomputing target estimators under systematic treatment assignment omissions, the framework provides a general blueprint for conservative variance estimation. It unifies classical approaches like the Neyman estimator and Newey-West HAC, while demonstrating strong empirical performance across various settings compared to specialized baseline methods.

## Key Contributions

- Introduces the Neyman Jackknife, a general-purpose framework for conservative variance estimation in finite-population causal inference under interference.
- Demonstrates that the proposed framework recovers classical estimators such as the Neyman estimator (under SUTVA) and Newey-West HAC (for time series).
- Shows via numerical experiments that the framework achieves competitive performance compared to domain-specific, purpose-built variance estimators.

## Open Questions & Future Work

- [[neyman-jackknife-parameter-tradeoff]]

## Key Concepts

- [[neyman-jackknife]]: A flexible framework for conservative variance estimation in finite-population causal inference that functions by recomputing target estimators under omitted treatment assignments.

## Archivist Review

The Neyman Jackknife is approved as a significant conceptual contribution that unifies various existing variance estimation techniques. One open question regarding parameter optimization is approved as it addresses the core implementation tradeoff of the proposed framework. The second candidate on spectral gaps was rejected as it represents a specific technical sub-problem rather than a high-level research bottleneck.

### Approved Concepts
- Neyman Jackknife: It provides a general, unified blueprint for variance estimation that generalizes classical estimators like Newey-West HAC and Neyman estimators, making it a highly reusable methodological contribution.

### Approved Open Questions
- Neyman Jackknife parameter optimization: Characterizing this tradeoff is essential for making the Neyman Jackknife practically effective and providing clear guidelines for hyperparameter selection in diverse experimental designs.

### Rejected Candidates
- [open_question] Approximating spectral gaps for complex designs (`spectral-gap-complex-designs`) - subcomponent_of_broader_mechanism: While mathematically interesting, this is a specific technical hurdle related to the implementation of bounds rather than a primary conceptual bottleneck for the framework's application.

## Links

- [Abstract](https://arxiv.org/abs/2604.24017)
- [PDF](https://arxiv.org/pdf/2604.24017)

