---
created_at: '2026-05-08T05:44:30Z'
source_papers:
- '[[openalex-260503723-segmenting-human-llm-co-authored-text-via-change-point-detec]]'
title: Co-authored Text Segmentation Dependency Bottleneck
---

**Background:** Change point detection algorithms typically rely on stationarity assumptions regarding the variability of the underlying signals. In scenarios involving human-LLM co-authored text, individual segments often exhibit heterogeneous detection score variability due to differences in sentence length and model-generated content.

**Question / Future Work:** It remains an open challenge to develop robust segmentation algorithms that maintain minimax optimality when the underlying detection scores are not only heterogeneous in variance but also potentially subject to adversarial perturbations or varying degrees of inter-sentence dependency. Future work is needed to extend the theoretical framework beyond the currently assumed independence of sentence-level detection scores to better reflect real-world co-authoring patterns where context flows across boundaries.

**Why It Matters:** The assumption of independence between sentence-level scores is a simplification that limits the applicability of current change point models in complex, cohesive prose, which is the primary domain of LLM-human co-authoring. Addressing these dependencies is crucial for improving boundary detection accuracy in real-world writing tasks.

**Evidence:** We do not further pursue those directions as the main contribution is to understand the effects of heterogeneous sigma_i on the signal-to-noise condition and localization error.