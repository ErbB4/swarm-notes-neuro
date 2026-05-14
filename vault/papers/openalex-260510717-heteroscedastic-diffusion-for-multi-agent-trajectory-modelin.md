---
# CSL-compatible fields
title: "Heteroscedastic Diffusion for Multi-Agent Trajectory Modeling"
author:
  - literal: "Guillem Capellera"
  - literal: "Antonio Rubio"
  - literal: "Luis Ferraz"
  - literal: "Antonio Agudo"
issued:
  date-parts:
    - [2026, 5, 11]
url: "https://arxiv.org/abs/2605.10717"

# Custom fields
paper_id: "2605.10717"
paper_source: "openalex"
domain: "time-series"
tags:
  - "diffusion-models"
  - "trajectory-forecasting"
  - "uncertainty-estimation"
  - "multi-agent-systems"
architectures:
  []
datasets:
  []
concept_slugs:
  - "u2diffine"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-14T06:10:38Z"
created_at: "2026-05-14T06:10:38Z"
---

# Heteroscedastic Diffusion for Multi-Agent Trajectory Modeling

**Authors**: Guillem Capellera, Antonio Rubio, Luis Ferraz, Antonio Agudo
**Date**: 2026-05-11
**Paper ID**: [openalex:2605.10717](https://arxiv.org/abs/2605.10717)

## Summary

This paper introduces U2Diffine, a diffusion-based framework designed to solve both multi-agent trajectory forecasting and completion tasks. The method augments standard denoising objectives with a negative log-likelihood loss for noise, allowing for the propagation of uncertainty to real state space via first-order Taylor approximations. Additionally, the authors provide U2Diff for accelerated sampling and a Rank Neural Network to rank multi-modal outputs by estimated error probability. Experimental results demonstrate state-of-the-art performance across multiple sports trajectory benchmarks.

## Key Contributions

- Introduced U2Diffine, a unified diffusion model for trajectory completion and forecasting that provides state-wise heteroscedastic uncertainty.
- Developed a noise-based NLL loss with first-order Taylor propagation to map latent space uncertainty to the state space.
- Proposed U2Diff for efficient, gradient-free sampling and a RankNN module to estimate error probabilities for multi-modal trajectories.
- Achieved state-of-the-art performance on four sports trajectory datasets (NBA, Basketball-U, Football-U, Soccer-U).

## Open Questions & Future Work

- [[flexible-multi-agent-trajectory-modeling]]

## Key Concepts

- [[u2diffine]]: A diffusion-based framework for multi-agent trajectory completion and forecasting that provides state-wise heteroscedastic uncertainty via latent space uncertainty propagation.

## Archivist Review

I approved U2Diffine as a distinct mechanism for combining diffusion with state-wise uncertainty quantification, and a consolidated open question regarding the need for flexible temporal/spatial trajectory modeling. I rejected the user's initial open question slug because it was redundant with the one I approved. Sports datasets were excluded as they are routine in this domain and lack the uniqueness required for standalone vault entries.

### Approved Concepts
- U2Diffine: It enables unified handling of trajectory completion and forecasting with explicit heteroscedastic uncertainty quantification through diffusion processes.

### Approved Open Questions
- Flexible Multi-Agent Trajectory Modeling: Flexibility in temporal and spatial dimensions is critical for applying trajectory modeling to varying, real-world sports and surveillance scenarios where observation durations and agent counts change dynamically.

### Rejected Candidates
- [open_question] Flexible Multi-Agent Trajectory Modeling (`variable-temporal-spatial-trajectory-modeling`) - duplicate_existing: This is a near-duplicate of the approved open question; the approved version uses a more descriptive and professional slug.

## Links

- [Abstract](https://arxiv.org/abs/2605.10717)
- [PDF](https://arxiv.org/pdf/2605.10717)

