---
created_at: '2026-05-16T06:03:08Z'
source_papers:
- '[[openalex-260513248-compact-latent-manifold-translation-a-parameter-efficient-fo]]'
title: Robustness to rare pathologies
---

**Background:** Physiological signal synthesis models often struggle with atypical arrhythmias or pathologies that fall outside the training distribution, as discrete quantization layers may map these irregular patterns to standard codebook entries.

**Question / Future Work:** There is a need to improve the robustness and generalization of latent manifold quantization models when encountering rare or out-of-distribution pathological cardiac patterns, which currently risk being over-regularized by the discrete codebook.

**Why It Matters:** Addressing this limitation is critical for the clinical reliability of generative physiological models, ensuring they do not suppress or blur life-saving diagnostic information during synthesis.