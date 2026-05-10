---
created_at: '2026-05-10T06:03:25Z'
source_papers:
- '[[openalex-260506032-does-synthetic-data-help-empirical-evidence-from-deep-learni]]'
title: Synthetic Data Alignment Challenges
---

**Background:** Foundational time series models are frequently trained on synthetic data at scale to improve zero-shot and few-shot performance, yet the effectiveness of synthetic augmentation for per-dataset fine-tuning remains highly sensitive to model architecture.

**Question / Future Work:** There is a lack of consensus and systematic understanding regarding the optimal strategies for using synthetic data in time series forecasting, particularly concerning which generator types reliably transfer, the ideal quantities for augmentation, and the role of curriculum scheduling in preventing distribution mismatch. Determining how to effectively align synthetic data distributions with diverse target domains remains an unresolved challenge.

**Why It Matters:** Identifying robust methods for synthetic data augmentation is critical for enhancing data-limited forecasting tasks, as the current reliance on trial-and-error often leads to model degradation due to distribution misalignment.