---
created_at: '2026-04-18T05:35:00Z'
source_papers:
- '[[openalex-260413414-minimax-optimality-and-spectral-routing-for-majority-vote-en]]'
title: Finite-width RL ensemble covariance
---

**Background:** Deep reinforcement learning often employs ensembles to estimate uncertainty, typically using uniform sampling from a correlated replay buffer. Training base learners on correlated data leads to ensemble members that are not independent, which diminishes the effectiveness of variance reduction techniques.

**Question / Future Work:** The problem of formalizing the covariance limits for finite-width deep neural networks with dynamically moving targets, particularly in settings that do not rely on Neural Tangent Kernel (NTK) simplifications, remains unresolved. Future work is required to establish whether the identified bootstrap covariance mechanisms and the benefits of dependency-aware routing persist in these general finite-width scenarios.

**Why It Matters:** This is a central limitation for applying the theoretical results to practical deep RL, as the current proof relies on NTK to bridge the gap between simple linear models and complex neural networks. Extending this would provide a more robust theoretical foundation for ensemble methods in deep learning.

**Evidence:** Formalizing the covariance limits for finite-width networks with dynamically moving targets, without NTK simplifications, remains open.