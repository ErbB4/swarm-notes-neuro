---
# CSL-compatible fields
title: "FMplex: Model Virtualization for Serving Extensible Foundation Models"
author:
  - literal: "Hetvi Shastri"
  - literal: "Pragya Sharma"
  - literal: "Walid A. Hanafy"
  - literal: "David Irwin"
  - literal: "Mani Srivastava"
  - literal: "Prashant Shenoy"
issued:
  date-parts:
    - [2026, 6, 8]
url: "https://arxiv.org/abs/2606.09643"

# Custom fields
paper_id: "2606.09643"
paper_source: "openalex"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "virtual-foundation-model-vfm"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-06-11T06:36:31Z"
created_at: "2026-06-11T06:36:31Z"
---

# FMplex: Model Virtualization for Serving Extensible Foundation Models

**Authors**: Hetvi Shastri, Pragya Sharma, Walid A. Hanafy, David Irwin, Mani Srivastava, Prashant Shenoy
**Date**: 2026-06-08
**Paper ID**: [openalex:2606.09643](https://arxiv.org/abs/2606.09643)

## Summary

FMplex is a foundation model serving system that addresses the resource inefficiencies of deploying customized tasks as independent model instances. By introducing a virtual foundation model (vFM) abstraction, it allows multiple tasks to share a single physical backbone while preserving logical isolation and independent lifecycles. The system incorporates a batch-aware fair-queueing scheduler to optimize throughput and latency across colocated tasks. Evaluation across 16 backbone variants and 92 downstream tasks confirms its effectiveness in increasing cluster-scale task density.

## Key Contributions

- Introduces FMplex, a serving system that virtualizes foundation model backbones to enable resource sharing across independent downstream tasks.
- Develops a batch-aware fair-queueing scheduler that optimizes performance through integrated inter- and intra-task batching.
- Demonstrates significant scalability improvements, hosting up to 6x more tasks and reducing latency by up to 80% compared to existing spatial partitioning methods.

## Key Concepts

- [[virtual-foundation-model-vfm]]: A virtualization abstraction that provides logically private foundation model instances backed by a shared physical backbone.

## Archivist Review

The submission focuses on a systems engineering contribution—virtualizing model backbones to improve multi-tenant serving efficiency. I approved the vFM abstraction as a core concept representing this paradigm, but rejected the scheduler as a subcomponent of the broader FMplex serving system. No datasets or open questions were proposed, and none were extracted that met the criteria for permanence.

### Approved Concepts
- Virtual Foundation Model (vFM): It provides a virtualization abstraction for foundation models that enables efficient multi-tenant resource sharing while maintaining logical task isolation.

### Rejected Candidates
- [concept] batch-aware fair-queueing scheduler (`batch-aware-fair-queueing-scheduler`) - subcomponent_of_broader_mechanism: This is a specific scheduling implementation detail for the FMplex system rather than a generalizable core architectural principle for model development.

## Links

- [Abstract](https://arxiv.org/abs/2606.09643)
- [PDF](https://arxiv.org/pdf/2606.09643)

