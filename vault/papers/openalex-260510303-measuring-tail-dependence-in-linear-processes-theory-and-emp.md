---
# CSL-compatible fields
title: "Measuring Tail Dependence in Linear Processes: Theory and Empirics"
author:
  - literal: "Debanjana Datta"
  - literal: "Diganta Mukherjee"
issued:
  date-parts:
    - [2026, 5, 11]
url: "https://arxiv.org/abs/2605.10303"

# Custom fields
paper_id: "2605.10303"
paper_source: "openalex"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-14T06:10:32Z"
created_at: "2026-05-14T06:10:32Z"
---

# Measuring Tail Dependence in Linear Processes: Theory and Empirics

**Authors**: Debanjana Datta, Diganta Mukherjee
**Date**: 2026-05-11
**Paper ID**: [openalex:2605.10303](https://arxiv.org/abs/2605.10303)

## Summary

This paper addresses the limitations of standard Gaussian models in capturing heavy-tailed distributions and extreme co-movements in financial time series. By leveraging copula theory and regular variation, the authors introduce a novel dependence measure designed to characterize joint extreme behavior. The framework is applied to high-frequency cryptocurrency datasets, with particular focus on the role of persistence properties in governing tail dependence.

## Key Contributions

- Proposes a novel dependence measure for capturing joint extremes in linear processes that accounts for both identical and non-identical regularly varying distributions.
- Analyzes the impact of persistence properties on extreme co-movements within financial time series, specifically within the context of high-frequency cryptocurrency data.
- Validates the theoretical findings through extensive simulation studies, demonstrating the measure's efficacy beyond standard Gaussian frameworks.

## Open Questions & Future Work

- [[robust-tail-dependence-measures]]

## Archivist Review

The submission proposes a mathematical dependence measure for extreme values in linear processes, which lacks the broader architectural or procedural reusability required for a permanent ML concept note. The open question regarding the robustness of dependence measures in the face of non-stationary or corrupted tail data remains a relevant and persistent challenge in time-series analysis, and is thus approved.

### Approved Open Questions
- Robust Tail Dependence Measurement: Ensuring the robustness of dependence measures against data contamination is critical for reliable risk management and financial modeling, particularly in extreme scenarios where data quality can be compromised.

### Rejected Candidates
- [concept] Novel Dependence Measure for Linear Processes (`novel-dependence-measure-for-linear-processes`) - not_reusable: The proposal is framed as a mathematical tool for linear processes rather than a broadly reusable machine learning mechanism or inductive bias.

## Links

- [Abstract](https://arxiv.org/abs/2605.10303)
- [PDF](https://arxiv.org/pdf/2605.10303)

