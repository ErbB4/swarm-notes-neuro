---
# CSL-compatible fields
title: "Quantum Adaptive Self-Attention for Financial Rebalancing: An Empirical Study on Automated Market Makers in Decentralized Finance"
author:
  - literal: "Chi-Sheng Chen"
  - literal: "Aidan Hung-Wen Tsai"
issued:
  date-parts:
    - [2026, 4, 21]
url: "https://arxiv.org/abs/2509.16955"

# Custom fields
paper_id: "2509.16955"
paper_source: "openalex"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "quantum-adaptive-self-attention"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-24T05:51:49Z"
created_at: "2026-04-24T05:51:49Z"
---

# Quantum Adaptive Self-Attention for Financial Rebalancing: An Empirical Study on Automated Market Makers in Decentralized Finance

**Authors**: Chi-Sheng Chen, Aidan Hung-Wen Tsai
**Date**: 2026-04-21
**Paper ID**: [openalex:2509.16955](https://arxiv.org/abs/2509.16955)

## Summary

The paper introduces Quantum Adaptive Self-Attention (QASA), a hybrid quantum-classical module designed for financial time-series decision-making in automated market makers. By constructing query, key, and value vectors through variational quantum circuits (VQCs) and applying softmax attention to Pauli-Z expectation values, QASA integrates quantum processing into transformer architectures. Empirical evaluation on BTCUSDC market data shows that QASA-based models outperform purely classical and pure quantum baselines in risk-adjusted metrics like Return and Sharpe ratio. The study confirms the viability of hybrid quantum-classical attention for complex financial rebalancing tasks.

## Key Contributions

- Introduces QASA (Quantum Adaptive Self-Attention), a hybrid quantum-classical attention module utilizing VQCs to process financial time-series data.
- Formulates automated market maker (AMM) rebalancing as a binary detection task, showing QASA achieves superior risk-adjusted returns (13.99%, Sharpe 1.76) compared to classical transformer and pure quantum baselines.
- Provides an empirical comparison on BTCUSDC data demonstrating that QASA-based models offer a favorable performance-stability-cost trade-off over pure quantum or purely classical ensembles.

## Open Questions & Future Work

- [[hybrid-quantum-attention-scalability-bottleneck]]

## Key Concepts

- [[quantum-adaptive-self-attention]]: A hybrid quantum-classical attention mechanism using variational quantum circuits to construct queries, keys, and values from Pauli-Z expectation vectors.

## Archivist Review

Approved Quantum Adaptive Self-Attention as a reusable hybrid module. The open question was renamed to be more general while preserving the technical bottleneck regarding hybrid quantum-classical scalability. Standard datasets like BTCUSDC were rejected as they are not unique or novel enough for individual registry.

### Approved Concepts
- Quantum Adaptive Self-Attention: Introduces a novel hybrid quantum-classical attention mechanism specifically for financial time-series forecasting.

### Approved Open Questions
- Hybrid Quantum Attention Scalability: Understanding the scaling limits is essential for determining if quantum-enhanced financial modules can transition from experimental prototypes to real-world, high-frequency decentralized finance applications.

### Rejected Candidates
- [open_question] Scalability of Hybrid QASA Modules (`qasa-scalability-latency-limitations`) - duplicate_existing: Renamed to a more canonical slug to reflect the broader mechanism rather than the specific model implementation.

## Links

- [Abstract](https://arxiv.org/abs/2509.16955)
- [PDF](https://arxiv.org/pdf/2509.16955)

