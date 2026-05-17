---
created_at: '2026-05-17T06:09:00Z'
source_papers:
- '[[openalex-260514285-forcingdas-unified-and-robust-data-assimilation-via-diffusio]]'
title: Causal-only Smoothing Bottleneck
---

**Background:** Data assimilation systems typically force a choice between online filtering and offline smoothing, and current learned methods struggle with long-horizon error accumulation when observations are non-Markovian.

**Question / Future Work:** Future architectures must enable more direct information flow from future observations to past states (e.g., via bidirectional attention or hybrid backbones) while maintaining the ability to switch between filtering and smoothing regimes at inference time, avoiding the limitations of causal-only backward propagation.

**Why It Matters:** This is a fundamental architectural limitation that restricts the efficacy of information propagation from future observations to past states, which is critical for high-performance smoothing and reanalysis.