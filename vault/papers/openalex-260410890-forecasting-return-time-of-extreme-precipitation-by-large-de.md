---
# CSL-compatible fields
title: "Forecasting Return Time of Extreme Precipitation by Large Deviation Theory"
author:
  - literal: "Haotian Xie"
  - literal: "Haoxian Liu"
  - literal: "Jingfang Fan"
  - literal: "Ying Tang"
issued:
  date-parts:
    - [2026, 4, 13]
url: "https://arxiv.org/abs/2604.10890"

# Custom fields
paper_id: "2604.10890"
paper_source: "openalex"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  - "CMIP6"
concept_slugs:
  []
dataset_slugs:
  - "cmip6"
skill: "TimeSeriesSkill"
processed_at: "2026-04-16T05:46:23Z"
created_at: "2026-04-16T05:46:23Z"
---

# Forecasting Return Time of Extreme Precipitation by Large Deviation Theory

**Authors**: Haotian Xie, Haoxian Liu, Jingfang Fan, Ying Tang
**Date**: 2026-04-13
**Paper ID**: [openalex:2604.10890](https://arxiv.org/abs/2604.10890)

## Summary

This paper presents a large deviation framework to address the forecasting of rare, extreme precipitation events by leveraging the Landau distribution. By enriching sparse historical data samples with the Landau fit, the authors derive more robust rate functions and return time estimates that extend beyond observed historical intensity ranges. The methodology is applied to CMIP6 climate projections, revealing that projected return time curves collapse onto a unified relation that highlights significantly increased lifetime risk for future cohorts.

## Key Contributions

- Introduced a large deviation theory framework for estimating extreme precipitation return times, overcoming limitations of traditional extreme value distributions.
- Demonstrated that the Landau distribution provides superior statistical fit for global extreme precipitation compared to conventional extreme value distributions (93% vs 76% accuracy).
- Established a unified scaling relation for return time curves across different CMIP6 emission scenarios, quantifying the heightened lifetime exposure for 21st-century birth cohorts.

## Open Questions & Future Work

- [[ldt-asymptotic-regime-climate-validation]]

## Archivist Review

I approved CMIP6 as a critical, widely-used climate dataset benchmark. I approved the open question regarding LDT validation in climate systems because it addresses a fundamental methodological challenge in applying physical principles to non-stationary time-series data. I rejected the concept of Landau distribution as it is a specific statistical distribution rather than a novel, reusable ML-specific mechanism, and I rejected the sub-daily modeling question as a routine extension of work rather than a deep unresolved problem.

### Approved Open Questions
- LDT Asymptotic Regime Validation in Climate Systems: This is a fundamental methodological limitation for applying statistical physics principles like LDT to the Earth system. If the LDP asymptotic assumptions are not met, the resulting return time predictions may be systematically biased, affecting climate risk assessment.

### Rejected Candidates
- [open_question] Sub-Daily Extreme Precipitation Modeling (`sub-daily-extreme-precipitation-modeling`) - low_impact: The question describes an extension of an existing method to a finer scale rather than a fundamental unresolved research bottleneck.

## Datasets

- [[cmip6]]

## Links

- [Abstract](https://arxiv.org/abs/2604.10890)
- [PDF](https://arxiv.org/pdf/2604.10890)

