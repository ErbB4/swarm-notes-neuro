---
# CSL-compatible fields
title: "Prediction of chaotic dynamics from data: An introduction"
author:
  - literal: "Luca Magri"
  - literal: "Andrea Nóvoa"
  - literal: "Elise Özalp"
issued:
  date-parts:
    - [2026, 4, 13]
url: "https://arxiv.org/abs/2604.11624"

# Custom fields
paper_id: "2604.11624"
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
processed_at: "2026-04-16T05:47:13Z"
created_at: "2026-04-16T05:47:13Z"
---

# Prediction of chaotic dynamics from data: An introduction

**Authors**: Luca Magri, Andrea Nóvoa, Elise Özalp
**Date**: 2026-04-13
**Paper ID**: [openalex:2604.11624](https://arxiv.org/abs/2604.11624)

## Summary

This paper provides a structured introduction to predicting chaotic dynamical systems using machine learning techniques. It integrates core concepts from chaos theory with state-of-the-art forecasting models, specifically focusing on Reservoir Computing (Echo State Networks) and Recurrent Neural Networks (LSTMs). The authors elucidate these methodologies through analysis of the Lorenz system, offering a conceptual framework for understanding the limitations and performance of data-driven forecasting in chaotic regimes.

## Key Contributions

- Provides a foundational bridge between dynamical systems theory and machine learning for time-series forecasting.
- Evaluates and compares Echo State Networks and LSTM networks in the context of reconstructing and predicting chaotic dynamics.
- Demonstrates pedagogical application of predictive models on the Lorenz system as a prototypical chaotic attractor.

## Open Questions & Future Work

- [[finite-time-finite-amplitude-lyapunov-analysis]]

## Archivist Review

The submitted candidates were reviewed against the strict vault criteria. I have approved the open question regarding finite-time and finite-amplitude stability, as it represents a core, non-trivial limitation in forecasting chaotic systems that persists beyond the scope of this pedagogical overview. No concepts were approved because the models discussed (ESNs, LSTMs) are standard, and the paper's contribution is primarily educational rather than proposing novel, reusable forecasting architectures.

### Approved Open Questions
- Finite-time and finite-amplitude stability: This is a fundamental limitation in applying linear stability theory to nonlinear, practical engineering problems where perturbations are rarely infinitesimal and time windows are inherently finite.

## Links

- [Abstract](https://arxiv.org/abs/2604.11624)
- [PDF](https://arxiv.org/pdf/2604.11624)

