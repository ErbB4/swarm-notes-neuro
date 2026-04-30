---
created_at: '2026-04-30T06:03:15Z'
source_papers:
- '[[openalex-260424587-bayesian-inference-for-hidden-markov-models-under-genuine-mu]]'
title: Optimal swap rate for HMMs
---

**Background:** Optimal swap acceptance rates for parallel tempering algorithms are well-established for specific classes of distributions, but the theoretical optimal rate for hidden Markov models remains undefined.

**Question / Future Work:** The parallel tempering (PT) algorithm relies on an inverse-temperature schedule to facilitate exploration of multimodal posterior distributions. While a swap acceptance rate of 0.234 is often cited as near-optimal for certain high-dimensional problems, determining the specific swap acceptance rate that maximizes mixing efficiency for hidden Markov models (HMMs) is an unresolved theoretical challenge.

**Why It Matters:** Identifying the optimal swap acceptance rate is critical for minimizing computational costs and ensuring efficient exploration of high-dimensional, multimodal posterior distributions in Bayesian HMM inference.