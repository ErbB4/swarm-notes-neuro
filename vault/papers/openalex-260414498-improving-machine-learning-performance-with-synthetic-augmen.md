---
# CSL-compatible fields
title: "Improving Machine Learning Performance with Synthetic Augmentation"
author:
  - literal: "Mel Sohm"
  - literal: "Charles Dezons"
  - literal: "Sami Sellami"
  - literal: "Oscar Ninou"
  - literal: "Axel Pinçon"
issued:
  date-parts:
    - [2026, 4, 16]
url: "https://arxiv.org/abs/2604.14498"

# Custom fields
paper_id: "2604.14498"
paper_source: "openalex"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "size-matched-null-augmentation"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-19T05:45:39Z"
created_at: "2026-04-19T05:45:39Z"
---

# Improving Machine Learning Performance with Synthetic Augmentation

**Authors**: Mel Sohm, Charles Dezons, Sami Sellami, Oscar Ninou, Axel Pinçon
**Date**: 2026-04-16
**Paper ID**: [openalex:2604.14498](https://arxiv.org/abs/2604.14498)

## Summary

This paper provides a formal analysis of synthetic data augmentation in financial machine learning, characterizing it as a bias-variance trade-off caused by shifts in the effective training distribution. The authors introduce a size-matched null augmentation method and a non-parametric block permutation test to isolate informational benefits from mere sample-size increases. Empirical evaluation across diverse generative models and financial datasets reveals that synthetic augmentation is beneficial in variance-dominant regimes but harmful in bias-dominant scenarios, highlighting the risks of distributional distortion.

## Key Contributions

- Formalizes synthetic augmentation as a modification of the effective training distribution, identifying a structural bias-variance trade-off.
- Introduces a size-matched null augmentation and a block permutation test to isolate genuine informational gains from mechanical sample-size effects.
- Demonstrates that synthetic data improves performance only in variance-dominant regimes (e.g., volatility forecasting) but degrades it in bias-dominant tasks (e.g., directional prediction).

## Open Questions & Future Work

- [[reconciling-targeted-augmentation-inference]]

## Key Concepts

- [[size-matched-null-augmentation]]: A controlled augmentation technique designed to decouple sample-size effects from the informational content of synthetic data.

## Archivist Review

I approved one concept and one open question. The concept 'Size-Matched Null Augmentation' offers a reusable, rigorous method for isolating informational gains from mere sample-size expansion in synthetic data contexts. The open question regarding the reconciliation of targeted augmentation with standard inference addresses a fundamental conflict between improving model performance on rare regimes and the validity of current evaluation frameworks, which is a significant bottleneck in financial ML.

### Approved Concepts
- Size-Matched Null Augmentation: Provides a methodological baseline to isolate informational gains from purely numerical sample-size increases in synthetic data generation.

### Approved Open Questions
- Reconciling Targeted Augmentation Inference: This is a critical methodological gap: if practitioners rely on standard unconditional significance tests to evaluate augmentation quality, they may discard generators that genuinely help rare-event detection simply because those generators shift the data distribution. Addressing this is essential for valid financial model development.

## Links

- [Abstract](https://arxiv.org/abs/2604.14498)
- [PDF](https://arxiv.org/pdf/2604.14498)

