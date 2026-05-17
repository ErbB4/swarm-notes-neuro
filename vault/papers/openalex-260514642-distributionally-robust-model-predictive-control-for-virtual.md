---
# CSL-compatible fields
title: "Distributionally Robust Model Predictive Control for Virtual Power Plants"
author:
  - literal: "Nikolas Recke"
  - literal: "Mathias Hudoba de Badyn"
issued:
  date-parts:
    - [2026, 5, 14]
url: "https://arxiv.org/abs/2605.14642"

# Custom fields
paper_id: "2605.14642"
paper_source: "openalex"
domain: "time-series"
tags:
  - "forecasting-horizon"
  - "seasonality-handling"
architectures:
  []
datasets:
  []
concept_slugs:
  - "time-varying-wasserstein-ambiguity-sets"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-17T06:07:59Z"
created_at: "2026-05-17T06:07:59Z"
---

# Distributionally Robust Model Predictive Control for Virtual Power Plants

**Authors**: Nikolas Recke, Mathias Hudoba de Badyn
**Date**: 2026-05-14
**Paper ID**: [openalex:2605.14642](https://arxiv.org/abs/2605.14642)

## Summary

This paper presents a distributionally robust model predictive control (DR-MPC) framework for Virtual Power Plant (VPP) operation under electricity price uncertainty. By integrating data-driven forecasts with time-varying Wasserstein ambiguity sets, the approach allows the VPP controller to adapt to forecast dispersion and potential distribution shifts. Evaluations on a Nordic case study demonstrate that the proposed method improves economic performance over standard MPC when the ambiguity radius is appropriately tuned, balancing robust reliability with conservativeness.

## Key Contributions

- Proposes a DR-MPC framework for Virtual Power Plants (VPPs) that integrates data-driven forecasting with quantile-based uncertainty quantification.
- Introduces time-varying Wasserstein ambiguity sets to adapt control actions to forecast dispersion and distributional shifts.
- Demonstrates up to 0.8% economic performance improvement in Nordic VPP scenarios compared to standard forecast-based MPC.

## Open Questions & Future Work

- [[joint-wasserstein-ambiguity-sets-temporal-dependencies]]

## Key Concepts

- [[time-varying-wasserstein-ambiguity-sets]]: A mechanism for constructing robust decision-making sets that adapt to time-varying forecast uncertainty and shifts in data distributions.

## Archivist Review

The paper proposes a robust control framework that dynamically adapts to forecast uncertainty. I approved the 'time-varying Wasserstein ambiguity sets' concept for its reusable contribution to distributionally robust optimization, and the 'joint Wasserstein ambiguity sets' open question as a critical limitation in handling temporal dependencies within model predictive control. No datasets were approved as none were sufficiently described as unique, reusable benchmarks.

### Approved Concepts
- Time-Varying Wasserstein Ambiguity Sets: Provides a tractable method for handling distributional uncertainty in MPC by dynamically adjusting the ambiguity set based on real-time data dispersion.

### Approved Open Questions
- Joint Wasserstein Ambiguity Sets: In VPPs with battery storage, decisions at time 'k' influence the state at 'k+1'. If the controller does not account for the joint evolution of price distributions, it may implement overly conservative strategies that ignore profitable, multi-period arbitrage opportunities.

## Links

- [Abstract](https://arxiv.org/abs/2605.14642)
- [PDF](https://arxiv.org/pdf/2605.14642)

