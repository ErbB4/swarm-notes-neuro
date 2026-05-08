---
# CSL-compatible fields
title: "Predicting and controlling nonlinear neuro-mechanical locomotion dynamics"
author:
  - literal: "Alexander E. Cohen"
  - literal: "Jörn Dunkel"
issued:
  date-parts:
    - [2026, 5, 5]
url: "https://arxiv.org/abs/2605.03362"

# Custom fields
paper_id: "2605.03362"
paper_source: "openalex"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "helmholtz-nambu-neuromechanics"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-08T05:44:38Z"
created_at: "2026-05-08T05:44:38Z"
---

# Predicting and controlling nonlinear neuro-mechanical locomotion dynamics

**Authors**: Alexander E. Cohen, Jörn Dunkel
**Date**: 2026-05-05
**Paper ID**: [openalex:2605.03362](https://arxiv.org/abs/2605.03362)

## Summary

This paper introduces a multiscale framework for inferring predictive neuromechanical models from high-dimensional neural and behavioral time-series data. By integrating interpretable spectral mode representations with Helmholtz-Nambu decompositions and Bayesian inference, the model quantitatively links neural activity to locomotion patterns. The efficacy of this approach is demonstrated using experimental data from Caenorhabditis elegans, where the model successfully predicts behaviors and identifies necessary neural activation patterns for locomotion control. This generic methodology offers a scalable solution for modeling complex neuro-mechanical dynamics across diverse biological species.

## Key Contributions

- Introduces an end-to-end theoretical and computational framework for inferring multiscale neuromechanical models from combined neural and locomotion data.
- Employs Helmholtz-Nambu decomposition and spectral mode representations to successfully map neural activity to behavioral outputs in C. elegans.
- Demonstrates the capability to predict neural activation patterns for real-time control of locomotion, providing a foundation for future closed-loop optogenetic experiments.

## Open Questions & Future Work

- [[latent-neuromodulatory-dynamics-modeling]]

## Key Concepts

- [[helmholtz-nambu-neuromechanics]]: A framework for mapping high-dimensional neural time series to behavioral dynamics by using spectral mode representations and Helmholtz-Nambu decompositions.

## Archivist Review

I approved the Helmholtz-Nambu neuromechanics framework as a distinctive, physics-informed approach to temporal decomposition in biological time series. I replaced the original, overly broad open question with a more targeted one focused specifically on the challenge of modeling unobserved latent variables in neuromechanical systems, which is a common and tractable research theme. I rejected the C. elegans dataset as it is a routine, specialized experimental outcome rather than a foundational, reusable benchmark.

### Approved Concepts
- Helmholtz-Nambu decomposition for neuromechanics: It provides a mathematically structured, interpretable decomposition of high-dimensional dynamical systems into divergence-free and curl-free components, which is critical for modeling complex neuromechanical coupling.

### Approved Open Questions
- Modeling Latent Neuromodulatory Dynamics: Understanding these latent influences is a fundamental bottleneck to achieving reliable predictive control in closed-loop biological systems.

### Rejected Candidates
- [open_question] Predictive Neuromechanical Modeling Limits (`predictive-neuromechanical-modeling-limits`) - duplicate_existing: This is a broad and vague summary of challenges rather than a specific, researchable, and trackable bottleneck; it is also highly overlapping with the newly approved question.

## Links

- [Abstract](https://arxiv.org/abs/2605.03362)
- [PDF](https://arxiv.org/pdf/2605.03362)

