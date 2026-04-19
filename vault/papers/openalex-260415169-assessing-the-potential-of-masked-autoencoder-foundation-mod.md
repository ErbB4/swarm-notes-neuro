---
# CSL-compatible fields
title: "Assessing the Potential of Masked Autoencoder Foundation Models in Predicting Downhole Metrics from Surface Drilling Data"
author:
  - literal: "Aleksander Berezowski"
  - literal: "Hassan Hassanzadeh"
  - literal: "Gouri Ginde"
issued:
  date-parts:
    - [2026, 4, 16]
url: "https://arxiv.org/abs/2604.15169"

# Custom fields
paper_id: "2604.15169"
paper_source: "openalex"
domain: "time-series"
tags:
  - "time-series"
  - "forecasting"
  - "self-supervised-learning"
architectures:
  []
datasets:
  []
concept_slugs:
  - "masked-autoencoder-foundation-models"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-19T05:45:02Z"
created_at: "2026-04-19T05:45:02Z"
---

# Assessing the Potential of Masked Autoencoder Foundation Models in Predicting Downhole Metrics from Surface Drilling Data

**Authors**: Aleksander Berezowski, Hassan Hassanzadeh, Gouri Ginde
**Date**: 2026-04-16
**Paper ID**: [openalex:2604.15169](https://arxiv.org/abs/2604.15169)

## Summary

This systematic mapping study evaluates the state of predictive modeling for downhole drilling metrics using surface sensor data. The review highlights that existing drilling analytics are largely reliant on supervised ANN and LSTM architectures, which struggle with limited labeled downhole data. The authors propose that Masked Autoencoder Foundation Models (MAEFMs) represent a significant, untapped opportunity to leverage abundant unlabeled drilling data through self-supervised pre-training to improve generalization and multi-task performance.

## Key Contributions

- Conducted a systematic mapping study of 13 papers (2015-2025) on predicting downhole metrics from surface sensor data.
- Identified a research gap where modern self-supervised foundation models are currently absent in drilling analytics despite the dominance of labeled-data-intensive architectures like LSTMs.
- Established the technical feasibility and strategic advantages of applying self-supervised MAEFMs to cross-well generalization and multi-task learning in drilling operations.

## Key Concepts

- [[masked-autoencoder-foundation-models]]: A class of self-supervised foundation models that leverage masking strategies for representation learning on unlabeled time-series data.

## Archivist Review

The review focused on identifying core technical shifts in industrial time-series forecasting. I approved the concept of 'Masked Autoencoder Foundation Models' as it serves as a robust, reusable paradigm for self-supervised learning in sparse, sensor-heavy contexts like drilling. I rejected the paper itself as a contribution, as literature reviews are not conceptual building blocks for the technical vault.

### Approved Concepts
- Masked Autoencoder Foundation Models (MAEFMs): The paper identifies MAEFMs as a novel, unexplored paradigm for time-series drilling analytics, moving beyond standard ANN/LSTM architectures.

### Rejected Candidates
- [concept] Systematic Mapping Study of Drilling Analytics (`systematic-mapping-study-of-drilling-analytics`) - not_novel: The paper itself is a literature review, not a new architectural contribution or methodological framework for the vault.

## Links

- [Abstract](https://arxiv.org/abs/2604.15169)
- [PDF](https://arxiv.org/pdf/2604.15169)

