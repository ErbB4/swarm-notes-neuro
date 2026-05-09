---
# CSL-compatible fields
title: "Bilinear Mamba-Koopman Neural MPC for Varying Dynamics"
author:
  - literal: "Matan Pagi"
  - literal: "Zohar Sorek"
issued:
  date-parts:
    - [2026, 5, 6]
url: "https://arxiv.org/abs/2605.04793"

# Custom fields
paper_id: "2605.04793"
paper_source: "openalex"
domain: "time-series"
tags:
  - "time-series-forecasting"
  - "neural-mpc"
  - "koopman-theory"
  - "control-systems"
architectures:
  []
datasets:
  []
concept_slugs:
  - "bilinear-mamba-koopman-neural-mpc"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-09T05:58:40Z"
created_at: "2026-05-09T05:58:40Z"
---

# Bilinear Mamba-Koopman Neural MPC for Varying Dynamics

**Authors**: Matan Pagi, Zohar Sorek
**Date**: 2026-05-06
**Paper ID**: [openalex:2605.04793](https://arxiv.org/abs/2605.04793)

## Summary

This paper addresses the limitation of conditional independence in standard Koopman-based neural MPC by introducing a Bilinear Mamba-Koopman model. By incorporating control-dependent coupling in the latent dynamics, the model allows for adaptive system operators while maintaining the convexity required for efficient Sequential Convex Programming (SCP). Empirical results on CartPole and RSCP benchmarks demonstrate that this approach improves forecasting accuracy and provides significantly greater robustness under time-varying dynamics and stale-plan execution.

## Key Contributions

- Proposes a Bilinear Mamba-Koopman Neural MPC that introduces control-dependent coupling to the latent dynamics, allowing for adaptive system operators.
- Maintains efficiency by adding less than 1% parameters via a low-rank structure while ensuring the existence of exact model Jacobians for Sequential Convex Programming.
- Demonstrates improved robustness and forecasting accuracy on CartPole and RSCP benchmarks under time-varying conditions, specifically showing graceful degradation during delayed re-planning.

## Open Questions & Future Work

- [[stability-guarantees-bilinear-koopman-control]]

## Key Concepts

- [[bilinear-mamba-koopman-neural-mpc]]: A neural MPC framework that incorporates control-dependent latent dynamics into the Koopman structure to improve adaptability in time-varying regimes.

## Archivist Review

I approved the Bilinear Mamba-Koopman Neural MPC concept as it provides a reusable extension to Koopman-based forecasting and control. I also approved the open question regarding stability guarantees for bilinear models, as this is a fundamental theoretical challenge for safety-critical neural MPC. I rejected the proposed benchmarking question as it is a localized critique of existing experiment design rather than a long-standing, cross-paper field bottleneck. I did not approve any datasets, as CartPole and RSCP are standard control environment families rather than specific contributions of this work.

### Approved Concepts
- Bilinear Mamba-Koopman Neural MPC: Introduces control-dependent coupling into Koopman operator-based neural MPC to overcome conditional independence constraints, enabling better adaptation to time-varying dynamics.

### Approved Open Questions
- Stability Guarantees for Bilinear MPC: This is critical for safety-critical control applications where global or robust stability guarantees are required before deployment.

### Rejected Candidates
- [open_question] Benchmarking Control-State Coupling Separation (`benchmarking-control-state-coupling-versus-parameter-drift`) - low_impact: The problem of benchmarking specific model components is often too specific to the evaluation workflow of a single paper rather than representing a general fundamental bottleneck in the field.

## Links

- [Abstract](https://arxiv.org/abs/2605.04793)
- [PDF](https://arxiv.org/pdf/2605.04793)

