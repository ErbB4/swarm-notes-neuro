---
# CSL-compatible fields
title: "Render, Don't Decode: Weight-Space World Models with Latent Structural Disentanglement"
author:
  - literal: "Roussel Desmond Nzoyem"
  - literal: "Mauro Comi"
issued:
  date-parts:
    - [2026, 5, 7]
url: "https://arxiv.org/abs/2605.06298"

# Custom fields
paper_id: "2605.06298"
paper_source: "openalex"
domain: "computer-vision"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "weight-space-world-models"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-10T06:06:03Z"
created_at: "2026-05-10T06:06:03Z"
---

# Render, Don't Decode: Weight-Space World Models with Latent Structural Disentanglement

**Authors**: Roussel Desmond Nzoyem, Mauro Comi
**Date**: 2026-05-07
**Paper ID**: [openalex:2605.06298](https://arxiv.org/abs/2605.06298)

## Summary

NOVA is a world modeling framework that replaces traditional decoder-based architectures with an analytically rendered weight-space representation using coordinate-based implicit neural representations (INRs). By operating directly on model weights rather than latent vectors, the framework achieves high computational efficiency, portability, and zero-shot super-resolution. The approach inherently disentangles complex scene dynamics into structural components like background and foreground, enabling high-fidelity controllable video forecasting.

## Key Contributions

- Introduces NOVA, a world model that encodes state as weights of an implicit neural representation, eliminating the need for heavy decoders.
- Achieves emergent latent disentanglement of scene components like foreground, background, and motion without auxiliary supervision.
- Demonstrates efficient controllable video forecasting on a single consumer GPU at ~40M parameters.

## Key Concepts

- [[weight-space-world-models]]: A world modeling framework that encodes environment states into the weights and biases of coordinate-based implicit neural representations.

## Archivist Review

The proposed 'Weight-Space World Models' concept is highly novel and represents a significant departure from standard latent state modeling in world models, making it a valuable addition to the vault. I rejected 'Latent Structural Disentanglement' because the paper frames it as an emergent capability of the weight-space architecture rather than a distinct, modular, or independently reusable mechanism. I applied a restrictive filter to ensure only the central paradigm shift was captured.

### Approved Concepts
- Weight-Space World Models: This introduces a paradigm shift in world modeling by encoding environment states directly into the parameters of a coordinate-based neural network rather than using traditional latent vector spaces, effectively bypassing the decoder bottleneck.

### Rejected Candidates
- [concept] Latent Structural Disentanglement (`latent-structural-disentanglement`) - subcomponent_of_broader_mechanism: While mentioned as an outcome of the model, it is an emergent property rather than a distinct, standardized architectural mechanism.

## Links

- [Abstract](https://arxiv.org/abs/2605.06298)
- [PDF](https://arxiv.org/pdf/2605.06298)

