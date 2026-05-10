---
# CSL-compatible fields
title: "End-to-End Identifiable and Consistent Recurrent Switching Dynamical Systems"
author:
  - literal: "Carles Balsells-Rodas"
  - literal: "Zhengrui Xiang"
  - literal: "Xavier Sumba"
  - literal: "Yingzhen Li"
issued:
  date-parts:
    - [2026, 5, 7]
url: "https://arxiv.org/abs/2605.06315"

# Custom fields
paper_id: "2605.06315"
paper_source: "openalex"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "omega-sds"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-10T06:05:26Z"
created_at: "2026-05-10T06:05:26Z"
---

# End-to-End Identifiable and Consistent Recurrent Switching Dynamical Systems

**Authors**: Carles Balsells-Rodas, Zhengrui Xiang, Xavier Sumba, Yingzhen Li
**Date**: 2026-05-07
**Paper ID**: [openalex:2605.06315](https://arxiv.org/abs/2605.06315)

## Summary

This paper addresses the challenge of learning identifiable representations in sequential models characterized by regime-switching dynamics. The authors move beyond the common reliance on variational approximations by providing theoretical identifiability guarantees for recurrent nonlinear switching dynamical systems. They propose ΩSDS, a flow-based estimator that allows for exact likelihood optimization through expectation-maximisation, resulting in better latent structure recovery and more precise dynamical forecasting compared to standard VAE-based methods.

## Key Contributions

- Establishes theoretical identifiability for a broad class of recurrent nonlinear switching dynamical systems, extending beyond stationary or restricted emission assumptions.
- Introduces ΩSDS, a flow-based estimator that facilitates exact likelihood optimization for switching systems via expectation-maximisation.
- Demonstrates superior latent disentanglement and predictive accuracy compared to traditional VAE-based approaches on both synthetic and empirical datasets.

## Key Concepts

- [[omega-sds]]: A flow-based estimator for recurrent switching dynamical systems that facilitates exact likelihood estimation via expectation-maximisation.

## Archivist Review

I approved the ΩSDS concept as it represents a novel methodological approach to overcoming the approximation limitations of variational inference in switching dynamical systems. I have maintained a strict stance on datasets and open questions, finding no candidates in this specific entry that meet the high threshold for long-term vault inclusion. The review prioritized foundational algorithmic contributions over application-specific metrics.

### Approved Concepts
- ΩSDS: It enables exact likelihood optimization for recurrent switching dynamical systems, overcoming VAE approximation gaps.

## Links

- [Abstract](https://arxiv.org/abs/2605.06315)
- [PDF](https://arxiv.org/pdf/2605.06315)

