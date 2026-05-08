---
# CSL-compatible fields
title: "OracleProto: A Reproducible Framework for Benchmarking LLM Native Forecasting via Knowledge Cutoff and Temporal Masking"
author:
  - literal: "Yiding Ma"
  - literal: "Chengyun Ruan"
  - literal: "Kaibo Huang"
  - literal: "Zhongliang Yang"
  - literal: "Linna Zhou"
issued:
  date-parts:
    - [2026, 5, 5]
url: "https://arxiv.org/abs/2605.03762"

# Custom fields
paper_id: "2605.03762"
paper_source: "openalex"
domain: "nlp"
tags:
  - "time-series-question-answering-tsqa"
  - "agentic-time-series-forecasting"
architectures:
  []
datasets:
  - "FutureX-Past"
concept_slugs:
  - "oracleproto"
dataset_slugs:
  - "futurex-past"
skill: "TimeSeriesSkill"
processed_at: "2026-05-08T05:43:50Z"
created_at: "2026-05-08T05:43:50Z"
---

# OracleProto: A Reproducible Framework for Benchmarking LLM Native Forecasting via Knowledge Cutoff and Temporal Masking

**Authors**: Yiding Ma, Chengyun Ruan, Kaibo Huang, Zhongliang Yang, Linna Zhou
**Date**: 2026-05-05
**Paper ID**: [openalex:2605.03762](https://arxiv.org/abs/2605.03762)

## Summary

OracleProto is a reproducible framework designed to evaluate the forecasting capabilities of large language models while mitigating information leakage from pretraining data. By combining knowledge-cutoff-aligned sample admission, temporal masking, and content-level leakage detection, the framework transforms resolved historical events into reliable forecasting benchmarks. Experimental results demonstrate that OracleProto maintains leakage at the 1% level, enabling rigorous, auditable, and comparative assessments of LLM forecasting performance.

## Key Contributions

- Introduces OracleProto, a reproducible benchmarking framework that reconstructs resolved events into time-bounded forecasting samples.
- Achieves leakage rates as low as 1%, representing a significant improvement over standard tool-only temporal filtering techniques.
- Provides a unified evaluation interface for measuring forecasting quality, sampling stability, and cost efficiency across multiple contemporary LLMs.

## Open Questions & Future Work

- [[llm-forecasting-leakage-evaluation]]

## Key Concepts

- [[oracleproto]]: A framework for creating reproducible LLM forecasting benchmarks by reconstructing resolved events with strict temporal masking and leakage detection.

## Archivist Review

I have approved OracleProto as a central concept because it provides a systematic methodological framework for a critical issue in LLM-based time-series forecasting. FutureX-Past is approved as a central dataset benchmark. I have also added a high-level open question regarding the fundamental difficulty of disentangling predictive reasoning from memorized knowledge in LLMs, which is a major ongoing concern for the field.

### Approved Concepts
- OracleProto: It establishes a systematic methodology for creating leakage-free, time-bounded forecasting benchmarks for LLMs by aligning data with model knowledge cutoffs, addressing a critical bottleneck in evaluating agentic forecasting.

### Approved Open Questions
- LLM Forecasting Leakage Evaluation: This is a foundational problem for ensuring that LLM forecasting benchmarks measure intelligence rather than memorization.

## Datasets

- [[futurex-past]]

## Links

- [Abstract](https://arxiv.org/abs/2605.03762)
- [PDF](https://arxiv.org/pdf/2605.03762)

