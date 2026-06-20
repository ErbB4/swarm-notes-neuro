---
# CSL-compatible fields
title: "SMART: A Flexible, Interpretable, and Scalable Spatio-temporal Brain Atlas from High-Resolution Imaging Data"
author:
  - literal: "John Kalkhof"
  - literal: "Boris Gutman"
  - literal: "Emile d’Angremont"
  - literal: "Daniel C. Alexander"
  - literal: "Marco Lorenzi"
issued:
  date-parts:
    - [2026, 6, 17]
url: "https://arxiv.org/abs/2606.18753"

# Custom fields
paper_id: "2606.18753"
paper_source: "openalex"
domain: "computer-vision"
tags:
  - "medical-imaging"
  - "time-series-forecasting"
  - "longitudinal-modeling"
  - "spatiotemporal-modeling"
architectures:
  []
datasets:
  []
concept_slugs:
  - "smart-framework"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-06-20T06:33:18Z"
created_at: "2026-06-20T06:33:18Z"
---

# SMART: A Flexible, Interpretable, and Scalable Spatio-temporal Brain Atlas from High-Resolution Imaging Data

**Authors**: John Kalkhof, Boris Gutman, Emile d’Angremont, Daniel C. Alexander, Marco Lorenzi
**Date**: 2026-06-17
**Paper ID**: [openalex:2606.18753](https://arxiv.org/abs/2606.18753)

## Summary

The SMART framework provides a novel approach for constructing spatio-temporal brain atlases from longitudinal high-resolution 3D medical images. By modeling global disease trajectories through region-specific differential equations and personalizing them via multi-scale Neural Cellular Automata, the method addresses existing limitations in interpretability and scalability found in black-box generative models. Evaluated across large longitudinal MRI cohorts including ADNI and OASIS-3, SMART outperforms traditional adversarial and diffusion baselines in both forecasting accuracy and temporal consistency.

## Key Contributions

- Introduced SMART, a spatio-temporal atlas construction framework that decouples global disease dynamics from patient-specific anatomical manifestations using region-specific differential equations.
- Leveraged multi-scale Neural Cellular Automata for dense, scalable diffeomorphic deformation field modeling in high-dimensional medical image longitudinal data.
- Demonstrated state-of-the-art disease progression forecasting accuracy and superior temporal consistency compared to diffusion and adversarial baselines on five large-scale MRI datasets.

## Key Concepts

- [[smart-framework]]: A spatio-temporal brain atlas framework that learns disease progression trajectories using region-specific differential equations and multi-scale Neural Cellular Automata.

## Archivist Review

I approved the SMART framework as a distinct method for longitudinal medical image modeling that separates global disease progression from local patient anatomy. I rejected the Neural Cellular Automata subcomponent because it is an implementation detail of the overarching SMART framework rather than a primary conceptual contribution in its own right. No new open questions or datasets were approved to maintain strict quality and scarcity standards.

### Approved Concepts
- SMART Framework: The framework introduces a novel way to decouple global disease progression dynamics from patient-specific anatomical manifestations in 3D medical imaging.

### Rejected Candidates
- [concept] Multi-scale Neural Cellular Automata for Diffeomorphic Deformation (`neural-cellular-automata-for-diffeomorphic-deformation`) - subcomponent_of_broader_mechanism: This is a specific architectural subcomponent used to implement the broader SMART framework.

## Links

- [Abstract](https://arxiv.org/abs/2606.18753)
- [PDF](https://arxiv.org/pdf/2606.18753)

