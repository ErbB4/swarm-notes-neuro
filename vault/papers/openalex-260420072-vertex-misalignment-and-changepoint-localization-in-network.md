---
# CSL-compatible fields
title: "Vertex misalignment and changepoint localization in network time series"
author:
  - literal: "Tianyi Chen"
  - literal: "Mohammad Sharifi Kiasari"
  - literal: "Sijing Yu"
  - literal: "Youngser Park"
  - literal: "Avanti Athreya"
  - literal: "Vince Lyzinski"
  - literal: "Carey E. Priebe"
  - literal: "Zachary Lubberts"
issued:
  date-parts:
    - [2026, 4, 22]
url: "https://arxiv.org/abs/2604.20072"

# Custom fields
paper_id: "2604.20072"
paper_source: "openalex"
domain: "time-series"
tags:
  - "time-series"
  - "dynamic-networks"
  - "changepoint-detection"
architectures:
  []
datasets:
  []
concept_slugs:
  - "euclidean-mirrors"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-25T05:37:17Z"
created_at: "2026-04-25T05:37:17Z"
---

# Vertex misalignment and changepoint localization in network time series

**Authors**: Tianyi Chen, Mohammad Sharifi Kiasari, Sijing Yu, Youngser Park, Avanti Athreya, Vince Lyzinski, Carey E. Priebe, Zachary Lubberts
**Date**: 2026-04-22
**Paper ID**: [openalex:2604.20072](https://arxiv.org/abs/2604.20072)

## Summary

This paper investigates how vertex misalignment affects the accuracy of changepoint localization in network time series. Using two illustrative models, the authors examine whether changepoint information is captured by marginal or joint distributions of latent vertex positions. They compare various localization techniques, including average degree statistics and Euclidean mirrors, finding that certain configurations are inherently robust to misalignment while others suffer from uncorrectable localization degradation. The study highlights the necessity of considering the underlying structure of latent information for robust network inference.

## Key Contributions

- Analyzes the impact of vertex misalignment on changepoint localization in dynamic network models.
- Demonstrates that changepoint information can reside in either marginal or joint distributions of latent vertex positions, affecting sensitivity to misalignment.
- Proves that for certain model classes, graph matching and optimal transport fail to correct localization errors caused by vertex misalignment.

## Open Questions & Future Work

- [[network-changepoint-signal-classification]]

## Key Concepts

- [[euclidean-mirrors]]: A procedure for localizing changepoints in network time series by analyzing latent position dynamics.

## Archivist Review

The paper provides a formal analysis of how latent position information (marginal vs joint) interacts with network vertex misalignment. I have approved 'Euclidean mirrors' as a distinct statistical technique and the open question regarding the classification of changepoint signals as it highlights a fundamental bottleneck in robust network time series inference. No datasets were included that met the criteria for a permanent standalone note.

### Approved Concepts
- Euclidean mirrors: Represents a specific, modern statistical procedure for changepoint localization in networks that is compared against baseline methods.

### Approved Open Questions
- Classifying Changepoint Signal Location: This is technically critical because existing changepoint detection methodologies perform significantly differently depending on whether they rely on marginal or joint information. Understanding how to handle intermediate cases is essential for robust inference in real-world applications where the nature of the signal is unknown.

## Links

- [Abstract](https://arxiv.org/abs/2604.20072)
- [PDF](https://arxiv.org/pdf/2604.20072)

