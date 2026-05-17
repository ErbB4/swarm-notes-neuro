---
# CSL-compatible fields
title: "In-Context Learning for Data-Driven Censored Inventory Control"
author:
  - literal: "Sohom Mukherjee"
  - literal: "Anh-Duy Pham"
  - literal: "Richard Pibernik"
  - literal: "Yunbei Xu"
issued:
  date-parts:
    - [2026, 5, 14]
url: "https://arxiv.org/abs/2605.14840"

# Custom fields
paper_id: "2605.14840"
paper_source: "openalex"
domain: "time-series"
tags:
  - "forecasting"
  - "inventory-control"
  - "in-context-learning"
  - "censored-data"
  - "posterior-sampling"
  - "meta-learning"
architectures:
  []
datasets:
  - "superstore-dataset"
concept_slugs:
  - "icgps-framework"
dataset_slugs:
  - "superstore-dataset"
skill: "TimeSeriesSkill"
processed_at: "2026-05-17T06:09:16Z"
created_at: "2026-05-17T06:09:16Z"
---

# In-Context Learning for Data-Driven Censored Inventory Control

**Authors**: Sohom Mukherjee, Anh-Duy Pham, Richard Pibernik, Yunbei Xu
**Date**: 2026-05-14
**Paper ID**: [openalex:2605.14840](https://arxiv.org/abs/2605.14840)

## Summary

This paper introduces In-Context Generative Posterior Sampling (ICGPS) to address inventory control problems with decision-dependent censoring. By meta-training a generative model offline and utilizing in-context autoregressive generation online, the method effectively completes censored demand to perform posterior sampling. Theoretical results show that the online regret is bounded by the quality of the offline completion, while experiments confirm robust performance and competitive advantages over traditional Thompson sampling and bandit heuristics, particularly under heavy censoring.

## Key Contributions

- Introduces In-Context Generative Posterior Sampling (ICGPS), a plug-in template for decision-making under censored feedback that leverages meta-trained generative models.
- Provides a theoretical analysis bounding the Bayesian regret of ICGPS, demonstrating that online performance is controlled by offline censored predictive mismatch.
- Instantiates the ICGPS framework with ChronosFlow, demonstrating robustness to prior mismatch and superior performance under heavy censoring compared to myopic and UCB-style baselines.

## Open Questions & Future Work

- [[identifiability-in-censored-inventory-control]]

## Key Concepts

- [[icgps-framework]]: A meta-learned framework for solving censored decision-making problems by treating posterior sampling as an in-context autoregressive generation task.

## Archivist Review

I have approved the ICGPS framework as a novel paradigm for combining in-context learning with posterior sampling, and the identifiability question as a fundamental bottleneck for this class of problems. The SuperStore dataset is included as a common, widely used benchmark in this domain. I rejected the specific model architecture 'ChronosFlow' as it is a subcomponent instantiation of the broader ICGPS concept.

### Approved Concepts
- In-Context Generative Posterior Sampling (ICGPS): ICGPS provides a novel plug-in template for sequential decision-making under censoring, shifting the problem from iterative imputation to autoregressive generation.

### Approved Open Questions
- Identifiability under severe censoring: This identifiability challenge is the central bottleneck for deploying offline-meta-learned decision policies in high-stakes operational environments.

### Rejected Candidates
- [concept] ChronosFlow (`chronosflow`) - subcomponent_of_broader_mechanism: This is an instantiation of the framework (a specific model architecture) rather than a reusable concept.

## Datasets

- [[superstore-dataset]]

## Links

- [Abstract](https://arxiv.org/abs/2605.14840)
- [PDF](https://arxiv.org/pdf/2605.14840)

