---
# CSL-compatible fields
title: "Feature Anchors for Time-Series Sensor-Based Human Activity Recognition"
author:
  - literal: "Ruijie Yao"
  - literal: "Chenhang Li"
  - literal: "Danyang Zhuo"
  - literal: "Tingjun Chen"
  - literal: "Xiaoyue Ni"
issued:
  date-parts:
    - [2026, 4, 28]
url: "https://arxiv.org/abs/2604.25092"

# Custom fields
paper_id: "2604.25092"
paper_source: "openalex"
domain: "nlp"
tags:
  - "time-series-augmented-generation"
architectures:
  []
datasets:
  []
concept_slugs:
  - "feature-anchors"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-01T06:04:28Z"
created_at: "2026-05-01T06:04:28Z"
---

# Feature Anchors for Time-Series Sensor-Based Human Activity Recognition

**Authors**: Ruijie Yao, Chenhang Li, Danyang Zhuo, Tingjun Chen, Xiaoyue Ni
**Date**: 2026-04-28
**Paper ID**: [openalex:2604.25092](https://arxiv.org/abs/2604.25092)

## Summary

The authors introduce TCNet, a novel architecture for sensor-based Human Activity Recognition (HAR) that treats handcrafted time-series features as 'feature anchors'. By modulating these explicit anchors with scale, bias, and gating parameters derived from raw IMU data, the model retains the interpretability of statistical features while gaining the flexibility of deep learning. Extensive experiments across five benchmarks demonstrate significant performance improvements over existing baselines, confirming that domain-specific anchors enhance representation quality for HAR tasks.

## Key Contributions

- Proposes the Temporal Conditioning Network for Feature Anchors (TCNet), which enables handcrafted time-series features to remain explicit while adapting to neural context.
- Demonstrates state-of-the-art performance improvements on HAR benchmarks, including a 14.6 mF1 point gain on the Daphnet dataset compared to rTsfNet.
- Provides evidence that keeping handcrafted feature semantics visible improves classification accuracy compared to traditional end-to-end latent representation learning.

## Open Questions & Future Work

- [[extending-feature-anchors-to-diverse-modalities-and-sparse-vocabularies]]

## Key Concepts

- [[feature-anchors]]: Handcrafted time-series features modulated by neural context to serve as explicit, adaptable intermediate representations within a deep learning pipeline.

## Archivist Review

The review focused on extracting the core design innovation of "Feature Anchors," which provides a robust methodology for integrating expert-derived features with neural representational learning. The rejected datasets were excluded as they represent standard evaluation benchmarks in the HAR field and do not constitute novel or uniquely critical assets for the vault. The open question was refined to capture the research challenge of generalizability across modalities and computational efficiency.

### Approved Concepts
- Feature Anchors: This central mechanism bridges the gap between interpretable handcrafted features and deep latent representations by maintaining explicit domain semantics while allowing neural adaptation.

### Approved Open Questions
- Expanding Feature Anchor Frameworks: Establishing the universality and efficiency of the anchor-based paradigm across broader sensor modalities and sparsity constraints is crucial for its adoption in real-world, resource-limited deployments.

### Rejected Candidates
- [dataset] USC-HAD (`USC-HAD`) - low_impact: Routine HAR benchmark dataset.
- [dataset] Daphnet (`Daphnet`) - low_impact: Routine HAR benchmark dataset.
- [dataset] MHealth (`MHealth`) - low_impact: Routine HAR benchmark dataset.
- [dataset] PAMAP2 (`PAMAP2`) - low_impact: Routine HAR benchmark dataset.

## Links

- [Abstract](https://arxiv.org/abs/2604.25092)
- [PDF](https://arxiv.org/pdf/2604.25092)

