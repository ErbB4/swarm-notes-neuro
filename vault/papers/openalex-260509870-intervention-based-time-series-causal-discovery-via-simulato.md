---
# CSL-compatible fields
title: "Intervention-Based Time Series Causal Discovery via Simulator-Generated Interventional Distributions"
author:
  - literal: "Tsuyoshi Okita"
issued:
  date-parts:
    - [2026, 5, 11]
url: "https://arxiv.org/abs/2605.09870"

# Custom fields
paper_id: "2605.09870"
paper_source: "openalex"
domain: "time-series"
tags:
  - "causal-discovery"
  - "time-series-forecasting"
  - "flow-matching"
architectures:
  []
datasets:
  []
concept_slugs:
  - "svar-fm"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-14T06:09:26Z"
created_at: "2026-05-14T06:09:26Z"
---

# Intervention-Based Time Series Causal Discovery via Simulator-Generated Interventional Distributions

**Authors**: Tsuyoshi Okita
**Date**: 2026-05-11
**Paper ID**: [openalex:2605.09870](https://arxiv.org/abs/2605.09870)

## Summary

SVAR-FM is a time series causal discovery framework that uses physics-based simulators to implement Pearl's do-operator by clamping variables to generate interventional distributions. Conditional Flow Matching is then employed to learn nonlinear interventional conditionals from these physically generated samples. The method is shown to recover correct causal directions in domains where observational methods fail due to confounding. Furthermore, it includes a theoretical sign-flip prediction that quantifies the relationship between simulator fidelity and causal estimation accuracy.

## Key Contributions

- Proposes SVAR-FM, which utilizes physics simulators as interventional generators to physically sever confounding paths in time series data.
- Establishes identifiability of structural VAR models under a coverage condition on simulator-clampable variables.
- Demonstrates a theoretical sign-flip corollary where low simulator fidelity leads to reversed causal estimates, empirically verified in ultrafast laser physics.

## Open Questions & Future Work

- [[simulator-fidelity-causal-identification-bias]]
- [[active-intervention-selection-causal-discovery]]

## Key Concepts

- [[svar-fm]]: A framework for time series causal discovery that utilizes physics-based simulators to physically generate interventional data for identifying structural vector autoregressive models.

## Archivist Review

The SVAR-FM framework is approved as a distinct contribution for simulator-based causal discovery. The open questions regarding simulator fidelity and active intervention selection are fundamental, domain-agnostic challenges for any simulator-assisted causal pipeline. No datasets were approved as none were cited as reusable public benchmarks.

### Approved Concepts
- SVAR-FM: Provides a novel, reusable paradigm for time-series causal discovery by using simulators as physical implementations of the do-operator to break confounding.

### Approved Open Questions
- Simulator Fidelity in Causal Discovery: Fundamental for ensuring the validity of AI-for-Science causal discovery workflows, particularly when high-fidelity models are computationally expensive.
- Active Intervention Selection Strategies: Key for scaling causal discovery to complex scientific systems where simulation budgets are a primary constraint.

## Links

- [Abstract](https://arxiv.org/abs/2605.09870)
- [PDF](https://arxiv.org/pdf/2605.09870)

