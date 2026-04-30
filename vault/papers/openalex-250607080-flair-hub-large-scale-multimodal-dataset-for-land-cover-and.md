---
# CSL-compatible fields
title: "FLAIR-HUB: Large-scale multimodal dataset for land cover and crop mapping"
author:
  - literal: "Anatol Garioud"
  - literal: "Sébastien Giordano"
  - literal: "Nicolás David"
  - literal: "Nicolas Gonthier"
issued:
  date-parts:
    - [2026, 4, 27]
url: "https://arxiv.org/abs/2506.07080"

# Custom fields
paper_id: "2506.07080"
paper_source: "openalex"
domain: "computer-vision"
tags:
  - "computer-vision"
  - "multimodal-learning"
  - "semantic-segmentation"
  - "remote-sensing"
  - "time-series-analysis"
  - "multitask-learning"
architectures:
  []
datasets:
  - "flair-hub"
concept_slugs:
  []
dataset_slugs:
  - "flair-hub"
skill: "TimeSeriesSkill"
processed_at: "2026-04-30T06:05:45Z"
created_at: "2026-04-30T06:05:45Z"
---

# FLAIR-HUB: Large-scale multimodal dataset for land cover and crop mapping

**Authors**: Anatol Garioud, Sébastien Giordano, Nicolás David, Nicolas Gonthier
**Date**: 2026-04-27
**Paper ID**: [openalex:2506.07080](https://arxiv.org/abs/2506.07080)

## Summary

FLAIR-HUB is a new large-scale, multimodal Earth observation dataset designed to support advanced land cover and crop mapping research. It integrates six distinct sensor modalities, including aerial imagery, SAR, and multi-spectral satellite time series, paired with high-resolution 20cm ground-truth labels. The authors provide comprehensive benchmarks using various deep learning architectures, demonstrating the efficacy of multimodal fusion and multi-task learning for complex classification tasks. The dataset is intended to facilitate progress in both supervised and self-supervised learning for environmental monitoring.

## Key Contributions

- Introduces FLAIR-HUB, a large-scale multimodal Earth observation dataset covering 2528 km² with 20cm resolution annotations across six aligned modalities.
- Establishes extensive baselines for multimodal land cover and crop mapping using state-of-the-art CNN and transformer architectures.
- Demonstrates that integrating six complementary data sources yields peak classification performance of 65.8% mean IoU, highlighting the benefits of multi-sensor fusion.

## Open Questions & Future Work

- [[optimal-multimodal-fusion-architectures]]
- [[multitask-learning-interference-remote-sensing]]

## Archivist Review

I have approved the FLAIR-HUB dataset as a significant new benchmark and retained the two proposed open questions as they effectively characterize systemic bottlenecks in remote sensing multimodal and multitask learning. The FLAIR-HUB concept was rejected as a concept entry because it is more appropriately tracked as a dataset.

### Approved Open Questions
- Optimal Multimodal Fusion Architectures: Understanding optimal fusion mechanisms is critical for maximizing the utility of increasingly complex and multimodal Earth Observation datasets.
- Multitask Learning Interference Management: Efficient multitask learning is essential for deploying unified models for comprehensive environmental monitoring without the computational cost of separate models.

### Rejected Candidates
- [concept] FLAIR-HUB (`flair-hub`) - duplicate_existing: This candidate is a dataset and was moved to approved_datasets.

## Datasets

- [[flair-hub]]

## Links

- [Abstract](https://arxiv.org/abs/2506.07080)
- [PDF](https://arxiv.org/pdf/2506.07080)

