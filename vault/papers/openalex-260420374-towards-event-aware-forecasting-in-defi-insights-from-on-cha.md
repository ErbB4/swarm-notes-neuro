---
# CSL-compatible fields
title: "Towards Event-Aware Forecasting in DeFi: Insights from On-chain Automated Market Maker Protocols"
author:
  - literal: "Huaiyu Jia"
  - literal: "Jiehshun You"
  - literal: "Yizhi Luo"
  - literal: "Jingyu Liu"
  - literal: "Shuo Sun"
issued:
  date-parts:
    - [2026, 4, 22]
url: "https://arxiv.org/abs/2604.20374"

# Custom fields
paper_id: "2604.20374"
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
  - "uncertainty-weighted-mean-squared-error"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-25T05:38:02Z"
created_at: "2026-04-25T05:38:02Z"
---

# Towards Event-Aware Forecasting in DeFi: Insights from On-chain Automated Market Maker Protocols

**Authors**: Huaiyu Jia, Jiehshun You, Yizhi Luo, Jingyu Liu, Shuo Sun
**Date**: 2026-04-22
**Paper ID**: [openalex:2604.20374](https://arxiv.org/abs/2604.20374)

## Summary

This paper addresses the unique event-driven nature of price discovery in Automated Market Maker (AMM) protocols by analyzing on-chain swap and reserve ratio events. The authors curate a large-scale, fine-grained dataset of 8.9 million events from major protocols and propose an Uncertainty Weighted Mean Squared Error (UWM) loss function for Time-Point Process (TPP) modeling. The UWM loss effectively integrates block interval regression into traditional TPP objectives, significantly improving temporal prediction accuracy while maintaining event classification robustness in DeFi environments.

## Key Contributions

- Constructed a fine-grained dataset of 8.9 million on-chain event records across four major AMM protocols (Pendle, Uniswap v3, Aave, Morpho).
- Proposed the Uncertainty Weighted Mean Squared Error (UWM) loss function to improve time-point process modeling of event-driven DeFi dynamics.
- Demonstrated that UWM reduces time prediction error by 56.41% compared to standard TPP objectives on eight baseline architectures.

## Open Questions & Future Work

- [[event-aware-defi-forecasting-bottleneck]]

## Key Concepts

- [[uncertainty-weighted-mean-squared-error]]: A loss function for Time-Point Processes that integrates block interval regression by weighting uncertainty with homoscedasticity.

## Archivist Review

I approved the Uncertainty Weighted Mean Squared Error loss as a reusable mechanism for TPP modeling, particularly for event-driven time series. I also approved the identified research direction as a bottleneck, ensuring it fits established naming conventions. I rejected the individual protocol datasets as they are components of a single aggregated collection rather than foundational, standalone research benchmarks.

### Approved Concepts
- Uncertainty Weighted Mean Squared Error: This loss function addresses the challenge of predicting discrete on-chain events by balancing event types with precise temporal (block interval) regression.

### Approved Open Questions
- Event-Aware DeFi Forecasting Bottleneck: This is fundamental to moving beyond classical finance paradigms and creating accurate, high-frequency forecasting tools tailored to the unique mechanics of blockchain-native liquidity pools.

### Rejected Candidates
- [open_question] Event-Aware Forecasting in DeFi (`event-aware-defi-forecasting-frameworks`) - other: Renamed to match vault convention as a bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2604.20374)
- [PDF](https://arxiv.org/pdf/2604.20374)

