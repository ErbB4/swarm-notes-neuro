---
# CSL-compatible fields
title: "Does Synthetic Data Help? Empirical Evidence from Deep Learning Time Series Forecasters"
author:
  - literal: "Hugo Cazaux"
  - literal: "Eyjólfur Ingi Ásgeirsson"
  - literal: "Hlynur Stefánsson"
issued:
  date-parts:
    - [2026, 5, 7]
url: "https://arxiv.org/abs/2605.06032"

# Custom fields
paper_id: "2605.06032"
paper_source: "openalex"
domain: "nlp"
tags:
  - "time-series-augmented-generation"
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-10T06:03:25Z"
created_at: "2026-05-10T06:03:25Z"
---

# Does Synthetic Data Help? Empirical Evidence from Deep Learning Time Series Forecasters

**Authors**: Hugo Cazaux, Eyjólfur Ingi Ásgeirsson, Hlynur Stefánsson
**Date**: 2026-05-07
**Paper ID**: [openalex:2605.06032](https://arxiv.org/abs/2605.06032)

## Summary

This paper performs a comprehensive large-scale empirical analysis of synthetic data augmentation in deep learning time series forecasting, covering nine experimental groups and over 4,000 training runs. The study reveals that the efficacy of synthetic data is highly dependent on model architecture, with channel-mixing models showing gains while channel-independent models suffer performance degradation. The findings offer practical guidelines, noting that synthetic augmentation is not a universal panacea and provides specific recommendations for training schedules and data generation strategies.

## Key Contributions

- Large-scale empirical study of 4,218 experimental runs evaluating synthetic time series augmentation across varied architectures and datasets.
- Identification of architecture-conditional performance: channel-mixing models (e.g., TimesNet, iTransformer) typically benefit, while channel-independent models (e.g., DLinear, PatchTST) are consistently degraded.
- Establishment of actionable guidelines: synthetic augmentation generally hurts performance (67% of trials) and requires specific strategies like gradual annealing and avoiding hard curriculum switching to be effective.

## Open Questions & Future Work

- [[synthetic-data-alignment-time-series]]

## Archivist Review

The paper provides an excellent empirical study on the nuances of synthetic data augmentation in time series. I rejected the concept candidate because it is already tracked in the vault. I approved the open question as it captures the fundamental tension identified in the paper: that synthetic augmentation is not a universal performance boost and depends heavily on architecture alignment, which is a major ongoing research challenge. I did not approve any datasets as the paper uses established benchmarks (like Weather) rather than contributing a new, distinct dataset.

### Approved Open Questions
- Synthetic Data Alignment Challenges: Identifying robust methods for synthetic data augmentation is critical for enhancing data-limited forecasting tasks, as the current reliance on trial-and-error often leads to model degradation due to distribution misalignment.

### Rejected Candidates
- [concept] time-series-augmented-generation (`time-series-augmented-generation`) - duplicate_existing: This concept is already present in the vault.

## Links

- [Abstract](https://arxiv.org/abs/2605.06032)
- [PDF](https://arxiv.org/pdf/2605.06032)

