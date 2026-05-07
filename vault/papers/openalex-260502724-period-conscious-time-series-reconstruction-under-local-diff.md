---
# CSL-compatible fields
title: "Period-conscious Time-series Reconstruction under Local Differential Privacy"
author:
  - literal: "Yaxuan Wang"
  - literal: "Tianxin Li"
  - literal: "Enji Liang"
  - literal: "Yue Fu"
  - literal: "Yanran Wang"
issued:
  date-parts:
    - [2026, 5, 4]
url: "https://arxiv.org/abs/2605.02724"

# Custom fields
paper_id: "2605.02724"
paper_source: "openalex"
domain: "time-series"
tags:
  - "time-series"
  - "differential-privacy"
  - "signal-reconstruction"
architectures:
  []
datasets:
  []
concept_slugs:
  - "cpr-framework"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-07T06:03:52Z"
created_at: "2026-05-07T06:03:52Z"
---

# Period-conscious Time-series Reconstruction under Local Differential Privacy

**Authors**: Yaxuan Wang, Tianxin Li, Enji Liang, Yue Fu, Yanran Wang
**Date**: 2026-05-04
**Paper ID**: [openalex:2605.02724](https://arxiv.org/abs/2605.02724)

## Summary

CPR (Cycle and Phase Recovery) is a novel reconstruction framework designed for periodic time-series data subjected to local differential privacy (LDP) noise. By employing multi-scale period probing and multi-consensus selection, the framework effectively suppresses spectral interference and stabilizes phase alignment across cycles. Subsequent EM-based denoising combined with kernel density estimation ensures robust recovery of the underlying signal, particularly under tight privacy budgets. Evaluation confirms that CPR significantly outperforms traditional LDP baselines in maintaining periodic integrity and minimizing reconstruction error.

## Key Contributions

- Introduces CPR, a period-aware reconstruction framework that performs multi-scale period probing and multi-consensus selection to mitigate LDP-induced spectral noise.
- Utilizes phase-matched aggregation and EM-based denoising with kernel density estimation to improve reconstruction quality under strict local differential privacy constraints.
- Demonstrates superior preservation of periodic structures and lower reconstruction error compared to representative LDP baselines in the low-epsilon regime on real-world datasets.

## Open Questions & Future Work

- [[non-stationary-periodic-ldp-reconstruction]]

## Key Concepts

- [[cpr-framework]]: A period-aware reconstruction framework for periodic time series that combines multi-scale period probing with EM-based denoising to mitigate LDP-induced signal corruption.

## Archivist Review

I approved the CPR framework as it provides a distinct, reusable methodology for addressing the intersection of periodic signal processing and local differential privacy. The open question regarding non-stationary periodic signals under LDP was approved as it identifies a clear limitation in current stationary-assumption-based approaches and maps to a substantial technical bottleneck for real-world deployment. No other concepts or datasets were sufficiently novel or central to merit inclusion.

### Approved Concepts
- Cycle and Phase Recovery (CPR): Introduces a method to handle noise-induced spectral interference and phase drift in periodic signals protected by LDP, specifically through multi-scale probing and phase-matched aggregation.

### Approved Open Questions
- Non-stationary Periodic LDP Reconstruction: Addressing non-stationary periodicity is critical for applying these privacy-preserving techniques to real-world multimedia streams, such as audio or heart rate, where temporal dynamics are intrinsic.

## Links

- [Abstract](https://arxiv.org/abs/2605.02724)
- [PDF](https://arxiv.org/pdf/2605.02724)

