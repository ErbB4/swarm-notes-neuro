---
# CSL-compatible fields
title: "GeomHerd: A Forward-looking Herding Quantification via Ricci Flow Geometry on Agent Interactive Simulations"
author:
  - literal: "Yang Lake"
  - literal: "Junwei Su"
  - literal: "Jingfeng Zeng"
  - literal: "Wenhao Lu"
  - literal: "Xingzhi Qian"
  - literal: "Weitong Zhang"
  - literal: "Chuan Wu"
  - literal: "Dunhong Jin"
issued:
  date-parts:
    - [2026, 5, 12]
url: "https://arxiv.org/abs/2605.11645"

# Custom fields
paper_id: "2605.11645"
paper_source: "openalex"
domain: "time-series"
tags:
  - "time-series-forecasting"
  - "multi-agent-systems"
  - "financial-forecasting"
  - "graph-neural-networks"
architectures:
  []
datasets:
  []
concept_slugs:
  - "geomherd"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-15T06:15:52Z"
created_at: "2026-05-15T06:15:52Z"
---

# GeomHerd: A Forward-looking Herding Quantification via Ricci Flow Geometry on Agent Interactive Simulations

**Authors**: Yang Lake, Junwei Su, Jingfeng Zeng, Wenhao Lu, Xingzhi Qian, Weitong Zhang, Chuan Wu, Dunhong Jin
**Date**: 2026-05-12
**Paper ID**: [openalex:2605.11645](https://arxiv.org/abs/2605.11645)

## Summary

GeomHerd is a forward-looking framework designed to detect herding behavior in multi-agent financial simulations by analyzing the geometric properties of agent-interaction graphs. Instead of relying on lagging price-correlation statistics, the framework uses discrete Ollivier-Ricci curvature to identify structural topological changes indicating emergent coordination. Experiments on a continuous-spin agent-based substrate demonstrate that the method anticipates herding onset significantly earlier than traditional baselines, with transferability to other agent-driven models.

## Key Contributions

- Introduces GeomHerd, a geometric framework that quantifies herding behavior by calculating discrete Ollivier-Ricci curvature on agent-interaction graphs, enabling forward-looking detection of systemic risk.
- Establishes a mean-field theoretical bridge between the proposed graph-theoretic curvature metric and the classical CSAD (Cross-Sectional Absolute Deviation) herding statistic.
- Demonstrates that GeomHerd identifies herding signals significantly earlier than price-correlation baselines, showing a 272-step lead on the continuous-spin agent-based substrate and 40-step lead on co-firing trajectories.

## Open Questions & Future Work

- [[rigorous-proof-ricci-csad-bridge]]

## Key Concepts

- [[geomherd]]: A geometric framework for quantifying herding and systemic risk by measuring discrete Ollivier-Ricci curvature on agent-interaction graphs.

## Archivist Review

I approved the GeomHerd framework as a novel geometric approach to systemic risk signaling in multi-agent systems, and the open question regarding its theoretical grounding in macroscopic indicators. These represent distinct, reusable contributions to time-series analysis and collective dynamics modeling. No datasets were approved as none were presented as novel benchmarks or research assets beyond standard simulation substrates.

### Approved Concepts
- GeomHerd: Introduces a novel geometric approach to quantifying emergent systemic behavior by measuring Ricci curvature on agent-interaction graphs rather than lagging statistics.

### Approved Open Questions
- Rigorous Proof for Ricci-CSAD Bridge: This theoretical link is essential for anchoring new geometric indicators to established, widely-used financial stability measures, providing formal validity to the interpretation of these new signals within the existing finance literature.

## Links

- [Abstract](https://arxiv.org/abs/2605.11645)
- [PDF](https://arxiv.org/pdf/2605.11645)

