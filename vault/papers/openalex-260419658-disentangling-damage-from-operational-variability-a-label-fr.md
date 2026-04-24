---
# CSL-compatible fields
title: "Disentangling Damage from Operational Variability: A Label-Free Self-Supervised Representation Learning Framework for Output-Only Structural Damage Identification"
author:
  - literal: "Xudong Jian"
  - literal: "Charikleia Stoura"
  - literal: "Simon Scandella"
  - literal: "Eleni Chatzi"
issued:
  date-parts:
    - [2026, 4, 21]
url: "https://arxiv.org/abs/2604.19658"

# Custom fields
paper_id: "2604.19658"
paper_source: "openalex"
domain: "time-series"
tags:
  - "time-series"
  - "self-supervised-learning"
  - "representation-learning"
  - "anomaly-detection"
  - "structural-health-monitoring"
architectures:
  []
datasets:
  []
concept_slugs:
  - "disentangled-representation-learning-damage-identification"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-24T05:52:41Z"
created_at: "2026-04-24T05:52:41Z"
---

# Disentangling Damage from Operational Variability: A Label-Free Self-Supervised Representation Learning Framework for Output-Only Structural Damage Identification

**Authors**: Xudong Jian, Charikleia Stoura, Simon Scandella, Eleni Chatzi
**Date**: 2026-04-21
**Paper ID**: [openalex:2604.19658](https://arxiv.org/abs/2604.19658)

## Summary

This paper introduces a label-free, self-supervised representation learning framework designed to isolate structural damage signals from confounding environmental and operational variability. The proposed model utilizes a dual-latent autoencoder architecture augmented with VICReg for invariance learning and a specific frequency-domain constraint to ensure reconstruction fidelity. By eliminating the need for labeled damage or environmental data, the framework provides a robust method for structural health monitoring that generalizes well across real-world vibration-based assets.

## Key Contributions

- Proposes a self-supervised autoencoder architecture that uses VICReg to disentangle damage-related latent features from operational variability.
- Introduces a frequency-domain constraint to ensure latent space fidelity to input power spectral densities.
- Demonstrates robustness and generalization on real-world vibration datasets (bridge and gearbox) without requiring damage or environmental labels.

## Open Questions & Future Work

- [[robust-temporal-decision-strategies-shm]]

## Key Concepts

- [[disentangled-representation-learning-damage-identification]]: A self-supervised framework using dual-latent autoencoders and invariance regularization to separate damage-related features from operational/environmental noise.

## Archivist Review

I approved the central mechanism of disentangling damage from operational noise as a standalone concept due to its broad applicability in industrial anomaly detection. I also approved the open question regarding sequence-level decision strategies as it represents a critical bridge between local representation learning and system-level monitoring reliability. Other candidates were rejected for being either too generic or performance-oriented rather than mechanism-oriented.

### Approved Concepts
- Disentangled Representation Learning for Damage Identification: It introduces a method to separate physical damage signals from operational noise using VICReg and spectral constraints without requiring labeled data, which is highly reusable in industrial anomaly detection.

### Approved Open Questions
- Robust temporal decision strategies for SHM: This addresses the fundamental reliability gap between local model inference and global structural state assessment in SHM.

### Rejected Candidates
- [concept] Self-Supervised Label-Free Disentangled Representation Learning (`self-supervised-label-free-disentangled-representation-learning`) - other: The title is overly generic; renamed to a more specific and descriptive term for the vault.
- [open_question] Improving weak damage detection (`improving-weak-damage-detection`) - low_impact: This is a performance-based goal (better detection of weak signals) rather than a clear technical bottleneck or mechanism-level research question.

## Links

- [Abstract](https://arxiv.org/abs/2604.19658)
- [PDF](https://arxiv.org/pdf/2604.19658)

