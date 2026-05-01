---
# CSL-compatible fields
title: "Observation-Guided Neural Surrogate Learning for Scientific Simulation Emulation: A Single-Gauge Flood-Inundation Proof of Concept"
author:
  - literal: "Marzieh Alireza Mirhoseini"
issued:
  date-parts:
    - [2026, 4, 28]
url: "https://arxiv.org/abs/2604.25890"

# Custom fields
paper_id: "2604.25890"
paper_source: "openalex"
domain: "time-series"
tags:
  - "time-series-augmented-generation"
  - "uncertainty-weighted-mean-squared-error"
architectures:
  []
datasets:
  []
concept_slugs:
  - "observation-guided-neural-surrogate-learning"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-01T06:05:12Z"
created_at: "2026-05-01T06:05:12Z"
---

# Observation-Guided Neural Surrogate Learning for Scientific Simulation Emulation: A Single-Gauge Flood-Inundation Proof of Concept

**Authors**: Marzieh Alireza Mirhoseini
**Date**: 2026-04-28
**Paper ID**: [openalex:2604.25890](https://arxiv.org/abs/2604.25890)

## Summary

This paper presents an observation-guided neural surrogate learning framework to emulate high-resolution hydrodynamic simulations for urban flood-inundation mapping. The approach uses a coarse ensemble Gaussian-process/local analogue (EnsCGP) model to generate initial estimates and uncertainty proxies, which are subsequently refined by a U-Net-ASPP neural corrector. By leveraging sparse point-wise gauge data as a training constraint alongside simulation-derived inputs, the model achieves high accuracy in replicating complex flood dynamics while maintaining consistency with sparse real-world sensor observations.

## Key Contributions

- Introduces an observation-guided surrogate framework that uses single-gauge records to constrain neural emulator training for high-resolution flood mapping.
- Develops a hybrid architecture combining an ensemble Gaussian-process/local analogue (EnsCGP) coarse estimator with a U-Net-ASPP neural corrector.
- Demonstrates R^2 ~ 0.99 and MAE < 0.01m on LISFLOOD-FP simulation benchmarks for urban flood-inundation emulation.

## Open Questions & Future Work

- [[observation-guided-flood-surrogate-validation]]

## Key Concepts

- [[observation-guided-neural-surrogate-learning]]: A framework that uses sparse point-wise observations to guide the training of a neural surrogate model for spatial simulation emulation.

## Archivist Review

I have approved the core methodological concept of observation-guided surrogate learning and the critical open question regarding the validation protocols for such hybrid frameworks. These items address the specific challenge of aligning high-fidelity simulations with sparse, real-world sensor data, a key bottleneck in scientific machine learning. Other potential candidates, such as the specific architecture (EnsCGP) or internal model components, were rejected as they are implementation-specific and represent subcomponents rather than distinct, reusable paradigms.

### Approved Concepts
- Observation-Guided Neural Surrogate Learning: Provides a novel paradigm for bridging sparse real-world sensor data with dense simulation outputs in scientific surrogate modeling.

### Approved Open Questions
- Validation of Observation-Guided Surrogates: Addressing these concerns is crucial to verify that the observation-guided correction improves actual model skill rather than merely overfitting to historical gauge records, and to establish the robustness and scalability of such hybrid modeling architectures for operational applications.

## Links

- [Abstract](https://arxiv.org/abs/2604.25890)
- [PDF](https://arxiv.org/pdf/2604.25890)

