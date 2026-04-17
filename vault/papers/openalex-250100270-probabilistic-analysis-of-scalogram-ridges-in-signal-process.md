---
# CSL-compatible fields
title: "Probabilistic analysis of scalogram ridges in signal processing"
author:
  - literal: "G Liu"
  - literal: "Yuan-Chung Sheu"
  - literal: "Hau‐Tieng Wu"
issued:
  date-parts:
    - [2026, 4, 14]
url: "https://arxiv.org/abs/2501.00270"

# Custom fields
paper_id: "2501.00270"
paper_source: "openalex"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "scalogram-ridges"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-17T05:46:39Z"
created_at: "2026-04-17T05:46:39Z"
---

# Probabilistic analysis of scalogram ridges in signal processing

**Authors**: G Liu, Yuan-Chung Sheu, Hau‐Tieng Wu
**Date**: 2026-04-14
**Paper ID**: [openalex:2501.00270](https://arxiv.org/abs/2501.00270)

## Summary

This paper presents a theoretical analysis of scalogram ridges in nonstationary time series, specifically within the context of the adaptive harmonic model contaminated by stationary Gaussian noise. The authors define these ridges as set-valued random processes and establish their key properties, including uniqueness and upper hemicontinuity. By applying maximal inequalities for complex moduli of nonstationary Gaussian processes, the study derives rigorous bounds on ridge deviations due to noise. These findings provide a formal foundation for the use of scalogram-based signal processing in noisy environments.

## Key Contributions

- Provides a theoretical probabilistic framework for scalogram ridges under the adaptive harmonic model with stationary Gaussian noise.
- Establishes the uniqueness of ridge points at individual time instances and proves the upper hemicontinuity of the ridge random process.
- Derives probabilistic bounds on the deviation between ridges of noisy and clean signals as a function of the signal-to-noise ratio.
- Develops maximal inequalities for the complex modulus of nonstationary Gaussian processes using Borell-TIS inequality and Dudley’s theorem.

## Open Questions & Future Work

- [[spectral-interference-ridge-analysis]]

## Key Concepts

- [[scalogram-ridges]]: A set-valued random process identifying the local maxima of a scalogram along the scale axis to track time-varying instantaneous frequencies in nonstationary signals.

## Archivist Review

I approved 'Scalogram Ridges' as a foundational concept for nonstationary time series because the paper formalizes its properties as a random process, which is a major advancement for the field. I also approved the open question regarding spectral interference, as it identifies a clear theoretical bottleneck for ridge-based signal decomposition. I rejected the maximal inequality candidate because it relies on existing classical results rather than creating a new ML concept.

### Approved Concepts
- Scalogram Ridges: Scalogram ridges are a fundamental tool in nonstationary signal analysis; providing a formal probabilistic foundation makes the method more robust and interpretable for future applications.

### Approved Open Questions
- Spectral Interference in Ridge Analysis: This is a fundamental limitation in time-frequency analysis for complex signals, affecting the reliability of component separation and tracking.

### Rejected Candidates
- [concept] Maximal Inequalities for Nonstationary Gaussian Processes (`maximal-inequalities-nonstationary-gaussian-processes`) - not_novel: These are established mathematical tools (Borell-TIS, Dudley) applied to a specific context, rather than a novel conceptual framework developed by this paper.

## Links

- [Abstract](https://arxiv.org/abs/2501.00270)
- [PDF](https://arxiv.org/pdf/2501.00270)

