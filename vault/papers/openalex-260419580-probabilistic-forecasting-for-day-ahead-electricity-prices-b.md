---
# CSL-compatible fields
title: "Probabilistic Forecasting for Day-ahead Electricity Prices, Battery Trading Strategies and the Economic Evaluation of Predictive Accuracy"
author:
  - literal: "Simon Hirsch"
  - literal: "Florian Ziel"
issued:
  date-parts:
    - [2026, 4, 21]
url: "https://arxiv.org/abs/2604.19580"

# Custom fields
paper_id: "2604.19580"
paper_source: "openalex"
domain: "time-series"
tags:
  - "time-series"
  - "forecasting"
  - "energy-markets"
architectures:
  []
datasets:
  []
concept_slugs:
  - "quantile-based-trading-strategy"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-24T05:51:07Z"
created_at: "2026-04-24T05:51:07Z"
---

# Probabilistic Forecasting for Day-ahead Electricity Prices, Battery Trading Strategies and the Economic Evaluation of Predictive Accuracy

**Authors**: Simon Hirsch, Florian Ziel
**Date**: 2026-04-21
**Paper ID**: [openalex:2604.19580](https://arxiv.org/abs/2604.19580)

## Summary

This paper critically evaluates the relationship between statistical probabilistic forecast accuracy and economic decision-making in electricity markets. The authors analyze common quantile-based battery trading strategies, highlighting inherent failures in incentivizing honest forecasts and accounting for price interdependencies. By modeling battery arbitrage as a stochastic program, the study demonstrates the limitations of using simplified trading benchmarks for evaluating forecasting models. The work provides significant insights into the reliability of application-based forecast assessment and proposes more robust methodologies for energy market forecasting.

## Key Contributions

- Identifies and formalizes flaws in current quantile-based trading strategies (QBTS) for battery arbitrage, specifically lack of incentive for honest forecasting and neglect of intertemporal price dependency.
- Proposes framing battery optimization as a stochastic programming problem utilizing full probabilistic forecasts rather than simple quantile approximations.
- Provides empirical evidence demonstrating that standard battery trading benchmarks can lead to misleading rankings of forecasting models due to sensitivity to model assumptions and risk profiles.

## Open Questions & Future Work

- [[economic-vs-statistical-forecast-evaluation]]

## Key Concepts

- [[quantile-based-trading-strategy]]: A trading heuristic that uses predictive quantiles to set limit orders, which can lead to biased model evaluation in energy market forecasting.

## Archivist Review

I approved the term 'Quantile-Based Trading Strategy' as it is a specific, widely used heuristic in energy forecasting that researchers should critically evaluate. The open question regarding the alignment between economic performance and statistical forecasting accuracy is highly relevant and captures a core methodological tension in energy time-series research. I adhered to the policy of being selective, approving only these two items while rejecting other general concepts.

### Approved Concepts
- Quantile-Based Trading Strategy: This highlights a common but flawed practice in energy forecasting evaluation, making it a valuable term for future reference in discussions about model evaluation.

### Approved Open Questions
- Economic vs Statistical Forecast Evaluation: Understanding this relationship is fundamental for the field of electricity price forecasting, as it determines whether researchers should rely on statistical scores or application-specific outcomes when selecting and validating forecasting models.

## Links

- [Abstract](https://arxiv.org/abs/2604.19580)
- [PDF](https://arxiv.org/pdf/2604.19580)

