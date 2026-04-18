---
# CSL-compatible fields
title: "Unsupervised Anomaly Detection in Process-Complex Industrial Time Series: A Real-World Case Study"
author:
  - literal: "Sergej Krasnikov"
  - literal: "Lukas Meitz"
  - literal: "Samineh Bagheri"
  - literal: "Michael Heider"
  - literal: "Thorsten Schöler"
  - literal: "Jörg Hähner"
issued:
  date-parts:
    - [2026, 4, 15]
url: "https://arxiv.org/abs/2604.13928"

# Custom fields
paper_id: "2604.13928"
paper_source: "openalex"
domain: "time-series"
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
processed_at: "2026-04-18T05:34:33Z"
created_at: "2026-04-18T05:34:33Z"
---

# Unsupervised Anomaly Detection in Process-Complex Industrial Time Series: A Real-World Case Study

**Authors**: Sergej Krasnikov, Lukas Meitz, Samineh Bagheri, Michael Heider, Thorsten Schöler, Jörg Hähner
**Date**: 2026-04-15
**Paper ID**: [openalex:2604.13928](https://arxiv.org/abs/2604.13928)

## Summary

This paper investigates unsupervised anomaly detection in highly complex, multi-stage industrial time-series data, highlighting the limitations of conventional models like Isolation Forest. Through a comparative study of various autoencoder architectures, the authors demonstrate that temporal convolutional autoencoders effectively capture the non-periodic, multi-scale dynamics of production environments. The study provides empirical evidence on real-world machinery data, offering insights into model selection for industrial applications.

## Key Contributions

- Presents a real-world industrial dataset capturing heterogeneous, multi-stage operational processes with high variability.
- Demonstrates that Isolation Forest baselines struggle with the multi-scale, non-periodic dynamics inherent in complex industrial machinery data.
- Evaluates various autoencoder architectures and identifies temporal convolutional autoencoders as the most robust performers for industrial anomaly detection.

## Open Questions & Future Work

- [[transformer-applicability-industrial-anomaly-detection]]

## Archivist Review

The paper provides a useful comparative analysis of anomaly detection models in a real-world industrial context, but the proposed findings are largely empirical and local to the specific machinery data provided. I have approved the open question regarding transformer applicability because it captures a significant, unresolved tension between architectural complexity and real-world industrial constraints. I rejected the proposed dataset and concepts as they lacked the necessary formal naming or conceptual abstraction required for long-term vault utility.

### Approved Open Questions
- Transformer Suitability in Industrial Settings: Determining the applicability of attention-based models in industrial settings is crucial for advancing beyond the performance plateaus currently observed with traditional autoencoder architectures in complex, multi-stage industrial environments.

### Rejected Candidates
- [dataset] Industrial Anomaly Detection Real-World Dataset (`industrial-anomaly-detection-real-world-dataset`) - weak_evidence: The dataset is not explicitly named or provided in a reusable format in the summary.
- [concept] Temporal Convolutional Autoencoder Robustness (`temporal-convolutional-autoencoder-robustness`) - paper_local: This is a specific model architecture finding rather than a general, reusable concept or mechanism for the vault.

## Links

- [Abstract](https://arxiv.org/abs/2604.13928)
- [PDF](https://arxiv.org/pdf/2604.13928)

