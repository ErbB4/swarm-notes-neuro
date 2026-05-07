---
created_at: '2026-05-07T06:04:45Z'
source_papers:
- '[[openalex-260502825-the-bayesian-reflex-online-learning-as-the-autonomic-nervous]]'
title: Online Inference for RGPs
---

**Background:** Recursive Gaussian Processes (RGPs) approximate deep neural networks by placing Gaussian process priors on hidden layers, with inference traditionally performed via batch-mode MCMC.

**Question / Future Work:** Although the RGP architecture is theoretically well-suited for online learning, developing true online inference algorithms—such as scalable particle-based or variational methods that maintain uncertainty quantification while processing streaming data—remains a significant challenge.

**Why It Matters:** Online inference for deep Bayesian models is critical for deploying adaptive AI in dynamic, high-stakes environments where batch retraining is infeasible.