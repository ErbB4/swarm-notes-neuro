---
# CSL-compatible fields
title: "Trajectory-Agnostic Asteroid Detection in TESS with Deep Learning"
author:
  - literal: "Brian P. Powell"
  - literal: "Jorge Martínez-Palomera"
  - literal: "A. Tuson"
  - literal: "Christina Hedges"
  - literal: "Jessie Dotson"
  - literal: "Jordan Caraballo-Vega"
issued:
  date-parts:
    - [2026, 5, 12]
url: "https://arxiv.org/abs/2605.12391"

# Custom fields
paper_id: "2605.12391"
paper_source: "openalex"
domain: "computer-vision"
tags:
  - "computer-vision"
architectures:
  []
datasets:
  []
concept_slugs:
  - "w-net"
  - "adaptive-normalization"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-15T06:16:06Z"
created_at: "2026-05-15T06:16:06Z"
---

# Trajectory-Agnostic Asteroid Detection in TESS with Deep Learning

**Authors**: Brian P. Powell, Jorge Martínez-Palomera, A. Tuson, Christina Hedges, Jessie Dotson, Jordan Caraballo-Vega
**Date**: 2026-05-12
**Paper ID**: [openalex:2605.12391](https://arxiv.org/abs/2605.12391)

## Summary

This paper introduces a trajectory-agnostic method for detecting moving objects in TESS image time-series data using a stacked 3D U-Net architecture termed W-Net. Unlike traditional "shift-and-stack" algorithms that require prior assumptions about object velocity and direction, this approach is robust to varying asteroid trajectories. The model incorporates a novel Adaptive Normalization layer to learn optimal data scaling directly from the inputs. The researchers also released the tess-asteroid-ml repository to support community-wide training for future space surveys.

## Key Contributions

- Introduces W-Net, a stacked 3D U-Net architecture that eliminates the need for explicit trajectory assumptions in asteroid detection.
- Proposes Adaptive Normalization to automatically learn optimal scaling distributions for image time-series.
- Provides the tess-asteroid-ml codebase to facilitate training and benchmarking in moving object detection.

## Open Questions & Future Work

- [[asteroid-label-quality-bottleneck]]

## Key Concepts

- [[w-net]]: A deep learning architecture composed of two stacked 3D U-Nets with skip connections for spatiotemporal feature extraction in image time-series.
- [[adaptive-normalization]]: A learned data scaling technique that allows neural networks to determine the optimal range and distribution for input data processing dynamically.

## Archivist Review

Approved the W-Net architecture and Adaptive Normalization mechanism as both represent reusable methodologies for time-series image processing. The open question regarding label quality in astronomical datasets was approved as a fundamental bottleneck, whereas the request regarding fast-moving objects was rejected as a routine data augmentation task.

### Approved Concepts
- W-Net: Central architecture for spatiotemporal feature extraction in moving object detection.
- Adaptive Normalization: Core technique for automating input data scaling learning, replacing static preprocessing.

### Approved Open Questions
- Moving Object Label Quality Bottleneck: This is a foundational performance bottleneck for supervised learning in astronomical surveys.

### Rejected Candidates
- [open_question] Detecting Fast-Moving Asteroids (`fast-asteroid-detection-bottleneck`) - other: This is a specific training data limitation (synthetic data injection) rather than a fundamental research bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2605.12391)
- [PDF](https://arxiv.org/pdf/2605.12391)

