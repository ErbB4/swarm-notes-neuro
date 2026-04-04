---
# CSL-compatible fields
title: "Modulate-and-Map: Crossmodal Feature Mapping with Cross-View Modulation for 3D Anomaly Detection"
author:
  - literal: "Alex Costanzino"
  - literal: "Pierluigi Zama Ramirez"
  - literal: "Giuseppe Lisanti"
  - literal: "Luigi Di Stefano"
issued:
  date-parts:
    - [2026, 4, 2]
url: "https://arxiv.org/abs/2604.02328"

# Custom fields
paper_id: "2604.02328"
paper_source: "arxiv"
domain: "computer-vision"
tags:
  - "anomaly-detection"
  - "multimodal-learning"
  - "3d-vision"
architectures:
  []
datasets:
  - "SiM3D"
concept_slugs:
  []
dataset_slugs:
  - "sim3d"
skill: "TimeSeriesSkill"
processed_at: "2026-04-04T20:07:16Z"
created_at: "2026-04-04T20:07:16Z"
---

# Modulate-and-Map: Crossmodal Feature Mapping with Cross-View Modulation for 3D Anomaly Detection

**Authors**: Alex Costanzino, Pierluigi Zama Ramirez, Giuseppe Lisanti, Luigi Di Stefano
**Date**: 2026-04-02
**Paper ID**: [arxiv:2604.02328](https://arxiv.org/abs/2604.02328)

## Summary

ModMap is a novel framework for 3D anomaly detection and segmentation that integrates multimodal data across multiple views. By employing crossmodal feature mapping and feature-wise modulation, the method explicitly captures complex view-dependent relationships often overlooked by independent-view approaches. The model also benefits from a specialized cross-view training strategy and a new foundational depth encoder, demonstrating superior performance on the SiM3D benchmark.

## Key Contributions

- Introduced ModMap, a framework that models cross-view and cross-modal relationships through feature-wise modulation for 3D anomaly detection.
- Developed a cross-view training strategy that utilizes all view combinations to enhance multiview anomaly scoring.
- Trained and released a foundational depth encoder optimized for high-resolution industrial 3D data.
- Achieved state-of-the-art performance on the SiM3D benchmark, outperforming existing methods by wide margins.

## Archivist Review

I have applied a restrictive selection policy, rejecting the proposed 'ModMap' framework as it represents a specific system-level architecture rather than a broadly applicable algorithmic concept or primitive. SiM3D is approved as a foundational benchmark for 3D anomaly detection in multiview settings. No open questions were proposed, and none were identified that meet the high threshold for permanent documentation.

### Rejected Candidates
- [concept] ModMap (`modmap`) - paper_local: ModMap is a specific architecture implementation rather than a generalizable algorithmic concept or primitive that is likely to see widespread independent adoption.

## Datasets

- [[sim3d]]

## Links

- [Abstract](https://arxiv.org/abs/2604.02328)
- [PDF](https://arxiv.org/pdf/2604.02328)

