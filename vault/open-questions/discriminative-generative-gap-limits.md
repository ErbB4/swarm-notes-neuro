---
created_at: '2026-05-15T06:16:13Z'
source_papers:
- '[[openalex-260511978-on-predicting-the-post-training-potential-of-pre-trained-llm]]'
title: Discriminative-Generative Capability Gap
---

**Background:** Large language models are developed through a two-stage process of pre-training and alignment, yet base model evaluations often fail to predict post-alignment performance.

**Question / Future Work:** It remains unclear if the discrepancy between a model's discriminative ability—recognizing response quality—and its generative capability—producing fluent, high-quality output—can be fully reconciled. This is particularly critical in open-ended domains where evaluative rubrics are less standardized than in factual reasoning tasks.

**Why It Matters:** This bottleneck highlights the fundamental limitation of using discriminative proxies for generative potential, which could lead to systematic failure in model selection for creative domains.

**Evidence:** It is possible for a “theoretician” model to possess high discriminative intelligence (recognizing the correct response) yet lack the generative motor control to execute it fluently.