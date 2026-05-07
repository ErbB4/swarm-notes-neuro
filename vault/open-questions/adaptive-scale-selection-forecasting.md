---
created_at: '2026-05-07T06:03:37Z'
source_papers:
- '[[openalex-260502689-msmixer-learned-multi-scale-temporal-mixing-with-complementa]]'
title: Adaptive Scale Selection Forecasters
---

**Background:** Multi-scale forecasting architectures often utilize fixed temporal pooling factors to capture varying frequencies. The optimality of these factors can depend on the specific dataset and its dominant periodicities.

**Question / Future Work:** Future work could investigate data-driven methods for dynamically selecting or optimizing the temporal scale factors (down-sampling rates), moving beyond fixed configurations like {1×, 4×, 16×}.

**Why It Matters:** Developing adaptive scale selection mechanisms is crucial for improving model performance on diverse datasets where fixed, heuristic-based down-sampling might not be optimal.