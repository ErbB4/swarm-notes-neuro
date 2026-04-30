---
# CSL-compatible fields
title: "Information bottleneck for learning the phase space of dynamics from high-dimensional experimental data"
author:
  - literal: "K. Michael Martini"
  - literal: "Eslam Abdelaleem"
  - literal: "Paarth Gulati"
  - literal: "Ilya Nemenman"
issued:
  date-parts:
    - [2026, 4, 27]
url: "https://arxiv.org/abs/2604.24662"

# Custom fields
paper_id: "2604.24662"
paper_source: "openalex"
domain: "time-series"
tags:
  - "time-series"
  - "latent-representation-learning"
  - "information-bottleneck"
  - "dynamical-systems"
architectures:
  []
datasets:
  []
concept_slugs:
  - "dysib"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-30T06:03:59Z"
created_at: "2026-04-30T06:03:59Z"
---

# Information bottleneck for learning the phase space of dynamics from high-dimensional experimental data

**Authors**: K. Michael Martini, Eslam Abdelaleem, Paarth Gulati, Ilya Nemenman
**Date**: 2026-04-27
**Paper ID**: [openalex:2604.24662](https://arxiv.org/abs/2604.24662)

## Summary

This paper introduces the Dynamical Symmetric Information Bottleneck (DySIB), a framework for learning low-dimensional representations of high-dimensional time-series data. By maximizing predictive mutual information between past and future observation windows and penalizing representation complexity, the method recovers latent dynamics without needing to reconstruct the raw input. Evaluation on experimental video data of a physical pendulum confirms that the learned latent space accurately captures the underlying system's dimensionality, topology, and geometry.

## Key Contributions

- Introduces DySIB, a method for learning latent dynamical state variables from high-dimensional time-series data without explicit observation reconstruction.
- Achieves the recovery of the two-dimensional phase space (topology and geometry) of a physical pendulum from raw video data.
- Demonstrates that maximizing predictive mutual information in latent space allows for the discovery of interpretable, canonical dynamical coordinates.

## Open Questions & Future Work

- [[canonical-representation-dynamics]]

## Key Concepts

- [[dysib]]: A method for learning low-dimensional representations of time-series by maximizing predictive mutual information between temporal windows while penalizing complexity.

## Archivist Review

I have approved the DySIB framework as a novel, non-reconstructive approach to latent state identification, and the open question regarding canonical representation forms, as these are foundational for the field of data-driven dynamical systems. I have rejected no candidates in this turn as the proposed items were highly selective and align with the requested standards for long-lived knowledge.

### Approved Concepts
- Dynamical Symmetric Information Bottleneck (DySIB): The central methodological innovation of the paper for latent dynamics discovery without reconstruction, providing a reusable framework for time-series representation learning.

### Approved Open Questions
- Canonical Latent Dynamics Representation: This is a critical bottleneck for the validation, benchmarking, and interpretability of data-driven dynamical modeling across arbitrary experiments.

## Links

- [Abstract](https://arxiv.org/abs/2604.24662)
- [PDF](https://arxiv.org/pdf/2604.24662)

