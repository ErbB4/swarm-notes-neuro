---
created_at: '2026-05-09T05:58:40Z'
source_papers:
- '[[openalex-260504793-bilinear-mamba-koopman-neural-mpc-for-varying-dynamics]]'
title: Stability Guarantees for Bilinear MPC
---

**Background:** Bilinear control models often utilize parameters that depend on input controls, necessitating careful management of system stability throughout the operating range.

**Question / Future Work:** While spectral regularization and local MPC trust-region constraints are employed during training and inference to manage stability, there is no formal proof establishing that the spectral radius of the effective drift operator remains strictly less than unity across the entire feasible control space. Developing theoretical guarantees for closed-loop stability of these bilinear Koopman models under control constraints remains an open problem.

**Why It Matters:** This is critical for safety-critical control applications where global or robust stability guarantees are required before deployment.

**Evidence:** Remark 2. The boundedness assumption on iterates is retained as an explicit hypothesis. ... those mechanisms do not by themselves constitute a formal proof that ρ(Aeff(u)) < 1 uniformly for all u ∈ U.