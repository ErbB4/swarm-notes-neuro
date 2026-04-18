---
# CSL-compatible fields
title: "Irregularly Sampled Time Series Interpolation for Binary Evolution Simulations Using Dynamic Time Warping"
author:
  - literal: "Ugur Demir"
  - literal: "Philipp M. Srivastava"
  - literal: "Aggelos Katsaggelos"
  - literal: "Vicky Kalogera"
  - literal: "S. Tapia"
  - literal: "Manuel Ballester"
  - literal: "Shamal Lalvani"
  - literal: "Patrick Koller"
  - literal: "Jeff J. Andrews"
  - literal: "Seth Gossage"
  - literal: "Max M. Briel"
  - literal: "Elizabeth Teng"
issued:
  date-parts:
    - [2026, 4, 15]
url: "https://arxiv.org/abs/2604.13604"

# Custom fields
paper_id: "2604.13604"
paper_source: "openalex"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "dtw-multi-parameter-alignment"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-18T05:34:41Z"
created_at: "2026-04-18T05:34:41Z"
---

# Irregularly Sampled Time Series Interpolation for Binary Evolution Simulations Using Dynamic Time Warping

**Authors**: Ugur Demir, Philipp M. Srivastava, Aggelos Katsaggelos, Vicky Kalogera, S. Tapia, Manuel Ballester, Shamal Lalvani, Patrick Koller, Jeff J. Andrews, Seth Gossage, Max M. Briel, Elizabeth Teng
**Date**: 2026-04-15
**Paper ID**: [openalex:2604.13604](https://arxiv.org/abs/2604.13604)

## Summary

Binary stellar evolution simulations are computationally expensive, necessitating efficient interpolation for stellar population synthesis. This paper introduces a novel approach for interpolating irregularly sampled binary stellar tracks using Dynamic Time Warping to perform track alignment and iterative averaging. By computing a shared warping path across physical parameters, the method preserves causal relationships and essential physical laws. The proposed technique significantly outperforms traditional interpolation methods, offering a more efficient way to generate accurate binary population samples for astrophysical research.

## Key Contributions

- Proposes a novel track alignment and iterative averaging method using Dynamic Time Warping to handle irregularities and discontinuities in binary evolution simulation data.
- Enables the generation of accurate binary population samples by computing a shared warping path that maintains essential physical relationships like the Stefan-Boltzmann law.
- Demonstrates consistent performance improvements over traditional linear interpolation baselines across multiple binary configuration datasets.

## Open Questions & Future Work

- [[adaptive-neighbor-selection-interpolation]]

## Key Concepts

- [[dtw-multi-parameter-alignment]]: A method for aligning irregularly sampled, multi-parameter time series by computing a shared warping path across all variables to preserve internal correlations and physical laws during averaging.

## Archivist Review

The approved concept generalizes the alignment technique to emphasize its utility across multi-parameter physical systems rather than just the stellar evolution domain. The approved open question addresses the structural limitation of static neighbor selection in interpolation tasks, which is a common bottleneck in scientific machine learning for physical emulators.

### Approved Concepts
- Dynamic Time Warping for Multi-Parameter Alignment: It provides a principled way to interpolate across high-dimensional, irregularly sampled trajectories where temporal consistency is critical to preserving causal physics, offering a robust alternative to standard time-agnostic interpolation.

### Approved Open Questions
- Morphology-Aware Neighbor Selection: This is a fundamental limitation in surrogate modeling and emulation for expensive scientific simulations, where sparse data often forces the inclusion of unrepresentative 'neighboring' samples.

### Rejected Candidates
- [concept] Dynamic Time Warping for Stellar Track Alignment (`dynamic-time-warping-stellar-track-alignment`) - other: Renamed and generalized to focus on the multi-parameter alignment mechanism rather than the specific application (stellar evolution).

## Links

- [Abstract](https://arxiv.org/abs/2604.13604)
- [PDF](https://arxiv.org/pdf/2604.13604)

