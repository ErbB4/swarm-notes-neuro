---
# CSL-compatible fields
title: "samsara: a continuous-time Markov chain Monte Carlo sampler for trans-dimensional Bayesian analysis"
author:
  - literal: "Gabriele Astorino"
  - literal: "Lorenzo Valbusa Dall'Armi"
  - literal: "R. Buscicchio"
  - literal: "Joachim Pomper"
  - literal: "Angelo Ricciardone"
  - literal: "W. Del Pozzo"
issued:
  date-parts:
    - [2026, 4, 20]
url: "https://arxiv.org/abs/2511.07385"

# Custom fields
paper_id: "2511.07385"
paper_source: "openalex"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "ctmcmc"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-23T05:48:38Z"
created_at: "2026-04-23T05:48:38Z"
---

# samsara: a continuous-time Markov chain Monte Carlo sampler for trans-dimensional Bayesian analysis

**Authors**: Gabriele Astorino, Lorenzo Valbusa Dall'Armi, R. Buscicchio, Joachim Pomper, Angelo Ricciardone, W. Del Pozzo
**Date**: 2026-04-20
**Paper ID**: [openalex:2511.07385](https://arxiv.org/abs/2511.07385)

## Summary

SAMSARA is a continuous-time MCMC framework designed for Bayesian inference where the parameter dimensionality is unknown. By framing parameter evolution as a sequence of Poisson-driven birth, death, and mutation processes, the method achieves automatic acceptance for trans-dimensional moves, bypassing the traditional bottlenecks of RJMCMC. The approach is validated on multi-signal time series and mixture model problems, demonstrating superior sampling efficiency and robust agreement with nested sampling benchmarks.

## Key Contributions

- Introduces SAMSARA, a CTMCMC framework for variable-dimensional Bayesian inference, utilizing Poisson-driven birth-death-mutation processes.
- Achieves automatic acceptance of trans-dimensional moves through adaptive rate definitions, enhancing convergence efficiency compared to standard RJMCMC.
- Demonstrates performance parity with nested sampling on complex tasks including Gaussian mixture models and multi-signal time series decomposition.

## Open Questions & Future Work

- [[ctmcmc-proposal-optimization]]

## Key Concepts

- [[ctmcmc]]: A trans-dimensional sampling framework that uses Poisson-driven continuous-time dynamics to avoid traditional RJMCMC acceptance bottlenecks.

## Archivist Review

I approved the CTMCMC concept as it provides a distinct, reusable alternative to traditional RJMCMC for trans-dimensional Bayesian problems, particularly relevant for time-series modeling where dimensionality may be unknown. I approved the open question on proposal optimization because it addresses a fundamental bottleneck in the scalability of this class of samplers. I rejected the tool name 'SAMSARA' in favor of the mechanism 'CTMCMC' to avoid capturing paper-local artifacts.

### Approved Concepts
- Continuous-time Markov chain Monte Carlo (CTMCMC): Represents a foundational algorithmic shift from RJMCMC for trans-dimensional Bayesian inference.

### Approved Open Questions
- Optimizing Mutation Proposals and Dynamics: Improving proposal schemes is critical for the practical scalability of CTMCMC to high-dimensional parameter spaces with unknown dimensionality.

### Rejected Candidates
- [concept] SAMSARA (`samsara`) - subcomponent_of_broader_mechanism: The paper is the primary introduction of the sampler, but the broader mechanism (CTMCMC) is already approved as a concept, rendering the specific implementation name redundant.

## Links

- [Abstract](https://arxiv.org/abs/2511.07385)
- [PDF](https://arxiv.org/pdf/2511.07385)

