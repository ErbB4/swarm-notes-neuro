---
# CSL-compatible fields
title: "Large-Scale Asset Selection via Metric Dependence with Enriched High Frequency Information"
author:
  - literal: "Yangzhou Chen"
  - literal: "Shuaida He"
  - literal: "Xin Chen"
issued:
  date-parts:
    - [2026, 5, 4]
url: "https://arxiv.org/abs/2605.02326"

# Custom fields
paper_id: "2605.02326"
paper_source: "openalex"
domain: "time-series"
tags:
  - "time-series-forecasting"
  - "financial-econometrics"
  - "portfolio-optimization"
architectures:
  []
datasets:
  []
concept_slugs:
  - "metric-dependence-screening"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-07T06:05:23Z"
created_at: "2026-05-07T06:05:23Z"
---

# Large-Scale Asset Selection via Metric Dependence with Enriched High Frequency Information

**Authors**: Yangzhou Chen, Shuaida He, Xin Chen
**Date**: 2026-05-04
**Paper ID**: [openalex:2605.02326](https://arxiv.org/abs/2605.02326)

## Summary

This paper addresses the sensitivity of large-scale portfolio allocation to estimation error by introducing Metric Dependence Screening (MDS). MDS represents asset data as object-valued point-curves, capturing both daily returns and intraday risk dynamics to improve asset selection. By employing a Fréchet variation-based dependence score, the method effectively filters high-dimensional investable universes before standard mean-variance allocation. Theoretical consistency and empirical performance are validated across simulations and a large-scale dataset of Chinese A-share stocks.

## Key Contributions

- Introduces Metric Dependence Screening (MDS), an asset selection procedure leveraging point-curve objects that combine daily returns with intraday risk curves.
- Establishes theoretical guarantees including concentration, sure selection, and rank consistency under ultrahigh dimensionality and α-mixing time series dependence.
- Demonstrates improved out-of-sample portfolio performance over return-based and scalar-based benchmarks on a dataset of 2,938 Chinese A-share stocks.

## Open Questions & Future Work

- [[integrating-market-frictions-in-screening]]

## Key Concepts

- [[metric-dependence-screening]]: A high-frequency data-driven screening procedure that uses Fréchet variation-based dependence scores to rank assets based on reward and intraday risk dynamics.

## Archivist Review

The paper introduces a robust framework for high-dimensional asset selection using object-valued representations. Metric Dependence Screening is approved for its distinct methodological contribution to financial econometrics. One open question regarding market frictions is approved, as it addresses a core limitation in translating theoretical performance gains to practical feasibility, while the other question was rejected as a standard experimental extension.

### Approved Concepts
- Metric Dependence Screening: It is the core methodological contribution of the paper for asset selection in large-scale portfolios.

### Approved Open Questions
- Integrating Market Frictions in Screening: Without accounting for transaction costs and turnover, the reported portfolio gains may be overstated, and the selection method might be practically infeasible for high-frequency or high-turnover rebalancing strategies.

### Rejected Candidates
- [open_question] Alternative High-Frequency Risk Signatures (`alternative-high-frequency-risk-signatures`) - low_impact: This is a standard research extension suggestion rather than a substantial theoretical or architectural bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2605.02326)
- [PDF](https://arxiv.org/pdf/2605.02326)

