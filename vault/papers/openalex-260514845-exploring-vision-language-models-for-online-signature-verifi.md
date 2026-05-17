---
# CSL-compatible fields
title: "Exploring Vision-Language Models for Online Signature Verification: A Zero-Shot Capability Study"
author:
  - literal: "Marta Robledo-Moreno"
  - literal: "Ruben Vera-Rodriguez"
  - literal: "Ruben Tolosana"
  - literal: "Javier Ortega-García"
issued:
  date-parts:
    - [2026, 5, 14]
url: "https://arxiv.org/abs/2605.14845"

# Custom fields
paper_id: "2605.14845"
paper_source: "openalex"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "rationalization-trap"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-17T06:08:33Z"
created_at: "2026-05-17T06:08:33Z"
---

# Exploring Vision-Language Models for Online Signature Verification: A Zero-Shot Capability Study

**Authors**: Marta Robledo-Moreno, Ruben Vera-Rodriguez, Ruben Tolosana, Javier Ortega-García
**Date**: 2026-05-14
**Paper ID**: [openalex:2605.14845](https://arxiv.org/abs/2605.14845)

## Summary

This study explores the zero-shot capabilities of advanced vision-language models (VLMs) for the biometric task of online signature verification. The authors propose a method to represent kinematic time-series as static images with stroke-opacity pressure encoding and develop a scoring protocol based on latent token probabilities. While the models demonstrate superior discrimination in random forgery scenarios, they struggle with skilled forgeries, where chain-of-thought reasoning often leads to a 'Rationalization Trap' that misinterprets forgery artifacts.

## Key Contributions

- Evaluates zero-shot performance of GPT-5.2 and Gemini 2.5 Pro on the Signature Verification Challenge (SVC) benchmark.
- Introduces a visual encoding method converting kinematic signature time-series into opacity-based static images.
- Identifies the 'Rationalization Trap' where chain-of-thought reasoning degrades accuracy in skilled forgery detection due to hallucinated justifications.

## Open Questions & Future Work

- [[vlm-rationalization-trap-mitigation]]

## Key Concepts

- [[rationalization-trap]]: A phenomenon where chain-of-thought reasoning in vision-language models leads to kinematic hallucinations that misclassify forgery artifacts as natural variability.

## Archivist Review

Approved the 'Rationalization Trap' as a reusable concept for failure modes in multimodal CoT reasoning, and the open question regarding its mitigation. Rejected the SVC dataset as it is a specific biometric task benchmark outside the primary scope of time-series forecasting research.

### Approved Concepts
- Rationalization Trap: Highlights a failure mode where explicit reasoning (CoT) in multimodal models misinterprets biometric signal artifacts, especially in skilled forgery scenarios.

### Approved Open Questions
- Mitigating VLM Rationalization Traps: Essential for building reliable forensic and diagnostic AI systems where accurate and interpretable reasoning is a prerequisite for human-in-the-loop verification.

### Rejected Candidates
- [dataset] Signature Verification Challenge (SVC) (`svc`) - low_impact: The SVC benchmark is a specific domain-standard set for signature verification that, while useful, is less critical for the broader time-series forecasting vault than more generalized benchmarks.

## Links

- [Abstract](https://arxiv.org/abs/2605.14845)
- [PDF](https://arxiv.org/pdf/2605.14845)

