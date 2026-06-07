---
# CSL-compatible fields
title: "Leveraging MTG-FCI fire observations for event-based fire behavior monitoring from near-real-time operation to seasonal analysis"
author:
  - literal: "Ronan Paugam"
  - literal: "Jean-Baptiste Filippi"
  - literal: "Akli Benali"
  - literal: "Jorge Gomes"
  - literal: "Weidong Xu"
  - literal: "Emanuel Dutra"
  - literal: "François André"
  - literal: "Damien Boulanger"
  - literal: "Vianney Retornard"
  - literal: "Andrea Meraner"
  - literal: "J M Harvie"
  - literal: "Victor Pénot"
  - literal: "Cyrielle Denjean"
issued:
  date-parts:
    - [2026, 6, 4]
url: "https://arxiv.org/abs/2606.06016"

# Custom fields
paper_id: "2606.06016"
paper_source: "openalex"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "fire-event-tracker-fet"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-06-07T06:33:45Z"
created_at: "2026-06-07T06:33:45Z"
---

# Leveraging MTG-FCI fire observations for event-based fire behavior monitoring from near-real-time operation to seasonal analysis

**Authors**: Ronan Paugam, Jean-Baptiste Filippi, Akli Benali, Jorge Gomes, Weidong Xu, Emanuel Dutra, François André, Damien Boulanger, Vianney Retornard, Andrea Meraner, J M Harvie, Victor Pénot, Cyrielle Denjean
**Date**: 2026-06-04
**Paper ID**: [openalex:2606.06016](https://arxiv.org/abs/2606.06016)

## Summary

This paper introduces the Fire Event Tracker (FET), an algorithm that transforms intermittent hotspot detections from the MTG-FCI geostationary satellite into coherent, persistent fire event sequences. By performing spatio-temporal clustering, the method generates near-real-time and retrospective data on fire evolution, including fire radiative power and spread rates. The framework was successfully validated through Mediterranean seasonal analysis and operational deployment in wildfire monitoring and airborne campaign support. FET-derived outputs were also used to initialize coupled atmospheric-fire simulations, demonstrating utility for both tactical resource allocation and seasonal environmental research.

## Key Contributions

- Introduces the Fire Event Tracker (FET) algorithm for spatio-temporal clustering of 10-min MTG-FCI satellite hotspot observations.
- Enables consistent fire behavior monitoring (geometry, radiative power, rate of spread) for both operational tactical support and retrospective seasonal analysis.
- Demonstrates utility in initializing coupled atmosphere-fire simulations (FOREFIRE-MesoNH) for plume forecasting and wildfire monitoring campaigns.

## Key Concepts

- [[fire-event-tracker-fet]]: A spatio-temporal clustering algorithm for associating geostationary satellite hotspot detections into persistent fire event sequences.

## Archivist Review

I have approved the Fire Event Tracker (FET) concept to acknowledge its contribution to fire-event spatio-temporal modeling, but I am also noting in the rejected list that it is essentially domain-specific to satellite wildfire monitoring, limiting its broader applicability across the general ML domain. I applied strict criteria focusing on generalizable temporal inductive biases and forecasting frameworks.

### Approved Concepts
- Fire Event Tracker (FET): Provides a methodology for converting intermittent satellite hotspot detections into coherent, persistent fire event objects for monitoring.

### Rejected Candidates
- [concept] Fire Event Tracker (FET) (`fire-event-tracker-fet`) - not_reusable: The algorithm is a domain-specific clustering procedure for satellite wildfire data and lacks the broader methodological abstraction required for a general machine learning knowledge vault.

## Links

- [Abstract](https://arxiv.org/abs/2606.06016)
- [PDF](https://arxiv.org/pdf/2606.06016)

