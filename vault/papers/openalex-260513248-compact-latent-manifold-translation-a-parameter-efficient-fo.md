---
# CSL-compatible fields
title: "Compact Latent Manifold Translation: A Parameter-Efficient Foundation Model for Cross-Modal and Cross-Frequency Physiological Signal Synthesis"
author:
  - literal: "Bo Cui"
  - literal: "Xiaowen Song"
  - literal: "Yaowen Zhang"
  - literal: "Shunzhe Zhang"
  - literal: "B. J. F. van Beijnum"
  - literal: "Monique Tabak, Ying Wang"
issued:
  date-parts:
    - [2026, 5, 13]
url: "https://arxiv.org/abs/2605.13248"

# Custom fields
paper_id: "2605.13248"
paper_source: "openalex"
domain: "nlp"
tags:
  - "time-series"
  - "foundation-models"
  - "cross-modal-learning"
  - "signal-processing"
architectures:
  []
datasets:
  []
concept_slugs:
  - "compact-latent-manifold-translation-clmt"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-16T06:03:08Z"
created_at: "2026-05-16T06:03:08Z"
---

# Compact Latent Manifold Translation: A Parameter-Efficient Foundation Model for Cross-Modal and Cross-Frequency Physiological Signal Synthesis

**Authors**: Bo Cui, Xiaowen Song, Yaowen Zhang, Shunzhe Zhang, B. J. F. van Beijnum, Monique Tabak, Ying Wang
**Date**: 2026-05-13
**Paper ID**: [openalex:2605.13248](https://arxiv.org/abs/2605.13248)

## Summary

Compact Latent Manifold Translation (CLMT) is a parameter-efficient (0.09B) foundation model designed for cross-modal and cross-frequency physiological signal synthesis. The framework employs a two-stage paradigm: first, a Universal Tokenizer using Hierarchical Residual Vector Quantization (RVQ) generates discrete latent manifolds to resolve modality entanglement. Second, a Context-Prompted Latent Translator performs signal synthesis as a discrete sequence translation task, significantly reducing computational requirements while outperforming large-scale baselines.

## Key Contributions

- Proposes CLMT, a 0.09B parameter model that achieves state-of-the-art results for PPG-to-ECG synthesis and cross-frequency super-resolution.
- Introduces a Universal Tokenizer using Hierarchical Residual Vector Quantization (RVQ) to isolate and decouple heterogeneous signal latent manifolds.
- Improves clinical R-peak detection F1-score from 0.37 to 0.83 in PPG-to-ECG synthesis and achieves a 0.9956 Pearson correlation in 25Hz to 100Hz super-resolution.

## Open Questions & Future Work

- [[pathology-robustness-in-discrete-quantization]]
- [[reducing-dependency-on-static-prompts]]

## Key Concepts

- [[compact-latent-manifold-translation-clmt]]: A parameter-efficient, two-stage discrete translation framework for cross-modal and cross-frequency physiological signal synthesis.

## Archivist Review

Approved the CLMT framework as a novel approach to discrete signal translation and selected two open questions concerning clinical robustness and conditioning limitations. The review applied a strict filter for clinical applicability, rejecting generic baseline improvement claims and focusing on the core architectural innovations.

### Approved Concepts
- Compact Latent Manifold Translation (CLMT): It is the primary novel architecture/paradigm proposed, framing physiological signal synthesis as a discrete sequence translation task.

### Approved Open Questions
- Robustness to rare pathologies: Addressing this limitation is critical for the clinical reliability of generative physiological models, ensuring they do not suppress or blur life-saving diagnostic information during synthesis.
- Mitigating static-data dependency: Reducing this dependency is essential for deploying these models in real-world, unpredictable clinical settings where comprehensive patient data is not always accessible.

## Links

- [Abstract](https://arxiv.org/abs/2605.13248)
- [PDF](https://arxiv.org/pdf/2605.13248)

