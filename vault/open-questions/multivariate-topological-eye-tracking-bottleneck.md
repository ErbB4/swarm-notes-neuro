---
created_at: '2026-04-26T05:51:54Z'
source_papers:
- '[[openalex-260421698-fixation-sequences-as-time-series-a-topological-approach-to]]'
title: Multivariate Topological Time Series
---

**Background:** Topological data analysis characterizes eye-tracking fixation sequences by interpreting them as time series and computing topological features. Currently, this process typically involves decomposing fixation coordinates into independent univariate components.

**Question / Future Work:** Extending topological time series analysis to handle true multivariate signals—such as simultaneous horizontal and vertical coordinates—without losing intrinsic spatial-temporal correlations remains a critical methodological bottleneck. Developing robust filtrations for multivariate time series would allow for a more holistic capture of trajectory dynamics in eye-tracking and similar sequential data.

**Why It Matters:** This is a fundamental bottleneck in the current topological approach to eye-tracking; addressing it would allow researchers to analyze the full, coordinated trajectory of eye movements rather than treating them as independent signals.

**Evidence:** One could generalize the notion of time series to one that captures both the horizontal and the vertical coordinate of a fixation. This, however, would yield a so-called multivariate time series, a format that is unsuitable for the methods of time series classification outlined here.