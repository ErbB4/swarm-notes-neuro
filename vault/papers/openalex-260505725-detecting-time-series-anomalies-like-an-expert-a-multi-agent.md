---
# CSL-compatible fields
title: "Detecting Time Series Anomalies Like an Expert: A Multi-Agent LLM Framework with Specialized Analyzers"
author:
  - literal: "Hyeongwon Kang"
  - literal: "Jeongseob Kim"
  - literal: "Jinwoo Park"
  - literal: "Pilsung Kang"
issued:
  date-parts:
    - [2026, 5, 7]
url: "https://arxiv.org/abs/2605.05725"

# Custom fields
paper_id: "2605.05725"
paper_source: "openalex"
domain: "time-series"
tags:
  - "anomaly-detection"
  - "time-series-forecasting"
  - "multi-agent-systems"
  - "large-language-models"
  - "in-context-learning"
architectures:
  []
datasets:
  []
concept_slugs:
  - "sage-specialized-analyzer-group-for-expert-like-detection"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-10T06:03:48Z"
created_at: "2026-05-10T06:03:48Z"
---

# Detecting Time Series Anomalies Like an Expert: A Multi-Agent LLM Framework with Specialized Analyzers

**Authors**: Hyeongwon Kang, Jeongseob Kim, Jinwoo Park, Pilsung Kang
**Date**: 2026-05-07
**Paper ID**: [openalex:2605.05725](https://arxiv.org/abs/2605.05725)

## Summary

SAGE is a multi-agent framework for univariate time-series anomaly detection that overcomes the limitations of monolithic LLM approaches by decoupling detection into specialized analyzers. Each analyzer utilizes domain-specific numerical tools and visualizations to produce diagnostic evidence, which is then synthesized by an evidence-grounded detector. By generating synthetic in-context examples from normal data, the system eliminates the need for labeled anomalous data while improving detection reliability and explainability. Experimental results across three benchmarks demonstrate superior performance and improved diagnostic utility compared to existing ML, DL, and LLM-based baselines.

## Key Contributions

- Introduces SAGE, a multi-agent framework that decomposes univariate time-series anomaly detection into specialized point, structural, seasonal, and pattern analyzers.
- Implements an evidence-grounded detection process that integrates family-specific numerical tools and diagnostic visualizations into confidence-scored anomaly records.
- Achieves state-of-the-art performance across three anomaly detection benchmarks without requiring anomalous segments or explicit type labels for in-context learning.

## Open Questions & Future Work

- [[llm-tsad-latency-bottleneck]]
- [[synthetic-data-coverage-gaps]]

## Key Concepts

- [[sage-specialized-analyzer-group-for-expert-like-detection]]: A multi-agent framework that decomposes univariate time-series anomaly detection into specialized analytical agents and an evidence-grounded detector.

## Archivist Review

I approved the SAGE framework for its novel multi-agent decomposition of anomaly detection, which represents a highly reusable architecture for complex temporal diagnosis. I also approved two open questions concerning the latency of agentic systems and the coverage limitations of synthetic data generation, as these are critical systemic challenges in the field. No datasets were approved as they were not named uniquely or treated as a central, reusable component.

### Approved Concepts
- SAGE (Specialized Analyzer Group for Expert-like Detection): This framework introduces a modular, agentic approach to anomaly detection that decomposes the task into specialized analysis and evidence synthesis, which is a significant departure from monolithic LLM usage.

### Approved Open Questions
- Efficiency in Agentic TSAD: Reducing the latency of agentic systems is a prerequisite for moving beyond benchmark evaluation to real-time industrial production environments.
- Limits of Synthetic Training: The limitation of synthetic data coverage remains the primary obstacle to deploying these systems in uncontrolled, highly variable physical environments.

## Links

- [Abstract](https://arxiv.org/abs/2605.05725)
- [PDF](https://arxiv.org/pdf/2605.05725)

