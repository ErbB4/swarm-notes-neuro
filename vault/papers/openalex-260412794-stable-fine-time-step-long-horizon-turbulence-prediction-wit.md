---
# CSL-compatible fields
title: "Stable Fine-Time-Step Long-Horizon Turbulence Prediction with a Multi-Stepsize Mixture-of-Experts Neural Operator"
author:
  - literal: "Guanyu Pan"
  - literal: "Huiyu Yang"
  - literal: "Yunpeng Wang"
  - literal: "Zikun Xu"
  - literal: "Jianchun Wang"
  - literal: "Nianyu Yi"
issued:
  date-parts:
    - [2026, 4, 14]
url: "https://arxiv.org/abs/2604.12794"

# Custom fields
paper_id: "2604.12794"
paper_source: "openalex"
domain: "time-series"
tags:
  - "time-series"
  - "forecasting"
architectures:
  []
datasets:
  []
concept_slugs:
  - "ms-moe-neural-operator"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-17T05:47:03Z"
created_at: "2026-04-17T05:47:03Z"
---

# Stable Fine-Time-Step Long-Horizon Turbulence Prediction with a Multi-Stepsize Mixture-of-Experts Neural Operator

**Authors**: Guanyu Pan, Huiyu Yang, Yunpeng Wang, Zikun Xu, Jianchun Wang, Nianyu Yi
**Date**: 2026-04-14
**Paper ID**: [openalex:2604.12794](https://arxiv.org/abs/2604.12794)

## Summary

This paper addresses the stability issues in long-horizon autoregressive neural operator predictions for turbulent flows, which are often caused by error accumulation at fine temporal resolutions. The authors propose a multi-stepsize mixture-of-experts (Ms-MoE) framework built on an implicit factorized Transformer (IFactFormer) backbone that adapts to different requested relative strides. By utilizing a time-step router to select scale-specific experts, the model maintains high-fidelity predictions during long-term rollouts. Empirical results on homogeneous isotropic turbulence and turbulent channel flow demonstrate superior stability and statistical accuracy over existing methods.

## Key Contributions

- Introduces the Multi-stepsize Mixture-of-Experts (Ms-MoE) neural operator that enables stable long-horizon turbulence forecasting at fine temporal resolutions.
- Proposes the Implicit Factorized Transformer (IFactFormer) as a backbone architecture for modeling time-advancement operators.
- Demonstrates improved stability and agreement with long-time-averaged statistics on forced homogeneous isotropic turbulence (HIT) and turbulent channel flow datasets compared to standard autoregressive baselines.

## Open Questions & Future Work

- [[long-horizon-neural-operator-stability]]

## Key Concepts

- [[ms-moe-neural-operator]]: A mixture-of-experts architecture that conditions on temporal stride to maintain stability and accuracy across varying time-steps in forecasting models.

## Archivist Review

I have approved the Ms-MoE concept as a reusable architecture for temporal stride conditioning. I also approved a more generalized version of the open question regarding stability and compositional consistency in neural operators, as this represents a fundamental challenge in scientific ML time-series forecasting. The proposed open question from the analysis was rejected in favor of the newly defined one to better align with the vault's standards for tracking long-term research bottlenecks.

### Approved Concepts
- Multi-stepsize Mixture-of-Experts (Ms-MoE): Provides a novel mechanism for handling multi-scale temporal dynamics in neural operators, which is a common bottleneck in long-horizon forecasting.

### Approved Open Questions
- Long-horizon Neural Operator Stability: Crucial for the long-term reliability of surrogates in scientific computing where statistical accuracy is as important as point-wise error.

### Rejected Candidates
- [open_question] Stable Long-Horizon Turbulence Prediction (`stable-long-horizon-turbulence-prediction`) - duplicate_existing: Duplicate of or subsumed by the more general and better-defined 'long-horizon-neural-operator-stability'.

## Links

- [Abstract](https://arxiv.org/abs/2604.12794)
- [PDF](https://arxiv.org/pdf/2604.12794)

