---
# CSL-compatible fields
title: "GCA Framework: A Gulf-Grounded Dataset and Agentic Pipeline for Climate Decision Support"
author:
  - literal: "Muhammad Umer Sheikh"
  - literal: "Khawar Shehzad"
  - literal: "Salman Khan"
  - literal: "Fahad Shahbaz Khan"
  - literal: "Muhammad Nauman Khan"
issued:
  date-parts:
    - [2026, 4, 14]
url: "https://arxiv.org/abs/2604.12306"

# Custom fields
paper_id: "2604.12306"
paper_source: "openalex"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  - "gca-ds"
concept_slugs:
  []
dataset_slugs:
  - "gca-ds"
skill: "TimeSeriesSkill"
processed_at: "2026-04-17T05:46:55Z"
created_at: "2026-04-17T05:46:55Z"
---

# GCA Framework: A Gulf-Grounded Dataset and Agentic Pipeline for Climate Decision Support

**Authors**: Muhammad Umer Sheikh, Khawar Shehzad, Salman Khan, Fahad Shahbaz Khan, Muhammad Nauman Khan
**Date**: 2026-04-14
**Paper ID**: [openalex:2604.12306](https://arxiv.org/abs/2604.12306)

## Summary

The GCA framework addresses the limitations of general-purpose LLMs in regional climate analysis by introducing a specialized dataset and agentic pipeline for the Gulf region. GCA-DS provides a comprehensive collection of 200k multimodal question-answer pairs covering policy, academic, and event-driven environmental data. The GCA agent integrates this knowledge with real-time geospatial processing and forecasting tools to provide actionable, grounded climate decision support. Benchmarking results confirm that this domain-aware approach improves the reliability and interpretability of LLM-based climate guidance.

## Key Contributions

- Introduces GCA-DS, a 200k multimodal QA dataset focused on Gulf climate policies, environmental reports, and remote-sensing data.
- Develops the Gulf Climate Agent (GCA), a modular, tool-augmented agent pipeline for climate analysis and geospatial processing.
- Demonstrates that domain-specific fine-tuning and tool integration significantly outperform general-purpose LLMs in regional climate decision support tasks.

## Open Questions & Future Work

- [[uncertainty-aware-climate-benchmarking]]

## Archivist Review

The GCA-DS dataset is approved as it serves as a foundational domain-specific resource for regional climate AI. The open question on uncertainty-aware benchmarking is approved as it highlights a critical bottleneck in deploying climate-AI for high-stakes decision-making. Other candidate concepts were rejected as they described specific system implementations rather than general methodological contributions.

### Approved Open Questions
- Uncertainty-Aware Climate Scenario Benchmarking: Current evaluation paradigms in climate AI are limited by a lack of rigorous, domain-specific benchmarks that can assess the reliability of AI models in scenarios involving high-stakes uncertainty and long-term climate projections.

### Rejected Candidates
- [concept] Gulf Climate Agent (GCA) (`gca-agent`) - paper_local: The GCA is a paper-specific implementation of a general agentic pipeline for climate analysis rather than a novel conceptual framework.

## Datasets

- [[gca-ds]]

## Links

- [Abstract](https://arxiv.org/abs/2604.12306)
- [PDF](https://arxiv.org/pdf/2604.12306)

