---
# CSL-compatible fields
title: "Generative Modeling of Approximately Periodic Time Series by a Posterior-Weighted Gaussian Process"
author:
  - literal: "Elias Reich"
  - literal: "Saverio Messineo"
  - literal: "S. Huber"
issued:
  date-parts:
    - [2026, 5, 13]
url: "https://arxiv.org/abs/2605.13150"

# Custom fields
paper_id: "2605.13150"
paper_source: "openalex"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "posterior-weighted-gaussian-process"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-16T06:01:30Z"
created_at: "2026-05-16T06:01:30Z"
---

# Generative Modeling of Approximately Periodic Time Series by a Posterior-Weighted Gaussian Process

**Authors**: Elias Reich, Saverio Messineo, S. Huber
**Date**: 2026-05-13
**Paper ID**: [openalex:2605.13150](https://arxiv.org/abs/2605.13150)

## Summary

This paper addresses the challenge of modeling approximately periodic time series, where signals exhibit repetitive trajectories with varying duration, amplitude, and dynamics. The authors propose a stochastic generative model based on a Gaussian Process with a posterior-modulated kernel, effectively decoupling intra-repetition structure from inter-repetition variability. This approach allows for the generation of synthetic trajectories that maintain consistent mean structures while introducing smooth, realistic inter-repetition fluctuations.

## Key Contributions

- Introduces a posterior-weighted Gaussian Process that enables generative modeling of approximately periodic time series.
- Proposes a two-stage kernel construction to decouple intra-repetition structural regularity from inter-repetition variability.
- Demonstrates the ability to synthesize realistic trajectories that preserve global structure while accounting for variations in duration, amplitude, and dynamics.

## Open Questions & Future Work

- [[scalable-inference-for-modulated-gp-covariance]]

## Key Concepts

- [[posterior-weighted-gaussian-process]]: A Gaussian Process model that uses a modulated kernel to generate approximately periodic time series by decoupling local trajectory structure from inter-repetition variation.

## Archivist Review

I approved the core 'Posterior-Weighted Gaussian Process' mechanism as it provides a distinct, reusable approach to decomposing time series periodicity. I also approved the open question regarding its scalability, as this represents a significant bottleneck for applying covariance-modulated GPs to long-horizon, high-repetition industrial data. The other candidate question was rejected as being too broad and dependent on general model improvement.

### Approved Concepts
- Posterior-Weighted Gaussian Process: The paper introduces this as the core mechanism to decouple intra-repetition structure from inter-repetition variability in approximately periodic data.

### Approved Open Questions
- Scalable Inference for Modulated GP Covariance: The current method's computational complexity limits its application to datasets with a large number of repetitions; addressing this is critical for the model's scalability in industrial contexts.

## Links

- [Abstract](https://arxiv.org/abs/2605.13150)
- [PDF](https://arxiv.org/pdf/2605.13150)

