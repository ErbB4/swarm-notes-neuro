---
# CSL-compatible fields
title: "Pre-localization of Massive Black Hole Binaries in the Millihertz Band"
author:
  - literal: "Xue-Ting Zhang"
  - literal: "Jonathan Gair"
  - literal: "Chris Messenger"
  - literal: "Natalia Korsakova"
  - literal: "Yi-Ming Hu"
  - literal: "Hong-Yu Chen"
issued:
  date-parts:
    - [2026, 4, 27]
url: "https://arxiv.org/abs/2604.24330"

# Custom fields
paper_id: "2604.24330"
paper_source: "openalex"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "amortized-bayesian-inference-gw"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-30T06:04:52Z"
created_at: "2026-04-30T06:04:52Z"
---

# Pre-localization of Massive Black Hole Binaries in the Millihertz Band

**Authors**: Xue-Ting Zhang, Jonathan Gair, Chris Messenger, Natalia Korsakova, Yi-Ming Hu, Hong-Yu Chen
**Date**: 2026-04-27
**Paper ID**: [openalex:2604.24330](https://arxiv.org/abs/2604.24330)

## Summary

This paper addresses the challenge of providing low-latency sky localization for massive black hole binaries (MBHBs) in space-borne gravitational-wave detectors. The authors propose an amortized Bayesian inference pipeline that leverages learned time-series embeddings and neural spline flows (NSF) to achieve rapid parameter estimation. The method successfully provides accurate pre-merger localizations, enabling timely electromagnetic follow-up within a one-minute analysis window.

## Key Contributions

- Introduces a normalizing flow-based inference pipeline using neural spline flows for low-latency gravitational wave parameter estimation.
- Achieves ~20 deg² pre-merger sky localization for massive black hole binaries approximately 15 minutes before coalescence.
- Demonstrates inference speed and accuracy comparable to traditional parallel-tempered Markov chain Monte Carlo (PTMCMC) methods while operating within a one-minute per-event latency budget.

## Open Questions & Future Work

- [[mbhb-source-confusion-separation-bottleneck]]

## Key Concepts

- [[amortized-bayesian-inference-gw]]: A framework that uses learned neural embeddings coupled with normalizing flows to replace traditional MCMC sampling for real-time parameter estimation of gravitational wave signals.

## Archivist Review

I approved the concept of 'Amortized Bayesian Inference for GW Parameter Estimation' as it represents a significant methodological shift in signal processing for real-time scientific inference. The open question on 'source confusion' was approved as a critical, non-trivial bottleneck for future multi-messenger observation architectures, whereas the original candidate was too broad and focused on general incremental precision improvements.

### Approved Concepts
- Amortized Bayesian Inference for GW Parameter Estimation: This approach shifts the computational burden from inference time to training time, which is the key enabler for real-time multi-messenger astronomy pipelines.

### Approved Open Questions
- MBHB Source Confusion Bottleneck: Addressing source confusion is a foundational requirement for the viability of future space-borne detectors like LISA.

### Rejected Candidates
- [open_question] Improving MBHB Inference Precision (`improving-mbhb-inference-precision-and-robustness`) - other: The candidate is partially conflated with general performance improvements; the proposed slug focuses more clearly on the specific, critical bottleneck of source confusion in multi-source environments.

## Links

- [Abstract](https://arxiv.org/abs/2604.24330)
- [PDF](https://arxiv.org/pdf/2604.24330)

