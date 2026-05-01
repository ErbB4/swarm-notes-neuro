---
# CSL-compatible fields
title: "Using Large Language Models for Black-Box Testing of FMU-Based Simulations"
author:
  - literal: "Abdullah Mughees"
  - literal: "Gaadha Sudheerbabu"
  - literal: "Tanwir Ahmad"
  - literal: "Dragoş Truşcan"
  - literal: "Mikael Månngård,"
  - literal: "Kristian Klemets"
issued:
  date-parts:
    - [2026, 4, 28]
url: "https://arxiv.org/abs/2604.25650"

# Custom fields
paper_id: "2604.25650"
paper_source: "openalex"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-01T06:04:56Z"
created_at: "2026-05-01T06:04:56Z"
---

# Using Large Language Models for Black-Box Testing of FMU-Based Simulations

**Authors**: Abdullah Mughees, Gaadha Sudheerbabu, Tanwir Ahmad, Dragoş Truşcan, Mikael Månngård,, Kristian Klemets
**Date**: 2026-04-28
**Paper ID**: [openalex:2604.25650](https://arxiv.org/abs/2604.25650)

## Summary

This paper introduces an LLM-driven framework to automate black-box testing for dynamic simulation models encapsulated as Functional Mock-up Units (FMUs). By leveraging functional and interface specifications, the system generates structured test scenarios in a Gherkin-style format, subsequently translating these into executable input time series for simulation. The framework automates the assertion-based verification of output behavior and provides human-readable diagnostic summaries to reduce manual testing overhead. Evaluation on a Lube Oil Cooling system highlights the approach's capability to bridge the gap between high-level functional requirements and automated numerical simulation verification.

## Key Contributions

- Proposes a human-in-the-loop framework utilizing LLMs to automate the generation of black-box testing scenarios for Functional Mock-up Units (FMUs).
- Implements a systematic pipeline for converting natural language functional specifications into structured Gherkin-style 'Given-When-Then' test scenarios and input time series.
- Demonstrates the efficacy of the approach on a Lube Oil Cooling system simulation, providing automated assertion checking, execution logging, and diagnostic visualization.

## Open Questions & Future Work

- [[adaptive-oracle-calibration-simulation]]

## Archivist Review

The paper proposes a workflow for applying LLMs to testing FMU simulations. The concepts involved (LLM-based test generation, assertion oracles) are currently implementation strategies rather than reusable, named foundational concepts. However, the identified problem of oracle calibration for simulation-based testing is a significant, persistent challenge in the field, making the proposed open question a strong candidate for the vault.

### Approved Open Questions
- Adaptive Oracle Calibration for Simulations: The reliance on poorly calibrated oracles undermines the trustworthiness of automated testing frameworks, as it increases false positives and negates the reliability of verification results.

### Rejected Candidates
- [concept] LLM-driven FMU Testing Framework (`llm-based-fmu-testing`) - paper_local: The framework is a specific application instance rather than a foundational concept or reusable algorithmic mechanism.
- [dataset] Lube Oil Cooling System Dataset (`lube-oil-cooling-system`) - low_impact: This is a specific simulation model instance rather than a benchmark dataset.

## Links

- [Abstract](https://arxiv.org/abs/2604.25650)
- [PDF](https://arxiv.org/pdf/2604.25650)

