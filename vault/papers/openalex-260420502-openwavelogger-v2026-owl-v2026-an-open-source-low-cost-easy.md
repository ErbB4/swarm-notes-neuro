---
# CSL-compatible fields
title: "OpenWaveLogger v2026 (OWL-v2026): an open source, low cost, easy to build, high performance logger for wave data measurements"
author:
  - literal: "Jean Rabault"
  - literal: "Joey Voermans"
  - literal: "Takuji Waseda"
  - literal: "Takehiko Nose"
  - literal: "Tsubasa Kodaira"
  - literal: "Koya Sato"
  - literal: "ALEXANDER BABANIN"
  - literal: "Gaute Hope"
  - literal: "Malte Müller"
  - literal: "Lars Willas Dreyer"
  - literal: "Øystein Lande"
  - literal: "Atle Jensen"
  - literal: "Øyvind Breivik"
issued:
  date-parts:
    - [2026, 4, 22]
url: "https://arxiv.org/abs/2604.20502"

# Custom fields
paper_id: "2604.20502"
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
processed_at: "2026-04-25T05:38:12Z"
created_at: "2026-04-25T05:38:12Z"
---

# OpenWaveLogger v2026 (OWL-v2026): an open source, low cost, easy to build, high performance logger for wave data measurements

**Authors**: Jean Rabault, Joey Voermans, Takuji Waseda, Takehiko Nose, Tsubasa Kodaira, Koya Sato, ALEXANDER BABANIN, Gaute Hope, Malte Müller, Lars Willas Dreyer, Øystein Lande, Atle Jensen, Øyvind Breivik
**Date**: 2026-04-22
**Paper ID**: [openalex:2604.20502](https://arxiv.org/abs/2604.20502)

## Summary

The OpenWaveLogger (OWL-v2026) is an open-source, low-cost platform designed for high-performance in-situ ocean wave measurements. By leveraging off-the-shelf components, the system enables researchers to collect full high-frequency time series (IMU and GNSS data) that are often inaccessible via telemetry-limited buoy networks. It achieves high-precision absolute UTC timestamping through GNSS pulse-per-second synchronization and offers reliable long-term battery autonomy for field deployments.

## Key Contributions

- Introduces the OpenWaveLogger (OWL-v2026), a low-cost (~$220) open-source hardware solution for high-frequency in-situ wave data acquisition.
- Provides a custom firmware implementation enabling low-jitter, six-axis IMU logging at up to 416Hz and GNSS-synchronized timestamping with sub-10ms accuracy.
- Demonstrates sustained 10-day continuous operation at 208Hz with 20-day autonomy on standard D-cell battery configurations.

## Open Questions & Future Work

- [[embedded-high-frequency-write-latency-bottleneck]]

## Archivist Review

This paper presents a hardware-focused contribution rather than an ML methodology. While the technical challenge of high-frequency data logging is relevant to time-series acquisition, the hardware design itself is not a reusable ML concept or framework. The open question regarding write latency is approved as it represents a fundamental physical bottleneck in long-term, high-frequency time-series data collection.

### Approved Open Questions
- Embedded High-Frequency Write Bottleneck: This bottleneck limits the scaling of sampling rates for long-term unattended field deployments where memory resources are constrained and data integrity is paramount.

### Rejected Candidates
- [open_question] SD card write latency bottlenecks (`sd-card-write-latency-bottleneck`) - other: Renamed to be more descriptive of the broader embedded constraint.

## Links

- [Abstract](https://arxiv.org/abs/2604.20502)
- [PDF](https://arxiv.org/pdf/2604.20502)

