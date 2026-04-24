---
# CSL-compatible fields
title: "DyWPE: Signal-Aware Dynamic Wavelet Positional Encoding for Time Series Transformers"
author:
  - literal: "Habib Irani"
  - literal: "Vangelis Metsis"
issued:
  date-parts:
    - [2026, 4, 21]
url: "https://arxiv.org/abs/2509.14640"

# Custom fields
paper_id: "2509.14640"
paper_source: "openalex"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "dynamic-wavelet-positional-encoding"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-24T05:50:35Z"
created_at: "2026-04-24T05:50:35Z"
---

# DyWPE: Signal-Aware Dynamic Wavelet Positional Encoding for Time Series Transformers

**Authors**: Habib Irani, Vangelis Metsis
**Date**: 2026-04-21
**Paper ID**: [openalex:2509.14640](https://arxiv.org/abs/2509.14640)

## Summary

DyWPE proposes a signal-aware positional encoding framework for time series transformers that replaces standard, signal-agnostic index-based encodings with dynamic embeddings derived from the Discrete Wavelet Transform (DWT). By capturing multi-scale non-stationary dynamics, the method addresses a fundamental limitation in applying transformer architectures to complex time-dependent signals. Empirical evaluation across ten datasets shows that DyWPE consistently improves predictive performance, notably on long-range sequences and biomedical data.

## Key Contributions

- Introduces DyWPE, a framework that generates positional embeddings for time series using Discrete Wavelet Transform (DWT) to capture multi-scale non-stationary signal dynamics.
- Demonstrates superior performance over traditional index-based positional encodings across ten diverse time series datasets, particularly in long-sequence and biomedical signal tasks.
- Provides a signal-aware alternative to static positional encoding, effectively bridging the gap between temporal sequence indices and underlying signal characteristics.

## Open Questions & Future Work

- [[adaptive-wavelet-decomposition-levels]]

## Key Concepts

- [[dynamic-wavelet-positional-encoding]]: A positional encoding framework for time series transformers that generates signal-aware embeddings using the Discrete Wavelet Transform.

## Archivist Review

I approved the core architectural concept of signal-aware positional encoding using wavelets because it addresses a fundamental limitation in time-series transformers and is highly reusable. I also approved the open question regarding adaptive wavelet decomposition scaling as it represents a significant, non-trivial bottleneck for making such multi-scale methods robust across diverse datasets. Standard practice was applied to reject generic dataset references and routine evaluation claims.

### Approved Concepts
- Dynamic Wavelet Positional Encoding: It provides a reusable mechanism to inject signal-aware, non-stationary temporal dynamics into transformer architectures, overcoming the limitations of index-only positional encodings.

### Approved Open Questions
- Adaptive Wavelet Decomposition Scaling: Determining the optimal wavelet decomposition depth dynamically would enable more robust and generalized architectures that adapt their hierarchical analysis to the specific complexity of input signals.

## Links

- [Abstract](https://arxiv.org/abs/2509.14640)
- [PDF](https://arxiv.org/pdf/2509.14640)

