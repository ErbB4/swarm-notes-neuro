---
created_at: '2026-04-23T05:48:38Z'
source_papers:
- '[[openalex-251107385-samsara-a-continuous-time-markov-chain-monte-carlo-sampler-f]]'
title: Optimizing Mutation Proposals and Dynamics
---

**Background:** The convergence efficiency of CTMCMC algorithms is highly dependent on the design of the mutation proposal distributions and the specific dynamics governing transitions between states.

**Question / Future Work:** Investigating adaptive proposal mechanisms—such as jumps in dimension greater than one, HMC-based deterministic drifts, and advanced Gibbs/Collapsed Gibbs samplers—is essential to reduce autocorrelation and scale to complex Bayesian problems.

**Why It Matters:** Improving proposal schemes is critical for the practical scalability of CTMCMC to high-dimensional parameter spaces with unknown dimensionality.