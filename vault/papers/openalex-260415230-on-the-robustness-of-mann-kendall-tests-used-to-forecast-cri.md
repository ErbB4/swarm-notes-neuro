---
# CSL-compatible fields
title: "On the robustness of Mann-Kendall tests used to forecast critical transitions"
author:
  - literal: "Tristan Gamot"
  - literal: "Nils Thibeau--Sutre"
  - literal: "Tom J. M. Van Dooren"
issued:
  date-parts:
    - [2026, 4, 16]
url: "https://arxiv.org/abs/2604.15230"

# Custom fields
paper_id: "2604.15230"
paper_source: "openalex"
domain: "time-series"
tags:
  - "time-series"
  - "statistical-analysis"
  - "forecasting"
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-19T05:44:35Z"
created_at: "2026-04-19T05:44:35Z"
---

# On the robustness of Mann-Kendall tests used to forecast critical transitions

**Authors**: Tristan Gamot, Nils Thibeau--Sutre, Tom J. M. Van Dooren
**Date**: 2026-04-16
**Paper ID**: [openalex:2604.15230](https://arxiv.org/abs/2604.15230)

## Summary

This paper investigates the statistical validity of the Mann-Kendall trend test when applied to the detection of early warning signals (EWS) for critical transitions. By comparing empirical distributions of the Mann-Kendall statistic against the theoretical Gaussian assumptions typically employed, the authors identify systemic mismatches exacerbated by autocorrelation. The study concludes that current practices suffer from inflated type I error rates, rendering standard Mann-Kendall tests unreliable for critical transition forecasting and suggesting the need for more robust alternatives.

## Key Contributions

- Demonstrates that the Gaussian assumption underlying Mann-Kendall trend tests fails in the context of critical transition detection due to induced autocorrelation.
- Provides evidence that mismatches between empirical and theoretical Mann-Kendall distributions lead to significantly inflated type I error rates in early warning signal (EWS) detection.
- Recommends against the usage of standard Mann-Kendall tests for forecasting critical transitions and proposes alternative statistical methodologies.

## Open Questions & Future Work

- [[gaussian-kernel-window-robustness-ews]]
- [[asymptotic-distribution-mann-kendall-ews]]

## Archivist Review

The paper highlights a critical failure in the standard application of Mann-Kendall tests due to induced autocorrelation in early warning signals. I have approved two open questions that directly address the need for either mitigating these artifacts through weighting or re-establishing a valid theoretical foundation for the statistic. I found no concepts that meet the high bar for permanent vault storage, as the main finding is essentially a cautionary note regarding the misuse of an existing statistical method.

### Approved Open Questions
- Gaussian Kernel EWS Robustness: High type I error rates in EWS detection are often driven by autocorrelation artifacts; finding effective mitigation strategies is crucial for reliable forecasting.
- Asymptotic Distribution of Mann-Kendall: Valid theoretical distributions are required to eliminate inflated false-positive rates that currently plague critical transition forecasting when using standard trend tests.

### Rejected Candidates
- [open_question] Gaussian kernel window robustness (`gaussian-kernel-rolling-window-robustness`) - other: Renamed for consistency and clarity.

## Links

- [Abstract](https://arxiv.org/abs/2604.15230)
- [PDF](https://arxiv.org/pdf/2604.15230)

