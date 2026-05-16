---
created_at: '2026-05-16T06:01:46Z'
source_papers:
- '[[openalex-260513816-uncertainty-driven-anomaly-detection-for-psychotic-relapse-u]]'
title: Early Fusion for Relapse Detection
---

**Background:** Early fusion involves integrating multimodal inputs directly within a neural network's architecture to learn joint representations, as opposed to combining outputs from independently trained models. Integrating diverse digital phenotypes like cardiac, motion, and sleep signals via early fusion is a potential avenue to capture complex cross-modal interactions for improved clinical prediction.

**Question / Future Work:** Future work is needed to explore early fusion architectures that jointly model cardiac and time/sleep patterns within a unified Transformer network. This approach seeks to capture deeper cross-modal dependencies that are not fully realized by current late-fusion strategies, potentially enhancing the detection of psychotic relapse in real-world settings.

**Why It Matters:** Current late-fusion methods treat models as independent, potentially missing complex nonlinear interactions between physiological modalities that are vital for early warning detection. Moving to early fusion is technically necessary to advance the state-of-the-art in multi-modal digital phenotyping.