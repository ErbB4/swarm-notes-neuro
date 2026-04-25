---
# CSL-compatible fields
title: "Unlocking the Forecasting Economy: A Suite of Datasets for the Full Lifecycle of Prediction Market: [Experiments & Analysis]"
author:
  - literal: "Huaiyu Jia"
  - literal: "Luofeng Zhou"
  - literal: "Wentao Zhang"
  - literal: "Lin William Cong"
  - literal: "Siguang Li"
  - literal: "Shuo Sun"
issued:
  date-parts:
    - [2026, 4, 22]
url: "https://arxiv.org/abs/2604.20421"

# Custom fields
paper_id: "2604.20421"
paper_source: "openalex"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  - "polymarket-lifecycle-dataset"
concept_slugs:
  []
dataset_slugs:
  - "polymarket-lifecycle-dataset"
skill: "TimeSeriesSkill"
processed_at: "2026-04-25T05:38:06Z"
created_at: "2026-04-25T05:38:06Z"
---

# Unlocking the Forecasting Economy: A Suite of Datasets for the Full Lifecycle of Prediction Market: [Experiments & Analysis]

**Authors**: Huaiyu Jia, Luofeng Zhou, Wentao Zhang, Lin William Cong, Siguang Li, Shuo Sun
**Date**: 2026-04-22
**Paper ID**: [openalex:2604.20421](https://arxiv.org/abs/2604.20421)

## Summary

This paper introduces a comprehensive, unified dataset suite for decentralized prediction markets, addressing the fragmentation of data across on-chain and off-chain sources. By integrating market metadata, high-granularity trading records, and oracle-resolution events, the authors provide a structured foundation for analyzing collective belief signals. The system supports reproducibility and extensibility, facilitating downstream research in event prediction, market calibration, and expectation reconstruction.

## Key Contributions

- Introduces the first continuously maintained, unified dataset suite for the full lifecycle of decentralized prediction markets (Polymarket), covering October 2020 to March 2026.
- Develops a cross-source relational data system that integrates heterogeneous on-chain and off-chain data through identifier resolution and incremental synchronization.
- Demonstrates the dataset's utility for time-series forecasting and analytical tasks via NBA outcome calibration and CPI expectation reconstruction case studies.

## Open Questions & Future Work

- [[oracle-risk-market-behavior]]

## Archivist Review

The paper focuses on the construction and utility of a large-scale, heterogeneous dataset for prediction markets. I have approved the dataset as a reusable resource for time-series and market research, and the open question regarding oracle risk as it presents a distinct, researchable problem in market dynamics. No novel algorithmic concepts were identified that transcend the domain-specific data collection effort.

### Approved Open Questions
- Trading under oracle risk: Understanding oracle-risk market dynamics is critical for the robustness of decentralized oracle designs and for preventing information distortion in markets that depend on external settlement.

## Datasets

- [[polymarket-lifecycle-dataset]]

## Links

- [Abstract](https://arxiv.org/abs/2604.20421)
- [PDF](https://arxiv.org/pdf/2604.20421)

