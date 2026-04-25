---
# CSL-compatible fields
title: "Physics-Enhanced Deep Learning for Proactive Thermal Runaway Forecasting in Li-Ion Batteries"
author:
  - literal: "Salman Khan"
  - literal: "Muhammad Zunair Zamir"
  - literal: "Syed Sajid Ullah"
  - literal: "Jie Li"
issued:
  date-parts:
    - [2026, 4, 22]
url: "https://arxiv.org/abs/2604.20175"

# Custom fields
paper_id: "2604.20175"
paper_source: "openalex"
domain: "time-series"
tags:
  - "time-series"
  - "forecasting"
  - "deep-learning"
architectures:
  []
datasets:
  []
concept_slugs:
  - "physics-informed-lstm"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-25T05:37:51Z"
created_at: "2026-04-25T05:37:51Z"
---

# Physics-Enhanced Deep Learning for Proactive Thermal Runaway Forecasting in Li-Ion Batteries

**Authors**: Salman Khan, Muhammad Zunair Zamir, Syed Sajid Ullah, Jie Li
**Date**: 2026-04-22
**Paper ID**: [openalex:2604.20175](https://arxiv.org/abs/2604.20175)

## Summary

This paper introduces a Physics-Informed Long Short-Term Memory (PI-LSTM) framework designed to predict thermal runaway in Li-ion batteries by integrating heat transfer equations directly into the training process. By adding a physics-based regularization term to the loss function, the model ensures temperature predictions remain thermodynamically consistent while maintaining the temporal modeling capabilities of LSTMs. Extensive evaluation on thirteen datasets confirms that PI-LSTM significantly outperforms standard data-driven baselines in both forecasting accuracy and physical validity.

## Key Contributions

- Proposed the Physics-Informed Long Short-Term Memory (PI-LSTM) framework to enforce thermodynamic constraints in battery temperature forecasting.
- Demonstrated that PI-LSTM achieves an 81.9% RMSE and 81.3% MAE reduction compared to standard LSTM models across thirteen battery datasets.
- Showed that physics-based regularization eliminates non-physical temperature oscillations common in pure data-driven approaches.

## Open Questions & Future Work

- [[multidimensional-hybrid-thermal-forecasting-bottleneck]]

## Key Concepts

- [[physics-informed-lstm]]: A recurrent neural network architecture that incorporates governing differential equations as a regularization term in its loss function to enforce physical consistency in sequence forecasting.

## Archivist Review

The paper proposes a standard and reusable approach to embedding physical constraints into recurrent neural network losses for time-series forecasting. The core contribution is approved as a concept because it represents a recurring pattern in scientific machine learning, while the open question regarding multi-physics coupling is maintained as a significant bottleneck in physical system modeling. No new datasets were approved as the paper utilizes aggregate, unnamed battery datasets.

### Approved Concepts
- Physics-Informed Long Short-Term Memory: It addresses the fundamental conflict between black-box deep learning accuracy and the necessity of thermodynamic consistency in critical infrastructure monitoring.

### Approved Open Questions
- Multidimensional hybrid thermal forecasting: Moving beyond 1D thermal constraints to multi-physics coupling is a non-trivial challenge for deploying robust, interpretable forecasting models in physical infrastructure.

## Links

- [Abstract](https://arxiv.org/abs/2604.20175)
- [PDF](https://arxiv.org/pdf/2604.20175)

