---
# CSL-compatible fields
title: "Calibrating Scientific Foundation Models with Inference-Time Stochastic Attention"
author:
  - literal: "Akash Yadav"
  - literal: "Taiwo A. Adebiyi"
  - literal: "Ruda Zhang"
issued:
  date-parts:
    - [2026, 4, 21]
url: "https://arxiv.org/abs/2604.19530"

# Custom fields
paper_id: "2604.19530"
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
processed_at: "2026-04-24T05:51:23Z"
created_at: "2026-04-24T05:51:23Z"
---

# Calibrating Scientific Foundation Models with Inference-Time Stochastic Attention

**Authors**: Akash Yadav, Taiwo A. Adebiyi, Ruda Zhang
**Date**: 2026-04-21
**Paper ID**: [openalex:2604.19530](https://arxiv.org/abs/2604.19530)

## Summary

The paper addresses the lack of calibrated uncertainty in deterministic Transformer-based scientific foundation models by introducing Stochastic Attention. This inference-time modification randomizes attention weights using normalized multinomial sampling, controlled by a single concentration parameter. By optimizing this parameter to match target distributions, the method produces well-calibrated predictive intervals without the need for extensive retraining. Evaluation on weather and timeseries benchmarks shows that this approach achieves competitive performance while significantly reducing computational overhead compared to retraining-based uncertainty quantification methods.

## Key Contributions

- Introduces Stochastic Attention, a lightweight, inference-time mechanism that replaces standard softmax weights with normalized multinomial samples to generate predictive ensembles.
- Proposes a post-hoc calibration objective for stochastic attention that requires only minutes of tuning, avoiding costly retraining of foundation models.
- Demonstrates superior native calibration and sharper prediction intervals compared to uncertainty-aware baselines on scientific weather and timeseries forecasting tasks.

## Links

- [Abstract](https://arxiv.org/abs/2604.19530)
- [PDF](https://arxiv.org/pdf/2604.19530)

