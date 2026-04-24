---
created_at: '2026-04-24T05:50:52Z'
source_papers:
- '[[openalex-260419343-scalable-memristive-friendly-reservoir-computing-for-time-se]]'
title: Automated hyperparameter optimization for reservoir computing
---

**Background:** Reservoir computing models, particularly those designed for memristive hardware, rely on fixed internal weights that are highly sensitive to architectural hyperparameters.

**Question / Future Work:** The reliance on manual, trial-and-error hyperparameter tuning in gradient-free architectures constitutes a significant barrier to scaling reservoir models across diverse datasets. Research is required to define systematic, computationally efficient tuning procedures that avoid the overhead of traditional derivative-based optimization.

**Why It Matters:** Without systematic optimization, the performance ceiling of reservoir-based neuromorphic systems remains unpredictable across new problem domains.

**Evidence:** Furthermore, MARS has plenty of hyperparameters and only a few learnable parameters. The hyperparameters are currently selected manually by try-and-error.