---
# CSL-compatible fields
title: "A Resilient Solution for Sewer Overflow Monitoring across Cloud and Edge"
author:
  - literal: "Vipin Singh"
  - literal: "Tianheng Ling"
  - literal: "Peter Ghaly"
  - literal: "Felix Grimmeisen"
  - literal: "Gregor Schiele"
  - literal: "Felix Bießmann"
issued:
  date-parts:
    - [2026, 5, 11]
url: "https://arxiv.org/abs/2605.10592"

# Custom fields
paper_id: "2605.10592"
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
processed_at: "2026-05-14T06:10:26Z"
created_at: "2026-05-14T06:10:26Z"
---

# A Resilient Solution for Sewer Overflow Monitoring across Cloud and Edge

**Authors**: Vipin Singh, Tianheng Ling, Peter Ghaly, Felix Grimmeisen, Gregor Schiele, Felix Bießmann
**Date**: 2026-05-11
**Paper ID**: [openalex:2605.10592](https://arxiv.org/abs/2605.10592)

## Summary

This paper introduces a resilient monitoring framework for combined sewer systems, designed to address the environmental risks posed by extreme rainfall. The system utilizes deep learning-based forecasting for sewer basin filling dynamics, implemented across a hybrid cloud-edge architecture. By ensuring local processing at the edge, the framework maintains functionality even during network outages, providing a robust tool for real-time monitoring and preventive intervention.

## Key Contributions

- Developed a web-based monitoring system for combined sewer overflows that deploys deep learning models across both cloud and edge environments.
- Ensures system resilience against network outages by enabling local inference capabilities at the edge.
- Provides an interactive dashboard for visualizing filling dynamics and capacity exceedance in sewer basins.

## Open Questions & Future Work

- [[robustness-to-data-degradation-in-critical-infrastructure]]

## Archivist Review

The paper describes a deployment architecture for sewer monitoring, which focuses on engineering integration rather than a novel methodological contribution to the field of time-series forecasting. The open question regarding data robustness was refined to focus on critical infrastructure, as sensor degradation in such environments is a persistent and non-trivial problem.

### Approved Open Questions
- Robustness to data degradation: Ensuring model robustness against real-world sensor degradation is critical for preventing false positives or missed overflow warnings in safety-critical infrastructure.

### Rejected Candidates
- [concept] Cloud-Edge Monitoring Architecture (`cloud-edge-monitoring-architecture`) - not_novel: General architecture pattern without specific novel mechanism.

## Links

- [Abstract](https://arxiv.org/abs/2605.10592)
- [PDF](https://arxiv.org/pdf/2605.10592)

