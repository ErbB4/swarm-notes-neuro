---
# CSL-compatible fields
title: "CycloneMAE: A Scalable Multi-Task Learning Model for Global Tropical Cyclone Probabilistic Forecasting"
author:
  - literal: "Renlong Hang"
  - literal: "Zihao Xu"
  - literal: "Jiuwei Zhao"
  - literal: "Runling Yu"
  - literal: "Leye Cheng"
  - literal: "Qingshan Liu"
issued:
  date-parts:
    - [2026, 4, 14]
url: "https://arxiv.org/abs/2604.12180"

# Custom fields
paper_id: "2604.12180"
paper_source: "openalex"
domain: "time-series"
tags:
  - "time-series-forecasting"
  - "probabilistic-forecasting"
  - "multi-task-learning"
  - "masked-autoencoder"
  - "climate-informatics"
  - "interpretability"
architectures:
  []
datasets:
  []
concept_slugs:
  - "tc-structure-aware-masked-autoencoder"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-17T05:45:59Z"
created_at: "2026-04-17T05:45:59Z"
---

# CycloneMAE: A Scalable Multi-Task Learning Model for Global Tropical Cyclone Probabilistic Forecasting

**Authors**: Renlong Hang, Zihao Xu, Jiuwei Zhao, Runling Yu, Leye Cheng, Qingshan Liu
**Date**: 2026-04-14
**Paper ID**: [openalex:2604.12180](https://arxiv.org/abs/2604.12180)

## Summary

CycloneMAE is a multi-task, structure-aware masked autoencoder designed to address the limitations of traditional NWP models in tropical cyclone forecasting. By integrating a discrete probabilistic gridding mechanism with a pre-train/fine-tune paradigm, the model delivers both deterministic and probabilistic forecasts from multi-modal data. The architecture excels at capturing transferable representations, consistently outperforming leading NWP systems across global ocean basins for various forecasting horizons. Evaluation highlights that the model learns physically interpretable dependencies, focusing on internal core dynamics for short-term predictions and broader environmental conditions for longer-term ones.

## Key Contributions

- Introduces CycloneMAE, a multi-task masked autoencoder model for scalable, probabilistic tropical cyclone forecasting.
- Employs a structure-aware masked autoencoder architecture to learn transferable representations from multi-modal satellite data.
- Achieves superior performance over operational NWP systems in wind/pressure forecasting up to 120 hours and track forecasting up to 24 hours across five global ocean basins.
- Provides physical interpretability through gradient-based attribution, demonstrating distinct attention shifts between internal core structures and external environment factors over different horizons.

## Open Questions & Future Work

- [[long-term-tc-track-forecasting-bottleneck]]

## Key Concepts

- [[tc-structure-aware-masked-autoencoder]]: A masked autoencoder architecture that incorporates domain-specific tropical cyclone structure priors to learn transferable representations for multi-modal forecasting.

## Archivist Review

The review process focused on isolating the contribution of structural inductive biases in representation learning for extreme events and the specific limitation of current deep learning architectures regarding spatial scale in weather forecasting. Other concepts were rejected as they represent standard applications of well-known architectures (like masked autoencoders) or localized performance metrics. I updated the open question to more precisely capture the architectural trade-off between localized high-resolution modeling and global atmospheric sensitivity.

### Approved Concepts
- TC Structure-Aware Masked Autoencoder: Demonstrates a domain-specific adaptation of self-supervised representation learning for spatio-temporal extreme events.

### Approved Open Questions
- Global-Local TC Tracking Bottleneck: This identifies a critical bottleneck for deep learning-based weather forecasting models when moving from localized short-range prediction to long-range synoptic-scale guidance.

### Rejected Candidates
- [open_question] Improving Long-term TC Tracking (`long-term-tc-track-forecasting`) - other: Renamed to better reflect the underlying architectural constraint rather than just the task goal.

## Links

- [Abstract](https://arxiv.org/abs/2604.12180)
- [PDF](https://arxiv.org/pdf/2604.12180)

