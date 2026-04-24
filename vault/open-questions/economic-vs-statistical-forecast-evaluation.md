---
created_at: '2026-04-24T05:51:07Z'
source_papers:
- '[[openalex-260419580-probabilistic-forecasting-for-day-ahead-electricity-prices-b]]'
title: Economic vs Statistical Forecast Evaluation
---

**Background:** Quantile-based trading strategies (QBTS) are frequently used in energy market literature to evaluate the economic utility of probabilistic price forecasts by placing limit orders based on specific quantiles.

**Question / Future Work:** It remains unclear whether and under what conditions the economic performance of trading strategies, such as QBTS or those based on stochastic programming, can serve as a valid substitute for (strictly) proper scoring rules in model selection and forecast evaluation. The potential for these application-based metrics to exhibit low discriminatory power or to incentivize non-optimal forecasting behaviors necessitates further investigation into the consistency between statistical accuracy and decision quality.

**Why It Matters:** Understanding this relationship is fundamental for the field of electricity price forecasting, as it determines whether researchers should rely on statistical scores or application-specific outcomes when selecting and validating forecasting models.

**Evidence:** From a practical perspective, this implies that economic backtest performance can be decision-relevant, but it is generally unsuitable as a stand-alone strictly proper scoring rule for model selection over full predictive distributions.