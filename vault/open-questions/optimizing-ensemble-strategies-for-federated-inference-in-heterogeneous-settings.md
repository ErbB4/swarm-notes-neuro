---
created_at: '2026-05-10T06:05:48Z'
source_papers:
- '[[openalex-260505718-enabling-federated-inference-via-unsupervised-consensus-embe]]'
title: Optimizing Ensemble Strategies in Federated Inference
---

**Background:** Federated inference frameworks allow multiple independent models to collaborate on prediction tasks without sharing raw input data, model parameters, or a common encoder. Despite their potential, these frameworks face significant challenges regarding performance gaps compared to centralized counterparts and optimal strategies for cross-device representation alignment.

**Question / Future Work:** There is a need to close the performance gap between consensus-embedding-based federated inference and idealized cooperative inference, specifically through the development of more accurate, modality-aware ensemble selection mechanisms and confidence estimation techniques. The current reliance on heuristic-based strategies results in sub-optimal aggregation in heterogeneous, non-IID environments, necessitating research into adaptive or learning-based ensemble strategies that can better handle representation discrepancies.

**Why It Matters:** The ensemble strategy is a primary determinant of performance in federated inference settings where individual models exhibit non-IID characteristics.

**Evidence:** the performance of CE-FI is already close to that of the FI-based baselines in many settings, a consistent gap still remains between the practical ensemble strategies and the Proposed w/ Oracle Ensemble setting.