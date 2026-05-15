---
created_at: '2026-05-15T06:16:19Z'
source_papers:
- '[[openalex-260512241-pretraining-strategies-and-scaling-for-ecg-foundation-models]]'
title: Architectural vs. Scale Dominance in Physiological FMs
---

**Background:** Foundation models for physiological signals, specifically ECGs, rely on self-supervised learning objectives and specific architectural inductive biases for effective representation.

**Question / Future Work:** It remains unclear whether the architectural superiority of structured state space models over transformers observed in ECG foundation models generalizes to more complex, multi-modal, or noisy clinical physiological data. Future research must determine if these benefits hold under different signal regimes or if multi-modal auxiliary supervision is required to surpass the performance of task-specific supervised baselines.

**Why It Matters:** This is a foundational concern for the field of physiological time-series modeling, as it directly impacts the design and scalability of future clinical AI tools. Identifying the limits of architectural superiority and the role of multimodal supervision is essential for moving beyond purely self-supervised ECG foundation models.

**Evidence:** the consistent superiority of the S4 backbone across all five objectives suggests that architectural choice remains the dominant factor, with pretraining strategy playing an important but secondary role.