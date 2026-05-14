---
created_at: '2026-05-14T06:08:36Z'
source_papers:
- '[[openalex-260510292-leapts-rethinking-time-series-forecasting-as-adaptive-multi]]'
title: Universal Scheduling Forecasting Bottleneck
---

**Background:** Current time series forecasting paradigms rely on either fixed single-pass mappings or iterative generation, which often struggle to adapt to non-stationary dynamics across the prediction horizon.

**Question / Future Work:** There is a need to develop universal, large-scale, pre-trained scheduling models capable of zero-shot forecasting across diverse, unseen scenarios, shifting away from the paradigm of training task-specific models from scratch on individual datasets.

**Why It Matters:** This addresses the bottleneck of domain-specific training and enables better generalization, which is critical for scaling forecasting capabilities to heterogeneous real-world applications.

**Evidence:** To solve this, a promising future direction is to build a large-scale, universal scheduling model. By pre-training on massive and diverse time-series data, we aim to learn general scheduling rules.