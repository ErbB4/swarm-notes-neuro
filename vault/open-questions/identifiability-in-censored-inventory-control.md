---
created_at: '2026-05-17T06:09:16Z'
source_papers:
- '[[openalex-260514840-in-context-learning-for-data-driven-censored-inventory-contr]]'
title: Identifiability under severe censoring
---

**Background:** Censored inventory control problems, such as the repeated newsvendor, involve decision-dependent uncertainty where the learner observes only partially revealed demand data. The fundamental difficulty arises from an identifiability and coverage challenge: policies may never observe demand in certain regions of the latent space, potentially preventing offline-trained models from translating into online performance.

**Question / Future Work:** Future research is required to provide theoretical guarantees translating offline predictive quality to online decision performance under severe censoring without relying on restrictive coverage conditions, specifically addressing how to handle information loss in the tail of demand distributions.

**Why It Matters:** This identifiability challenge is the central bottleneck for deploying offline-meta-learned decision policies in high-stakes operational environments.

**Evidence:** Censoring creates fundamental identifiability and coverage issues: the learner may never see certain regions of the latent space under conservative policies, so offline predictive quality may fail to translate to online decision quality, without additional assumptions.