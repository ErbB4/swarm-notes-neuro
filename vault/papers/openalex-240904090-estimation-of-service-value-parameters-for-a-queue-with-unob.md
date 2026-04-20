---
# CSL-compatible fields
title: "Estimation of service value parameters for a queue with unobserved balking"
author:
  - literal: "Daniel Podorojnyi"
  - literal: "Liron Ravner"
issued:
  date-parts:
    - [2026, 4, 17]
url: "https://arxiv.org/abs/2409.04090"

# Custom fields
paper_id: "2409.04090"
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
skill: "GeneralMLSkill"
processed_at: "2026-04-20T05:54:28Z"
created_at: "2026-04-20T05:54:28Z"
---

# Estimation of service value parameters for a queue with unobserved balking

**Authors**: Daniel Podorojnyi, Liron Ravner
**Date**: 2026-04-17
**Paper ID**: [openalex:2409.04090](https://arxiv.org/abs/2409.04090)

## Summary

This paper addresses the estimation of latent customer service values in a queueing system where only queue lengths are observed, and balking behavior is hidden. The authors propose a Maximum Likelihood Estimator for the parametric distribution of service values and prove its consistency and asymptotic normality. This framework is further applied to develop a dynamic pricing scheme that optimizes revenue by iteratively refining price updates based on estimated parameters. The proposed methodology is validated through numerical simulation experiments.

## Key Contributions

- Constructed a Maximum Likelihood Estimator (MLE) to infer the parametric distribution of customer service values in a queueing system with unobserved balking.
- Established consistency and asymptotic normality for the proposed MLE under verifiable conditions based on observed queue length dynamics.
- Developed a dynamic pricing algorithm that iteratively updates admission prices to maximize revenue by leveraging the estimated service value parameters.

## Open Questions & Future Work

- [[non-parametric-balking-estimation]]
- [[joint-estimation-value-patience]]

## Archivist Review

I have reviewed the submission and decided to approve the two open questions provided, as they identify significant, unresolved research bottlenecks regarding the structural limitations of parametric queueing models. I have rejected all concept candidates as the proposed methodology (MLE for queueing parameters) is a standard application of statistical inference rather than a novel, reusable ML architecture or algorithmic pattern deserving of a permanent vault entry.

### Approved Open Questions
- Non-parametric estimation for unobserved balking: This addresses the restrictive nature of parametric assumptions in strategic queuing models, potentially expanding applicability to real-world scenarios where underlying utility distributions are unknown.
- Joint estimation of valuation and patience: Relaxing the homogeneity of delay sensitivity is critical for accurately modeling real-world queuing systems where customers have diverse time constraints.

## Links

- [Abstract](https://arxiv.org/abs/2409.04090)
- [PDF](https://arxiv.org/pdf/2409.04090)

