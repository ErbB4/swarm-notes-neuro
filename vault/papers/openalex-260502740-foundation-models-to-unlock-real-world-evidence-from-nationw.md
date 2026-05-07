---
# CSL-compatible fields
title: "Foundation Models to Unlock Real-World Evidence from Nationwide Medical Claims"
author:
  - literal: "Fan Ma"
  - literal: "Yuntian Liu"
  - literal: "Xiang Lan"
  - literal: "Weipeng Zhou"
  - literal: "Jun Ni"
  - literal: "Mauro Giuffrè"
  - literal: "Lingfei Qian"
  - literal: "Xueqing Peng"
  - literal: "Yujia Zhou"
  - literal: "Ruey-Ling Weng"
  - literal: "Huan He"
  - literal: "Lu Li"
  - literal: "Qingyu Chen"
  - literal: "Andrew Loza"
  - literal: "Laila Rasmy"
  - literal: "Degui Zhi"
  - literal: "Yuan Lu"
  - literal: "Chenjie Zeng"
  - literal: "Joshua C. Denny"
  - literal: "Lee Schwamm"
  - literal: "Daniella Meeker"
  - literal: "Lucila Ohno-Machado"
  - literal: "Yong Chen"
  - literal: "Hua Xu"
issued:
  date-parts:
    - [2026, 5, 4]
url: "https://arxiv.org/abs/2605.02740"

# Custom fields
paper_id: "2605.02740"
paper_source: "openalex"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  - "MarketScan"
concept_slugs:
  - "reclaim"
dataset_slugs:
  - "marketscan"
skill: "TimeSeriesSkill"
processed_at: "2026-05-07T06:04:37Z"
created_at: "2026-05-07T06:04:37Z"
---

# Foundation Models to Unlock Real-World Evidence from Nationwide Medical Claims

**Authors**: Fan Ma, Yuntian Liu, Xiang Lan, Weipeng Zhou, Jun Ni, Mauro Giuffrè, Lingfei Qian, Xueqing Peng, Yujia Zhou, Ruey-Ling Weng, Huan He, Lu Li, Qingyu Chen, Andrew Loza, Laila Rasmy, Degui Zhi, Yuan Lu, Chenjie Zeng, Joshua C. Denny, Lee Schwamm, Daniella Meeker, Lucila Ohno-Machado, Yong Chen, Hua Xu
**Date**: 2026-05-04
**Paper ID**: [openalex:2605.02740](https://arxiv.org/abs/2605.02740)

## Summary

ReClaim is a generative transformer foundation model trained on massive-scale longitudinal administrative claims data. It effectively learns complex representations of patient trajectories, encompassing diagnoses, procedures, and medications. Empirical evaluation shows substantial performance gains over existing baselines across 1,000+ disease-onset prediction tasks and enhanced utility in healthcare expenditure forecasting and trial emulation. The model demonstrates strong generalizability and scaling laws across diverse medical event types.

## Key Contributions

- Introduced ReClaim, a generative transformer trained on 43.8 billion medical events from 200 million patients in the MarketScan database.
- Achieved a mean AUC of 75.6% across 1,000+ disease-onset prediction tasks, significantly outperforming LightGBM (66.3%) and Delphi (69.4%).
- Demonstrated superior utility in downstream clinical tasks, including improved healthcare expenditure forecasting and a 72% reduction in systematic bias for target trial emulation.

## Open Questions & Future Work

- [[clinical-phenotype-definitions-for-foundation-models]]

## Key Concepts

- [[reclaim]]: A generative transformer foundation model trained on large-scale administrative claims data for longitudinal healthcare trajectory modeling.

## Archivist Review

ReClaim is approved as a key healthcare foundation model architecture specifically targeting longitudinal administrative claims, which is a domain-specific paradigm deserving recognition. MarketScan is approved as a central dataset in this field. The open question regarding clinical phenotype definitions is approved as it addresses a fundamental limitation in benchmarking high-stakes clinical models. The multimodal integration question was rejected as being a generic 'more data' future work direction common to many model papers.

### Approved Concepts
- ReClaim: It is a foundational model specifically architecture for administrative claims data, demonstrating state-of-the-art performance in disease prediction and healthcare expenditure forecasting.

### Approved Open Questions
- Clinical Phenotype Definitions for Foundation Models: Using suboptimal disease definitions limits the clinical validity and precision of disease-onset predictions, potentially leading to representations that capture coding patterns rather than true pathophysiology.

## Datasets

- [[marketscan]]

## Links

- [Abstract](https://arxiv.org/abs/2605.02740)
- [PDF](https://arxiv.org/pdf/2605.02740)

