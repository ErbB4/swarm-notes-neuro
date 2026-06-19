---
# CSL-compatible fields
title: "ASTEROID: A Spatiotemporal Information Transformer for Forecasting Multi-Step Time Series of Molecular Dynamics"
author:
  - literal: "Kexin Wu"
  - literal: "Luonan Chen"
  - literal: "Renxiao Wang"
issued:
  date-parts:
    - [2026, 6, 16]
url: "https://arxiv.org/abs/2606.17668"

# Custom fields
paper_id: "2606.17668"
paper_source: "openalex"
domain: "time-series"
tags:
  - "transformer"
  - "spatiotemporal-modeling"
  - "forecasting"
  - "molecular-dynamics"
architectures:
  []
datasets:
  []
concept_slugs:
  - "spatiotemporal-information-sti-transformation"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-06-19T06:46:39Z"
created_at: "2026-06-19T06:46:39Z"
---

# ASTEROID: A Spatiotemporal Information Transformer for Forecasting Multi-Step Time Series of Molecular Dynamics

**Authors**: Kexin Wu, Luonan Chen, Renxiao Wang
**Date**: 2026-06-16
**Paper ID**: [openalex:2606.17668](https://arxiv.org/abs/2606.17668)

## Summary

ASTEROID is a data-driven framework designed to accelerate molecular dynamics (MD) simulations by predicting multi-step atomic coordinates directly. By reformulating MD trajectories as high-dimensional spatiotemporal sequences and incorporating a novel Spatiotemporal Information (STI) Transformation into a Transformer architecture, the model efficiently handles complex multiscale dependencies. It employs a local-global self-attention mechanism for spatial interaction modeling and an encoder-decoder structure for robust temporal forecasting. Evaluation on quantum-mechanics derived molecular datasets confirms that the approach improves prediction accuracy while substantially reducing the computational overhead of traditional simulation methods.

## Key Contributions

- Introduces ASTEROID, a framework that models molecular dynamics trajectories as high-dimensional spatiotemporal sequences, enabling direct multi-step atomic coordinate prediction without iterative integration.
- Implements a local-global self-attention mechanism to capture both short- and long-range spatial interactions in molecular systems.
- Demonstrates superior prediction accuracy and significantly lower computational cost compared to conventional molecular dynamics integration methods on quantum-mechanics derived benchmarks.

## Key Concepts

- [[spatiotemporal-information-sti-transformation]]: A technique for embedding domain-specific spatiotemporal evolution equations directly into the self-attention mechanisms of a Transformer.

## Archivist Review

I approved the STI Transformation as a concept because it represents a specific, reusable architectural design pattern for embedding domain-specific evolution rules into attention-based models. The ASTEROID framework itself was rejected as a local branding choice for an MD application rather than a generalized contribution. No datasets or open questions met the high bar for permanent archival given the paper's focus on a specific domain application.

### Approved Concepts
- Spatiotemporal Information (STI) Transformation: The integration of a physics-derived or domain-specific transformation equation into a Transformer architecture represents a reusable design pattern for spatiotemporal forecasting.

### Rejected Candidates
- [concept] ASTEROID Framework (`asteroid-framework`) - paper_local: This is an application-specific framework name rather than a reusable architectural mechanism.

## Links

- [Abstract](https://arxiv.org/abs/2606.17668)
- [PDF](https://arxiv.org/pdf/2606.17668)

