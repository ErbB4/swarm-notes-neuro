---
# CSL-compatible fields
title: "PARD-SSM: Probabilistic Cyber-Attack Regime Detection via Variational Switching State-Space Models"
author:
  - literal: "Prakul Sunil Hiremath"
  - literal: "PeerAhammad M Bagawan"
  - literal: "Sahil Bhekane"
issued:
  date-parts:
    - [2026, 4, 2]
url: "https://arxiv.org/abs/2604.02299"

# Custom fields
paper_id: "2604.02299"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "regime-dependent-switching-lds"
dataset_slugs:
  []
skill: "GeneralMLSkill"
processed_at: "2026-04-04T20:07:49Z"
created_at: "2026-04-04T20:07:49Z"
---

# PARD-SSM: Probabilistic Cyber-Attack Regime Detection via Variational Switching State-Space Models

**Authors**: Prakul Sunil Hiremath, PeerAhammad M Bagawan, Sahil Bhekane
**Date**: 2026-04-02
**Paper ID**: [arxiv:2604.02299](https://arxiv.org/abs/2604.02299)

## Summary

PARD-SSM is a probabilistic framework designed to detect multi-stage cyber-attacks by modeling network telemetry as a Regime-Dependent Switching Linear Dynamical System. By employing a structured variational approximation, the model efficiently identifies distinct adversarial phases—such as reconnaissance and exfiltration—in real-time. Experimental results on benchmark datasets demonstrate superior F1 performance and provide predictive alerts significantly earlier than existing methods.

## Key Contributions

- Introduces PARD-SSM, a probabilistic framework for cyber-attack detection that models multi-stage adversarial behavior as hidden states in a switching linear dynamical system.
- Develops a structured variational inference technique reducing inference complexity to O(TK^2), enabling real-time detection on standard hardware.
- Achieves F1 scores of 98.2% and 97.1% on CICIDS2017 and UNSW-NB15 respectively, with sub-1.2ms latency and early-warning predictive capabilities.

## Key Concepts

- [[regime-dependent-switching-lds]]: A state-space modeling approach that treats distinct adversarial attack stages as discrete, latent dynamic regimes.

## Archivist Review

The paper proposes a specialized state-space model for multi-stage attack detection. I approved the core conceptual framework as it provides a reusable probabilistic approach to sequential anomaly detection. No other candidates were proposed, and the paper-specific datasets were excluded per the strict requirement to avoid routine benchmark notes.

### Approved Concepts
- Regime-Dependent Switching Linear Dynamical System: Provides a novel probabilistic framing for multi-stage attack detection by modeling adversarial phases as hidden regimes.

## Links

- [Abstract](https://arxiv.org/abs/2604.02299)
- [PDF](https://arxiv.org/pdf/2604.02299)

