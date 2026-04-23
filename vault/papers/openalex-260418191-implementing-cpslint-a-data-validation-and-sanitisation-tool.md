---
# CSL-compatible fields
title: "Implementing CPSLint: A Data Validation and Sanitisation Tool for Industrial Cyber-Physical Systems"
author:
  - literal: "Uraz Odyurt"
  - literal: "Ömer Sayilir"
  - literal: "Mariëlle Stoelinga"
  - literal: "Vadim Zaytsev"
issued:
  date-parts:
    - [2026, 4, 20]
url: "https://arxiv.org/abs/2604.18191"

# Custom fields
paper_id: "2604.18191"
paper_source: "openalex"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "cpslint"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-23T05:48:03Z"
created_at: "2026-04-23T05:48:03Z"
---

# Implementing CPSLint: A Data Validation and Sanitisation Tool for Industrial Cyber-Physical Systems

**Authors**: Uraz Odyurt, Ömer Sayilir, Mariëlle Stoelinga, Vadim Zaytsev
**Date**: 2026-04-20
**Paper ID**: [openalex:2604.18191](https://arxiv.org/abs/2604.18191)

## Summary

CPSLint is a domain-specific language developed to standardize the data preparation, validation, and sanitization processes for industrial cyber-physical systems. By raising the level of abstraction, it allows users to replace repetitive, ad-hoc Python scripts with concise, maintainable code structures. The tool specifically targets the challenges of large-scale, unstructured time-series data typical of industrial monitoring. CPSLint aims to improve productivity and reproducibility for both data scientists and domain experts working with industrial data pipelines.

## Key Contributions

- Introduces CPSLint, a domain-specific language (DSL) to abstract and standardize repetitive time-series data preparation, validation, and sanitization tasks.
- Reduces the complexity of data preparation in cyber-physical systems by enabling both data scientists and domain experts to define workflows concisely.
- Addresses the lack of maintainability and reproducibility inherent in ad-hoc, case-specific Python scripting for industrial data pipelines.

## Open Questions & Future Work

- [[industrial-dsl-expressivity-bottleneck]]

## Key Concepts

- [[cpslint]]: A domain-specific language for automating the validation and sanitization of time-series data in cyber-physical systems.

## Archivist Review

I approved CPSLint as a reusable conceptual framework for DSL-based time-series data prep. I reframed the open question to be more abstract and universally applicable to industrial data DSLs, moving away from the tool-specific roadmap presented in the original submission.

### Approved Concepts
- CPSLint: It introduces a domain-specific language approach to standardize and abstract repetitive data preparation tasks in industrial time-series settings, which is a novel structural intervention compared to ad-hoc scripting.

### Approved Open Questions
- Industrial DSL Expressivity Bottleneck: These features address the bottleneck of limited expressiveness and format compatibility, which currently restricts the tool from being used across a wider range of industrial data-centric workflows.

### Rejected Candidates
- [open_question] Extending CPSLint with domain-specific features (`cpslint-domain-specific-extensions`) - other: The original title and description were overly tied to a specific tool's roadmap; renamed to a more general research problem.

## Links

- [Abstract](https://arxiv.org/abs/2604.18191)
- [PDF](https://arxiv.org/pdf/2604.18191)

