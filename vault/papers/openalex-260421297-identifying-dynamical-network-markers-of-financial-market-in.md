---
# CSL-compatible fields
title: "Identifying dynamical network markers of financial market instability"
author:
  - literal: "Mariko I. Ito"
  - literal: "Hiroyuki Hasada"
  - literal: "Yudai Honma"
  - literal: "Takaaki Ohnishi"
  - literal: "Tsutomu Watanabe"
  - literal: "Kazuyuki Aihara"
issued:
  date-parts:
    - [2026, 4, 23]
url: "https://arxiv.org/abs/2604.21297"

# Custom fields
paper_id: "2604.21297"
paper_source: "openalex"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "dynamical-network-marker-theory"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-26T05:52:26Z"
created_at: "2026-04-26T05:52:26Z"
---

# Identifying dynamical network markers of financial market instability

**Authors**: Mariko I. Ito, Hiroyuki Hasada, Yudai Honma, Takaaki Ohnishi, Tsutomu Watanabe, Kazuyuki Aihara
**Date**: 2026-04-23
**Paper ID**: [openalex:2604.21297](https://arxiv.org/abs/2604.21297)

## Summary

This paper applies Dynamical Network Marker (DNM) theory to identify precursors to market instability in financial systems. By modeling market participants as interacting nodes in a network using Tokyo Stock Exchange order and execution data, the authors identify critical slowing down as an early warning signal for large price movements. The methodology successfully generates daily indicators of structural change, highlighting the potential for building real-world early warning systems in high-dimensional trading environments.

## Key Contributions

- Introduces a framework to treat financial market participants as interacting elements for Dynamical Network Marker (DNM) analysis.
- Demonstrates the detection of early warning signals for large price movements using Tokyo Stock Exchange order data.
- Validates DNM theory's applicability to high-dimensional trading activity time series on a daily time scale.

## Open Questions & Future Work

- [[dnm-robustness-exogenous-shocks]]

## Key Concepts

- [[dynamical-network-marker-theory]]: A theoretical framework for identifying early-warning signals of critical transitions in high-dimensional systems by analyzing the collective behavior of interacting components.

## Archivist Review

I approved the Dynamical Network Marker Theory concept because it provides a powerful, distinct alternative to traditional forecasting by focusing on critical slowing down in interaction networks. I also approved the open question regarding robustness to exogenous shocks, as it addresses a fundamental limitation in applying this theory to real-world, non-closed systems. I rejected the ensemble aggregation question because it is a general machine learning task rather than one tied strictly to the unique challenges of DNM research.

### Approved Concepts
- Dynamical Network Marker Theory: Provides a unique framework for identifying structural change points in high-dimensional systems by analyzing node interactions, offering a shift from standard time-series forecasting.

### Approved Open Questions
- DNM Robustness Against Exogenous Shocks: Without addressing the impact of exogenous shocks, the practical applicability of DNM for real-time risk management remains limited, as external market noise frequently triggers false positives or obscures pre-instability signals.

### Rejected Candidates
- [open_question] Ensemble-Based DNM Indicator Aggregation (`dnm-ensemble-aggregation`) - generic: This is a fairly generic ensemble/aggregation problem applicable to any forecasting method, and not specific to the unique mechanics of DNM theory.

## Links

- [Abstract](https://arxiv.org/abs/2604.21297)
- [PDF](https://arxiv.org/pdf/2604.21297)

