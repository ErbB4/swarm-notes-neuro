---
# CSL-compatible fields
title: "Multimodal Transformer Based Generic Mixture Density Network for Scattering Timescale Estimation of Fast Radio Bursts"
author:
  - literal: "Bikash Kharel"
  - literal: "Emmanuel Fonseca"
  - literal: "Srinjoy Das"
  - literal: "Mason Ng"
  - literal: "Paul Scholz"
  - literal: "Mawson W. Simmons"
  - literal: "Lordrick Kahinga"
  - literal: "Afrokk Khan"
issued:
  date-parts:
    - [2026, 6, 2]
url: "https://arxiv.org/abs/2606.03596"

# Custom fields
paper_id: "2606.03596"
paper_source: "openalex"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  - "chime-frb"
concept_slugs:
  - "mt-gmdn"
dataset_slugs:
  - "chime-frb"
skill: "TimeSeriesSkill"
processed_at: "2026-06-05T06:33:39Z"
created_at: "2026-06-05T06:33:39Z"
---

# Multimodal Transformer Based Generic Mixture Density Network for Scattering Timescale Estimation of Fast Radio Bursts

**Authors**: Bikash Kharel, Emmanuel Fonseca, Srinjoy Das, Mason Ng, Paul Scholz, Mawson W. Simmons, Lordrick Kahinga, Afrokk Khan
**Date**: 2026-06-02
**Paper ID**: [openalex:2606.03596](https://arxiv.org/abs/2606.03596)

## Summary

The paper introduces the Multimodal Transformer Based Generic Mixture Density Network (MT-GMDN) to address the computational bottleneck of estimating scattering timescales (τ) for fast radio bursts. By utilizing parallel transformer encoders to process both dynamic spectra and timeseries profiles, the model provides probabilistic outputs via a mixture density formulation, effectively handling the zero-inflated distribution of scattering values. The method achieves state-of-the-art performance on the CHIME/FRB dataset, offering significant gains in speed and robustness over traditional template-fitting methods while quantifying prediction uncertainty.

## Key Contributions

- Introduced MT-GMDN, a multimodal transformer that fuses dynamic spectra and timeseries profiles to estimate scattering timescales.
- Achieved 94% R^2 on measurable scattering timescales and 90% recall in identifying scattering presence.
- Incorporated heteroskedastic error estimation within a mixture density framework to provide confidence intervals for physical parameter predictions.

## Key Concepts

- [[mt-gmdn]]: A multimodal transformer-based mixture density network designed to predict physical parameter distributions in zero-inflated time-series data.

## Archivist Review

I approved the MT-GMDN architecture as a novel approach to zero-inflated parameter estimation in signal data, and included the CHIME/FRB dataset as it is the central evaluation corpus for this specific astrophysical task. I rejected further subcomponents as they are adequately covered by the primary architectural concept.

### Approved Concepts
- MT-GMDN: This is the primary multimodal architecture proposed for handling zero-inflated physical parameter estimation via mixture density networks in astrophysical time series.

### Rejected Candidates
- [concept] Parallel Transformer Encoders for Signal Fusion (`mt-gmdn-subcomponents`) - subcomponent_of_broader_mechanism: This is a standard implementation subcomponent of the proposed MT-GMDN architecture and does not warrant a separate entry.

## Datasets

- [[chime-frb]]

## Links

- [Abstract](https://arxiv.org/abs/2606.03596)
- [PDF](https://arxiv.org/pdf/2606.03596)

