---
# CSL-compatible fields
title: "Enabling Federated Inference via Unsupervised Consensus Embedding"
author:
  - literal: "Yui Hashimoto"
  - literal: "Takayuki Nishio"
  - literal: "Yuichi Kitagawa"
  - literal: "Takahito Tanimura"
issued:
  date-parts:
    - [2026, 5, 7]
url: "https://arxiv.org/abs/2605.05718"

# Custom fields
paper_id: "2605.05718"
paper_source: "openalex"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "consensus-embedding-based-federated-inference-ce-fi"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-10T06:05:48Z"
created_at: "2026-05-10T06:05:48Z"
---

# Enabling Federated Inference via Unsupervised Consensus Embedding

**Authors**: Yui Hashimoto, Takayuki Nishio, Yuichi Kitagawa, Takahito Tanimura
**Date**: 2026-05-07
**Paper ID**: [openalex:2605.05718](https://arxiv.org/abs/2605.05718)

## Summary

The paper introduces Consensus Embedding-based Federated Inference (CE-FI), a framework for distributed model cooperation that preserves privacy by avoiding the exchange of raw data or model parameters. CE-FI uses a learned consensus embedding layer to map heterogeneous model outputs into a shared space, trained exclusively on unlabeled data. Empirical results on image classification benchmarks show that CE-FI maintains strong predictive performance under non-IID conditions while relaxing common assumptions required by existing federated inference methods.

## Key Contributions

- Introduces CE-FI, a framework enabling cooperative inference across heterogeneous models without shared parameters, raw data, or encoders.
- Employs a Consensus Embedding (CE) layer to map diverse intermediate representations into a unified space via shared unlabeled data.
- Demonstrates consistent performance gains over solo inference across CIFAR-10 and CIFAR-100 benchmarks under non-IID conditions.

## Open Questions & Future Work

- [[optimizing-ensemble-strategies-for-federated-inference-in-heterogeneous-settings]]
- [[privacy-risks-of-shared-intermediate-representations]]

## Key Concepts

- [[consensus-embedding-based-federated-inference-ce-fi]]: A framework for federated inference that aligns heterogeneous model representations into a common embedding space using unlabeled data.

## Archivist Review

The paper proposes a novel, architecture-agnostic approach to federated inference. I have approved the framework itself as a foundational concept for distributed cooperation and two critical open questions concerning the performance-privacy trade-offs inherent in sharing intermediate latent representations. Standard datasets were rejected as they are routine in the literature.

### Approved Concepts
- Consensus Embedding-based Federated Inference (CE-FI): This is the core contribution of the paper, enabling cooperative inference across heterogeneous models while preserving privacy.

### Approved Open Questions
- Optimizing Ensemble Strategies in Federated Inference: The ensemble strategy is a primary determinant of performance in federated inference settings where individual models exhibit non-IID characteristics.
- Privacy Risks of Shared Representations: Quantifying the privacy leakage risk of intermediate representations is fundamental to the deployment of federated inference in sensitive domains.

## Links

- [Abstract](https://arxiv.org/abs/2605.05718)
- [PDF](https://arxiv.org/pdf/2605.05718)

