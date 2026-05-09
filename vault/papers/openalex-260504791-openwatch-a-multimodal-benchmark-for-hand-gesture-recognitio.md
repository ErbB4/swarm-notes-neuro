---
# CSL-compatible fields
title: "OpenWatch: A Multimodal Benchmark for Hand Gesture Recognition on Smartwatches"
author:
  - literal: "Pietro Bonazzi"
  - literal: "Youssef Ahmed"
  - literal: "Daniel Eckert"
  - literal: "Andrea Ronco"
  - literal: "Junjie Zeng"
  - literal: "Dengxin Dai"
  - literal: "Michele Magno"
issued:
  date-parts:
    - [2026, 5, 6]
url: "https://arxiv.org/abs/2605.04791"

# Custom fields
paper_id: "2605.04791"
paper_source: "openalex"
domain: "nlp"
tags:
  - "time-series-forecasting"
architectures:
  []
datasets:
  - "OpenWatch"
concept_slugs:
  - "mixtoken"
dataset_slugs:
  - "openwatch"
skill: "TimeSeriesSkill"
processed_at: "2026-05-09T05:58:18Z"
created_at: "2026-05-09T05:58:18Z"
---

# OpenWatch: A Multimodal Benchmark for Hand Gesture Recognition on Smartwatches

**Authors**: Pietro Bonazzi, Youssef Ahmed, Daniel Eckert, Andrea Ronco, Junjie Zeng, Dengxin Dai, Michele Magno
**Date**: 2026-05-06
**Paper ID**: [openalex:2605.04791](https://arxiv.org/abs/2605.04791)

## Summary

This paper introduces OpenWatch, a comprehensive multimodal benchmark for smartwatch-based gesture recognition featuring synchronized IMU and PPG signals. The authors evaluate various classification methods and propose two novel techniques: MixToken, a highly efficient mixture-of-experts architecture, and NormWear-Lora, an optimized low-rank adaptation module. The findings demonstrate that PPG integration significantly enhances predictive performance and that specialized task-specific architectures can outperform large-scale foundation models in both accuracy and memory footprint on resource-constrained devices.

## Key Contributions

- Introduced OpenWatch, the first open-access multimodal benchmark for smartwatch gesture recognition containing 10+ hours of synchronized IMU and PPG data from 50 participants.
- Developed MixToken, a mixture-of-experts architecture achieving 90% F1-score with 223k parameters, significantly outperforming fine-tuned foundation models in accuracy and memory efficiency.
- Demonstrated a 12.5% F1-score improvement in gesture recognition by integrating PPG signals with inertial sensing, providing empirical evidence for the predictive value of physiological data.

## Open Questions & Future Work

- [[personalization-wearable-gestures]]

## Key Concepts

- [[mixtoken]]: A task-specific mixture-of-experts architecture that fuses signal-specific filterbank features with cross-channel statistical tokens via learned logit mixing.

## Archivist Review

I approved the 'MixToken' architecture as it introduces a novel way of fusing channel-specific and statistical tokens via logit mixing for efficient time-series classification. I also approved the 'OpenWatch' dataset as it is a foundational, open-access multimodal resource for smartwatch gesture recognition. 'NormWear-Lora' was rejected as it represents a standard application of existing adaptation techniques (LoRA) rather than a novel conceptual contribution. Personalization in wearable gestures was identified as a critical, non-trivial research bottleneck for this domain.

### Approved Concepts
- MixToken: It provides a high-performance, parameter-efficient alternative to fine-tuning large foundation models in resource-constrained wearable edge environments.

### Approved Open Questions
- Personalization in Wearable Gestures: Personalization is essential for balancing system-wide accuracy with user-specific gesture nuances, impacting long-term model robustness and user satisfaction.

### Rejected Candidates
- [concept] NormWear-Lora (`normwear-lora`) - not_novel: This is a specific application of Low-Rank Adaptation (LoRA) to a sensor domain, which is a common pattern rather than a distinct new architectural concept.

## Datasets

- [[openwatch]]

## Links

- [Abstract](https://arxiv.org/abs/2605.04791)
- [PDF](https://arxiv.org/pdf/2605.04791)

