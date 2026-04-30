---
# CSL-compatible fields
title: "Bayesian inference for hidden Markov models under genuine multimodality with application to ecological time series"
author:
  - literal: "Marco A. Gallegos-Herrada"
  - literal: "Vianey Leos-Barajas"
  - literal: "Jeffrey S. Rosenthal"
issued:
  date-parts:
    - [2026, 4, 27]
url: "https://arxiv.org/abs/2604.24587"

# Custom fields
paper_id: "2604.24587"
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
processed_at: "2026-04-30T06:03:15Z"
created_at: "2026-04-30T06:03:15Z"
---

# Bayesian inference for hidden Markov models under genuine multimodality with application to ecological time series

**Authors**: Marco A. Gallegos-Herrada, Vianey Leos-Barajas, Jeffrey S. Rosenthal
**Date**: 2026-04-27
**Paper ID**: [openalex:2604.24587](https://arxiv.org/abs/2604.24587)

## Summary

This paper addresses the challenge of Bayesian inference in hidden Markov models (HMMs) when the posterior distribution exhibits genuine multimodality, even after addressing label switching. The authors identify and correct common implementation failures of parallel tempering (PT) algorithms in this context and propose new non-informative priors that improve posterior exploration. The methodology is applied to analyze blue whale dive behavior, demonstrating that improved sampling leads to more reliable inference of movement patterns in complex, covariate-dependent models.

## Key Contributions

- Identifies critical implementation pitfalls in parallel tempering (PT) algorithms for HMMs that impede effective exploration of multimodal posterior distributions.
- Proposes novel non-informative prior distributions specifically designed to facilitate robust Bayesian exploration of HMM posterior landscapes.
- Demonstrates the effectiveness of the refined PT implementation on blue whale dive time series data, accounting for behavioral covariates.

## Open Questions & Future Work

- [[optimal-swap-rate-hmm-pt]]
- [[hmm-mode-validation-diagnostics]]

## Archivist Review

The paper focuses on implementation refinements for HMM inference rather than novel algorithmic concepts; therefore, no concepts were approved. The open questions regarding HMM-specific parallel tempering optimization and mode validation are well-formulated, research-grade bottlenecks that are distinct from existing vault entries.

### Approved Open Questions
- Optimal swap rate for HMMs: Identifying the optimal swap acceptance rate is critical for minimizing computational costs and ensuring efficient exploration of high-dimensional, multimodal posterior distributions in Bayesian HMM inference.
- Validating HMM posterior modes: Without rigorous validation, relying on mode-wise inference may lead to incorrect scientific conclusions by over-interpreting numerical artifacts.

## Links

- [Abstract](https://arxiv.org/abs/2604.24587)
- [PDF](https://arxiv.org/pdf/2604.24587)

