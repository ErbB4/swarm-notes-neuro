---
# CSL-compatible fields
title: "Delving into Non-Exchangeability for Conformal Prediction in Graph-Structured Multivariate Time Series"
author:
  - literal: "Ruichao Guo"
  - literal: "Xingyao Han"
  - literal: "Luo Wenshui"
  - literal: "Zhe Liu"
  - literal: "Chen Gong"
  - literal: "Hesheng Wang"
issued:
  date-parts:
    - [2026, 5, 6]
url: "https://arxiv.org/abs/2605.04957"

# Custom fields
paper_id: "2605.04957"
paper_source: "openalex"
domain: "time-series"
tags:
  - "time-series"
  - "uncertainty-quantification"
  - "graph-neural-networks"
  - "conformal-prediction"
  - "forecasting"
architectures:
  []
datasets:
  []
concept_slugs:
  - "spectral-graph-conditional-exchangeability"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-09T05:56:47Z"
created_at: "2026-05-09T05:56:47Z"
---

# Delving into Non-Exchangeability for Conformal Prediction in Graph-Structured Multivariate Time Series

**Authors**: Ruichao Guo, Xingyao Han, Luo Wenshui, Zhe Liu, Chen Gong, Hesheng Wang
**Date**: 2026-05-06
**Paper ID**: [openalex:2605.04957](https://arxiv.org/abs/2605.04957)

## Summary

This paper addresses the limitation of standard conformal prediction in graph-structured multivariate time series, where cross-node coupling violates the exchangeability assumption. The authors introduce Spectral Graph Conditional Exchangeability (SGCE), which partitions data into high-frequency components—treated as exchangeable—and low-frequency components that capture global trends. By conditioning high-frequency residuals on these low-frequency embeddings, the proposed SCALE framework enables robust uncertainty quantification for non-exchangeable temporal graphs, outperforming current state-of-the-art conformal methods on traffic forecasting tasks.

## Key Contributions

- Proposes Spectral Graph Conditional Exchangeability (SGCE) to enable valid conformal prediction in the presence of cross-node dependencies.
- Introduces Spectral Conformal prediction via wAveLEt transform (SCALE), an end-to-end framework that utilizes graph wavelets for decomposition and conformalizes high-frequency residuals.
- Demonstrates superior coverage-efficiency trade-offs on traffic forecasting benchmarks compared to existing conformal prediction methods.

## Open Questions & Future Work

- [[conformal-prediction-non-exchangeable-graphs]]

## Key Concepts

- [[spectral-graph-conditional-exchangeability]]: A framework for uncertainty quantification in non-exchangeable graph-structured data by conditioning high-frequency spectral components on low-frequency global trends.

## Archivist Review

The concept of Spectral Graph Conditional Exchangeability (SGCE) is approved as it provides a foundational mechanism for handling non-exchangeability in graph-structured time series. The open question regarding conformal prediction in non-exchangeable graphs is also approved as a significant unresolved theoretical and practical bottleneck. Other candidates were rejected for being either specific implementation instances or generic dataset descriptors.

### Approved Concepts
- Spectral Graph Conditional Exchangeability: Introduces a novel paradigm for applying conformal prediction to non-exchangeable graph-structured time series by conditioning on spectral features.

### Approved Open Questions
- Conformal Prediction for Graph-Structured Time Series: Addressing this bottleneck is essential for applying reliable, distribution-free uncertainty quantification to high-stakes, graph-structured systems where point forecasts are insufficient.

### Rejected Candidates
- [concept] Spectral Conformal prediction via wAveLEt transform (`scale-framework`) - subcomponent_of_broader_mechanism: The paper-specific implementation SCALE is a subcomponent application of the more fundamental SGCE concept.
- [dataset] Traffic (`traffic-dataset`) - generic: Generic dataset label without reference to a specific version or collection.

## Links

- [Abstract](https://arxiv.org/abs/2605.04957)
- [PDF](https://arxiv.org/pdf/2605.04957)

