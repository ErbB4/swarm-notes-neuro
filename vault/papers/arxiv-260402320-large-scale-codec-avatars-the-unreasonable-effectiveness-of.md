---
# CSL-compatible fields
title: "Large-scale Codec Avatars: The Unreasonable Effectiveness of Large-scale Avatar Pretraining"
author:
  - literal: "Junxuan Li"
  - literal: "Rawal Khirodkar"
  - literal: "Chengan He"
  - literal: "Zhongshi Jiang"
  - literal: "Giljoo Nam"
  - literal: "Lingchen Yang"
  - literal: "Jihyun Lee"
  - literal: "Egor Zakharov"
  - literal: "Zhaoen Su"
  - literal: "Rinat Abdrashitov"
  - literal: "Yuan Dong"
  - literal: "Julieta Martinez"
  - literal: "Kai Li"
  - literal: "Qingyang Tan"
  - literal: "Takaaki Shiratori"
  - literal: "Matthew Hu"
  - literal: "Peihong Guo"
  - literal: "Xuhua Huang"
  - literal: "Ariyan Zarei"
  - literal: "Marco Pesavento"
  - literal: "Yichen Xu"
  - literal: "He Wen"
  - literal: "Teng Deng"
  - literal: "Wyatt Borsos"
  - literal: "Anjali Thakrar"
  - literal: "Jean-Charles Bazin"
  - literal: "Carsten Stoll"
  - literal: "Ginés Hidalgo"
  - literal: "James Booth"
  - literal: "Lucy Wang"
  - literal: "Xiaowen Ma"
  - literal: "Yu Rong"
  - literal: "Sairanjith Thalanki"
  - literal: "Chen Cao"
  - literal: "Christian Häne"
  - literal: "Abhishek Kar"
  - literal: "Sofien Bouaziz"
  - literal: "Jason Saragih"
  - literal: "Yaser Sheikh"
  - literal: "Shunsuke Saito"
issued:
  date-parts:
    - [2026, 4, 2]
url: "https://arxiv.org/abs/2604.02320"

# Custom fields
paper_id: "2604.02320"
paper_source: "arxiv"
domain: "computer-vision"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "pre-post-training-avatars"
dataset_slugs:
  []
skill: "NLPSkill"
processed_at: "2026-04-04T20:07:35Z"
created_at: "2026-04-04T20:07:35Z"
---

# Large-scale Codec Avatars: The Unreasonable Effectiveness of Large-scale Avatar Pretraining

**Authors**: Junxuan Li, Rawal Khirodkar, Chengan He, Zhongshi Jiang, Giljoo Nam, Lingchen Yang, Jihyun Lee, Egor Zakharov, Zhaoen Su, Rinat Abdrashitov, Yuan Dong, Julieta Martinez, Kai Li, Qingyang Tan, Takaaki Shiratori, Matthew Hu, Peihong Guo, Xuhua Huang, Ariyan Zarei, Marco Pesavento, Yichen Xu, He Wen, Teng Deng, Wyatt Borsos, Anjali Thakrar, Jean-Charles Bazin, Carsten Stoll, Ginés Hidalgo, James Booth, Lucy Wang, Xiaowen Ma, Yu Rong, Sairanjith Thalanki, Chen Cao, Christian Häne, Abhishek Kar, Sofien Bouaziz, Jason Saragih, Yaser Sheikh, Shunsuke Saito
**Date**: 2026-04-02
**Paper ID**: [arxiv:2604.02320](https://arxiv.org/abs/2604.02320)

## Summary

Large-Scale Codec Avatars (LCA) addresses the trade-off between high-fidelity studio modeling and generalizable in-the-wild avatar reconstruction. By adopting a pre/post-training paradigm—pretraining on 1M in-the-wild videos and post-training on high-quality curated data—LCA achieves both robust population-scale generalization and fine-grained expressive control. The model enables efficient feedforward inference and exhibits emergent capabilities such as relightability and zero-shot robustness to stylized imagery.

## Key Contributions

- Introduces Large-Scale Codec Avatars (LCA), a feedforward, full-body 3D avatar model that generalizes to population-scale identities.
- Establishes a new pre/post-training paradigm, leveraging 1M in-the-wild videos for prior learning followed by high-quality post-training for fidelity.
- Demonstrates emergent zero-shot capabilities in relightability, loose garment support, and robustness to stylized inputs without direct explicit supervision.

## Key Concepts

- [[pre-post-training-avatars]]: A two-stage training approach for 3D avatars that combines large-scale in-the-wild pretraining with high-quality domain-specific post-training to achieve both generalization and high fidelity.

## Archivist Review

I have approved the 'Pre/Post-training Paradigm' as a core concept because it defines a reusable methodological strategy for scaling 3D modeling, mirroring the transition toward foundation models in other domains. No other candidates were proposed, and no specific datasets were identified as central, reusable assets. The selection adheres to the policy of prioritizing high-level, durable architectural or training paradigms.

### Approved Concepts
- Pre/Post-training Paradigm for 3D Avatars: This paradigm addresses the trade-off between large-scale generalization and high-fidelity reconstruction, offering a novel methodological framework for scaling 3D avatar models.

## Links

- [Abstract](https://arxiv.org/abs/2604.02320)
- [PDF](https://arxiv.org/pdf/2604.02320)

