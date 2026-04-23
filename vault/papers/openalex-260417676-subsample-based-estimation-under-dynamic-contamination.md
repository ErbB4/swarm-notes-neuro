---
# CSL-compatible fields
title: "Subsample-based Estimation under Dynamic Contamination"
author:
  - literal: "Yukai Yang"
  - literal: "Rickard Sandberg"
issued:
  date-parts:
    - [2026, 4, 20]
url: "https://arxiv.org/abs/2604.17676"

# Custom fields
paper_id: "2604.17676"
paper_source: "openalex"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "patch-removal-operator"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-23T05:48:30Z"
created_at: "2026-04-23T05:48:30Z"
---

# Subsample-based Estimation under Dynamic Contamination

**Authors**: Yukai Yang, Rickard Sandberg
**Date**: 2026-04-20
**Paper ID**: [openalex:2604.17676](https://arxiv.org/abs/2604.17676)

## Summary

This paper identifies a critical structural failure in standard subsample-based robust estimation when applied to dynamic time series models under contamination. It demonstrates that residuals carry contamination footprints that persist even when corrupted observations are removed, rendering traditional pointwise subsampling inconsistent. The authors introduce a patch removal operator that transforms index sets to account for residual propagation, successfully restoring asymptotic consistency for the uncontaminated parameters.

## Key Contributions

- Proves that standard subsample-based estimation is fundamentally invalid in dynamic time series due to residual contamination propagation.
- Introduces a propagation-compatible index set transformation technique via a 'patch removal operator' to mitigate residual footprints.
- Demonstrates that the proposed approach restores estimator consistency under dynamic contamination where traditional pointwise removal fails.

## Open Questions & Future Work

- [[robust-model-selection-dynamic-contamination]]

## Key Concepts

- [[patch-removal-operator]]: A transformation of index sets in dynamic time series models that removes the lingering residual footprints of contaminated observations to restore estimator consistency.

## Archivist Review

The paper makes a clear, novel contribution by formalizing the failure of standard robust estimation in dynamic settings due to residual propagation. I have approved the 'Patch Removal Operator' as a reusable concept for handling this specific class of time series error, and included the open question regarding robust model selection as a necessary follow-up to this line of inquiry. No datasets were proposed or included in the paper's scope for archival.

### Approved Concepts
- Patch Removal Operator: It provides a formal mechanism to address a fundamental failure mode in time series estimation under dynamic contamination, distinguishing it from simple pointwise outlier removal.

### Approved Open Questions
- Robust Model Selection Under Dynamic Contamination: Standard information criteria are sensitive to contaminated observations; developing theoretically sound criteria that account for the residual structure is essential for reliable model selection in contaminated time series.

## Links

- [Abstract](https://arxiv.org/abs/2604.17676)
- [PDF](https://arxiv.org/pdf/2604.17676)

