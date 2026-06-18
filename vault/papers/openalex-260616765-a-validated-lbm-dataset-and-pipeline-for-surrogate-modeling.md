---
# CSL-compatible fields
title: "A Validated LBM Dataset and Pipeline for Surrogate Modeling of Turbulent 3D Obstructed Channel Flows"
author:
  - literal: "Lukas Schröder"
  - literal: "Shubham Kavane"
  - literal: "Harald Köstler"
issued:
  date-parts:
    - [2026, 6, 15]
url: "https://arxiv.org/abs/2606.16765"

# Custom fields
paper_id: "2606.16765"
paper_source: "openalex"
domain: "computer-vision"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "lbm-turbulent-flow-pipeline"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-06-18T06:38:10Z"
created_at: "2026-06-18T06:38:10Z"
---

# A Validated LBM Dataset and Pipeline for Surrogate Modeling of Turbulent 3D Obstructed Channel Flows

**Authors**: Lukas Schröder, Shubham Kavane, Harald Köstler
**Date**: 2026-06-15
**Paper ID**: [openalex:2606.16765](https://arxiv.org/abs/2606.16765)

## Summary

This paper introduces a high-fidelity, validated lattice Boltzmann method (LBM) pipeline for generating training data for 3D turbulent channel flows across a range of Reynolds numbers. By ensuring physical accuracy through rigorous verification against experimental benchmarks like turbulent fluctuations and drag coefficients, the authors provide a standard for testing neural operator performance in fluid dynamics. The research framework is designed to evaluate surrogate models—such as FNOs and U-Nets—on complex tasks including forecasting and super-resolution, specifically measuring their ability to represent turbulent energy cascades.

## Key Contributions

- Introduces a reproducible lattice Boltzmann (LBM) data generation pipeline for 3D turbulent channel flows at Reynolds numbers 1,000–10,000.
- Provides rigorous physical validation against experimental benchmarks, including Strouhal numbers, drag coefficients, and turbulent fluctuations.
- Establishes a standardized framework for evaluating neural surrogates (FNO, U-Net) across forecasting, super-resolution, and error-correction tasks in fluid dynamics.

## Key Concepts

- [[lbm-turbulent-flow-pipeline]]: A verified pipeline for generating high-fidelity lattice Boltzmann simulation data of 3D turbulent channel flows for surrogate modeling evaluation.

## Archivist Review

I have approved the LBM pipeline as a concept because it represents a reusable methodological framework for producing validated scientific datasets. I rejected the concept of energy cascade representation because it describes a physical phenomenon rather than a reusable algorithmic contribution or methodology. No specific datasets were approved as the authors did not name the specific generated dataset or repository in a way that suggests a standalone benchmark name beyond the general pipeline description.

### Approved Concepts
- Lattice Boltzmann Method Pipeline for Turbulent Flows: Provides a standardized, validated data generation framework essential for training and benchmarking neural operators on complex, high-Reynolds number 3D turbulent flow problems.

### Rejected Candidates
- [concept] Turbulent Energy Cascade Representation (`turbulent-energy-cascade-representation`) - generic: This is a standard physical phenomenon rather than a specific neural operator mechanism or novel architectural concept.

## Links

- [Abstract](https://arxiv.org/abs/2606.16765)
- [PDF](https://arxiv.org/pdf/2606.16765)

