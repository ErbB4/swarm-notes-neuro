---
# CSL-compatible fields
title: "Socio-Conformal Calibration in Complex Survey Data: Marginal Validity Is Not Enough for Subgroup Reliability"
author:
  - literal: "Amir Rafe"
  - literal: "Subasish Das"
issued:
  date-parts:
    - [2026, 5, 7]
url: "https://arxiv.org/abs/2605.05562"

# Custom fields
paper_id: "2605.05562"
paper_source: "openalex"
domain: "nlp"
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
processed_at: "2026-05-10T06:06:10Z"
created_at: "2026-05-10T06:06:10Z"
---

# Socio-Conformal Calibration in Complex Survey Data: Marginal Validity Is Not Enough for Subgroup Reliability

**Authors**: Amir Rafe, Subasish Das
**Date**: 2026-05-07
**Paper ID**: [openalex:2605.05562](https://arxiv.org/abs/2605.05562)

## Summary

This paper investigates the limitation of standard conformal prediction in ensuring subgroup reliability for ordinal forecasting in complex social surveys. Using the Pew American Trends Panel, the authors evaluate split conformal, Mondrian conformal, and a regularized comparator across population subgroups. Results show that nominal marginal validity is insufficient for subgroup fairness and that group-specific calibration methods can ironically degrade both efficiency and fairness in fragmented calibration cells. The study provides a cautionary finding that naive group-specific calibration is not a robust remedy for survey-based uncertainty quantification.

## Key Contributions

- Demonstrates that standard marginal conformal prediction fails to guarantee subgroup reliability in survey-based ordinal forecasting, resulting in weighted subgroup gaps of ~13 percentage points.
- Finds that naive Mondrian (group-specific) conformal calibration exacerbates the fairness-efficiency trade-off in survey data, increasing set sizes without reliably closing subgroup coverage gaps.
- Introduces a regularized Mondrian comparator that shrinks group thresholds toward global quantiles to improve calibration stability, though it fails to yield significant fairness gains in complex survey settings.

## Open Questions & Future Work

- [[survey-weighted-conformal-calibration-fairness]]

## Archivist Review

The paper provides a valuable empirical cautionary tale about the limitations of applying Mondrian conformal prediction in survey-weighted contexts. I approved the open question regarding the interplay between survey weighting and conformal fairness as it highlights a substantial, persistent bottleneck. I rejected the 'Regularized Mondrian Comparator' as a concept because it functions as a local implementation heuristic rather than a foundational framework.

### Approved Open Questions
- Fairness in Survey-Weighted Conformal Prediction: This is technically important because it addresses the core tension between theoretical validity and empirical fairness in machine learning deployments. Identifying whether and how group-specific calibration can be applied safely in small-sample, survey-weighted settings is crucial for AI governance and policy-oriented applications where demographic equity is required.

### Rejected Candidates
- [concept] Regularized Mondrian Comparator (`regularized-mondrian-comparator`) - subcomponent_of_broader_mechanism: This is a specific heuristic comparison technique for conformal prediction rather than a broad, reusable paradigm or mechanism.

## Links

- [Abstract](https://arxiv.org/abs/2605.05562)
- [PDF](https://arxiv.org/pdf/2605.05562)

