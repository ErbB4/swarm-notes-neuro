---
# CSL-compatible fields
title: "A public dataset of Ariel simulated observations for developing exoplanetary atmosphere data reduction pipelines"
author:
  - literal: "Lorenzo V. Mugnai"
  - literal: "Kai Hou Yip"
  - literal: "Andrea Bocchieri"
  - literal: "Ανδρέας Παπαγεωργίου"
  - literal: "V. Batista"
  - literal: "Orphée Faucoz"
  - literal: "Angèle Syty"
  - literal: "Tara Tahseen"
  - literal: "Enzo Pascale"
  - literal: "Ingo Waldmann"
issued:
  date-parts:
    - [2026, 5, 5]
url: "https://arxiv.org/abs/2605.03719"

# Custom fields
paper_id: "2605.03719"
paper_source: "openalex"
domain: "computer-vision"
tags:
  - "computer-vision"
architectures:
  []
datasets:
  - "ariel-simulated-exoplanet-dataset"
concept_slugs:
  []
dataset_slugs:
  - "ariel-simulated-exoplanet-dataset"
skill: "TimeSeriesSkill"
processed_at: "2026-05-08T05:44:24Z"
created_at: "2026-05-08T05:44:24Z"
---

# A public dataset of Ariel simulated observations for developing exoplanetary atmosphere data reduction pipelines

**Authors**: Lorenzo V. Mugnai, Kai Hou Yip, Andrea Bocchieri, Ανδρέας Παπαγεωργίου, V. Batista, Orphée Faucoz, Angèle Syty, Tara Tahseen, Enzo Pascale, Ingo Waldmann
**Date**: 2026-05-05
**Paper ID**: [openalex:2605.03719](https://arxiv.org/abs/2605.03719)

## Summary

This paper presents a comprehensive, high-fidelity synthetic dataset for the ESA Ariel mission, designed to facilitate the development and benchmarking of exoplanetary atmosphere data reduction pipelines. By providing ground-truth labeled time-series spectroscopy, the authors enable researchers to stress-test data-driven detrending methods against instrumental and astrophysical systematics. Additionally, the paper establishes a deep learning baseline and critically assesses the impact of dataset shift on the performance of ML-based detrending in real-world scenarios.

## Key Contributions

- Provides a comprehensive public dataset of simulated Ariel exoplanet atmosphere observations for benchmarking data reduction and detrending algorithms.
- Establishes a deep neural network baseline for time-series spectroscopic data reduction to enable method comparison.
- Identifies and quantifies the critical challenge of dataset shift in ML-based detrending when training and operational distributions diverge.

## Open Questions & Future Work

- [[generalization-under-domain-shift]]

## Archivist Review

I have approved the simulated dataset as a valuable, reusable resource for benchmarking detrending algorithms. I also approved the open question regarding generalization under domain shift, as it specifically highlights the systemic risk to scientific inference in survey-class missions. The uncertainty quantification question was rejected as a general ML topic rather than a central, unique challenge specific to the scientific domain presented.

### Approved Open Questions
- Generalization under domain shift: Scientific inference in survey missions depends on algorithms that generalize across diverse populations; failure to handle distribution shift directly compromises the homogeneity and reliability of the survey results.

### Rejected Candidates
- [open_question] Reliable uncertainty quantification (`reliable-uncertainty-quantification`) - duplicate_existing: Uncertainty quantification calibration is a general ML problem already well-represented by existing literature and vault themes.

## Datasets

- [[ariel-simulated-exoplanet-dataset]]

## Links

- [Abstract](https://arxiv.org/abs/2605.03719)
- [PDF](https://arxiv.org/pdf/2605.03719)

