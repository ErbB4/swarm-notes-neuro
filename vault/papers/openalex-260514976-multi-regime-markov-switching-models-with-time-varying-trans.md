---
# CSL-compatible fields
title: "Multi-regime Markov-switching models with time-varying transition probabilities: An application to U.S. Treasury yields"
author:
  - literal: "Samuel Modée"
  - literal: "Yushu Li"
  - literal: "Sjur Westgaard"
  - literal: "Stein Andreas Bethuelsen"
issued:
  date-parts:
    - [2026, 5, 14]
url: "https://arxiv.org/abs/2605.14976"

# Custom fields
paper_id: "2605.14976"
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
processed_at: "2026-05-17T06:08:13Z"
created_at: "2026-05-17T06:08:13Z"
---

# Multi-regime Markov-switching models with time-varying transition probabilities: An application to U.S. Treasury yields

**Authors**: Samuel Modée, Yushu Li, Sjur Westgaard, Stein Andreas Bethuelsen
**Date**: 2026-05-14
**Paper ID**: [openalex:2605.14976](https://arxiv.org/abs/2605.14976)

## Summary

This paper examines multi-regime Markov-switching models with time-varying transition probabilities (TVTP), specifically extending the GAS model to K-regime configurations. The authors conduct extensive simulations to evaluate parameter recovery and uncover a fundamental non-identifiability issue concerning the GAS score coefficient. Their empirical application to U.S. Treasury yields highlights that while point forecasting remains robust to model specification, characterizing underlying regime dynamics requires careful treatment of the transition mechanism. They also provide the 'multiregimeTVTP' R package to support implementation and further research.

## Key Contributions

- Extends the two-regime Generalized Autoregressive Score (GAS) model to a K-regime setting with regime-specific means and variances.
- Identifies a critical non-identifiability issue in the GAS score coefficient caused by a ridge in the joint likelihood surface of the variance and the score coefficient.
- Demonstrates through empirical analysis that one-step ahead forecasts are robust to TVTP misspecification, while filtered regime probabilities are highly sensitive.
- Provides an open-source R package 'multiregimeTVTP' for parameter estimation and data simulation in multi-regime TVTP models.

## Open Questions & Future Work

- [[gas-model-identifiability]]

## Archivist Review

I approved the identifiability issue in GAS models because it documents a specific, well-defined mathematical breakdown (likelihood surface ridges) in a popular time-series architecture, which is highly reusable knowledge for practitioners. I rejected the other open question as it was too vague and lacked a specific research direction. No new concepts were approved as the paper describes incremental extensions to known Markov-switching and GAS frameworks.

### Approved Open Questions
- Identifiability in GAS models: Understanding this identifiability issue is crucial for practitioners attempting to use GAS-driven Markov-switching models, as it explains why these models frequently fail to converge or collapse to simpler constant-transition specifications in empirical applications.

### Rejected Candidates
- [open_question] Functional forms in TVTP models (`functional-form-tvtp-impact`) - generic: The proposal is too generic and lacks a specific, testable bottleneck or mechanism to serve as a research-level open question.

## Links

- [Abstract](https://arxiv.org/abs/2605.14976)
- [PDF](https://arxiv.org/pdf/2605.14976)

