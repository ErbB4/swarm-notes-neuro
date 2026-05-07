---
# CSL-compatible fields
title: "Learning Temporal Patterns in Financial Time Series: A Comparative Study of Quantum LSTM and Quantum Reservoir Computing"
author:
  - literal: "Danyal Maheshwari"
  - literal: "Gerhard Hellstern"
  - literal: "Martin Zaefferer"
  - literal: "Martin Braun"
  - literal: "Tanja Döhler"
issued:
  date-parts:
    - [2026, 5, 4]
url: "https://arxiv.org/abs/2605.02656"

# Custom fields
paper_id: "2605.02656"
paper_source: "openalex"
domain: "time-series"
tags:
  - "time-series"
  - "quantum-machine-learning"
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-07T06:04:08Z"
created_at: "2026-05-07T06:04:08Z"
---

# Learning Temporal Patterns in Financial Time Series: A Comparative Study of Quantum LSTM and Quantum Reservoir Computing

**Authors**: Danyal Maheshwari, Gerhard Hellstern, Martin Zaefferer, Martin Braun, Tanja Döhler
**Date**: 2026-05-04
**Paper ID**: [openalex:2605.02656](https://arxiv.org/abs/2605.02656)

## Summary

This paper presents a comparative study of Quantum Long Short-Term Memory (QLSTM) and Quantum Reservoir Computing (QRC) for financial forecasting. The authors explore the impact of lag structures and amplitude encoding on predictive accuracy under practical qubit constraints. Empirical results demonstrate that quantum-hybrid models reach parity with classical baselines in univariate scenarios and offer performance advantages in complex, multivariate financial datasets.

## Key Contributions

- Evaluates and compares Quantum LSTM (QLSTM) and Quantum Reservoir Computing (QRC) architectures for financial time-series forecasting.
- Demonstrates that QRC and QLSTM can achieve competitive performance with classical benchmarks in univariate settings.
- Shows that quantum-enhanced architectures with amplitude encoding provide performance improvements over classical models in multivariate regimes with correlated inputs.

## Open Questions & Future Work

- [[scalability-and-optimization-of-quantum-recurrent-models]]

## Archivist Review

The paper provides a comparative study of established quantum-hybrid architectures. I have approved the open question regarding the scaling and optimization of these models as it addresses a fundamental bottleneck in the field of quantum time-series forecasting. The proposed concepts (QLSTM and QRC) were rejected as they represent specific model classes rather than reusable mechanisms.

### Approved Open Questions
- Scaling and Optimizing Quantum Recurrent Models: This research is crucial for identifying the practical scalability and utility of quantum-enhanced temporal pattern learning, moving beyond small-scale proofs of concept to real-world deployment in financial or other complex time-series domains.

### Rejected Candidates
- [concept] Quantum Long Short-Term Memory (QLSTM) (`quantum-lstm`) - not_reusable: This is a specific model architecture often discussed in literature rather than a foundational mechanism or abstract concept reusable across various architectures.
- [concept] Quantum Reservoir Computing (QRC) (`quantum-reservoir-computing`) - not_reusable: Similar to QLSTM, this is a class of model architectures rather than a distinct reusable mechanism.

## Links

- [Abstract](https://arxiv.org/abs/2605.02656)
- [PDF](https://arxiv.org/pdf/2605.02656)

