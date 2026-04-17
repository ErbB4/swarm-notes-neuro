---
# CSL-compatible fields
title: "Forecasting the Past: Gradient-Based Distribution Shift Detection in Trajectory Prediction"
author:
  - literal: "Michele De Vita"
  - literal: "Julian Wiederer"
  - literal: "Vasileios Belagiannis"
issued:
  date-parts:
    - [2026, 4, 14]
url: "https://arxiv.org/abs/2604.12425"

# Custom fields
paper_id: "2604.12425"
paper_source: "openalex"
domain: "time-series"
tags:
  - "time-series"
  - "autonomous-driving"
  - "self-supervised-learning"
  - "distribution-shift-detection"
architectures:
  []
datasets:
  []
concept_slugs:
  - "gradient-based-distribution-shift-detection"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-17T05:46:04Z"
created_at: "2026-04-17T05:46:04Z"
---

# Forecasting the Past: Gradient-Based Distribution Shift Detection in Trajectory Prediction

**Authors**: Michele De Vita, Julian Wiederer, Vasileios Belagiannis
**Date**: 2026-04-14
**Paper ID**: [openalex:2604.12425](https://arxiv.org/abs/2604.12425)

## Summary

This paper addresses the problem of distribution shift in trajectory prediction for autonomous systems, which can lead to hazardous failures. The authors propose a non-intrusive, self-supervised approach that uses a post-hoc decoder to forecast trajectory completion and derives a shift detection score from the L2 norm of the model's loss gradient. This method enables real-time identification of unfamiliar environmental or behavioral conditions without requiring modifications to the original trajectory predictor. Evaluation across the Shifts and Argoverse benchmarks demonstrates consistent performance in identifying shifts and predicting potential collisions in simulated driving scenarios.

## Key Contributions

- Introduces a self-supervised, post-hoc method to detect distributional shifts by training a decoder on trajectory completion tasks.
- Demonstrates that the L2 norm of the decoder's gradient effectively quantifies shift severity without interfering with the primary prediction model.
- Validates efficacy on Shifts and Argoverse datasets and demonstrates utility for early collision detection in motion planning environments.

## Key Concepts

- [[gradient-based-distribution-shift-detection]]: A post-hoc, self-supervised method for detecting distribution shifts by monitoring the gradient norm of a secondary trajectory forecasting task.

## Archivist Review

The proposal was evaluated for its contribution to non-intrusive distribution shift detection. The concept of gradient-based shift detection via a self-supervised auxiliary task is sufficiently novel and generalizable to warrant a note. The suggested datasets were rejected as they are standard benchmarks in the autonomous driving and time-series forecasting domains.

### Approved Concepts
- Gradient-Based Distribution Shift Detection: This technique enables post-hoc, non-intrusive detection of distribution shifts in trajectory models, a critical requirement for safety in autonomous systems.

### Rejected Candidates
- [dataset] Shifts Dataset (`shifts-dataset`) - not_novel: This is a routine benchmark dataset already widely referenced in trajectory prediction literature.
- [dataset] Argoverse Dataset (`argoverse-dataset`) - not_novel: This is a standard, widely-used dataset in the field and does not require a standalone vault entry.

## Links

- [Abstract](https://arxiv.org/abs/2604.12425)
- [PDF](https://arxiv.org/pdf/2604.12425)

