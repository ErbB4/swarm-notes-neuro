---
# CSL-compatible fields
title: "Spatiotemporal downscaling and nowcasting of urban land surface temperatures with deep neural networks"
author:
  - literal: "Solomiia Kurchaba"
  - literal: "Angela Meyer"
issued:
  date-parts:
    - [2026, 5, 13]
url: "https://arxiv.org/abs/2605.13566"

# Custom fields
paper_id: "2605.13566"
paper_source: "openalex"
domain: "computer-vision"
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
processed_at: "2026-05-16T06:02:18Z"
created_at: "2026-05-16T06:02:18Z"
---

# Spatiotemporal downscaling and nowcasting of urban land surface temperatures with deep neural networks

**Authors**: Solomiia Kurchaba, Angela Meyer
**Date**: 2026-05-13
**Paper ID**: [openalex:2605.13566](https://arxiv.org/abs/2605.13566)

## Summary

This paper addresses the spatiotemporal resolution trade-off in satellite-derived land surface temperature (LST) products by combining geostationary and polar-orbiting satellite data. A U-Net architecture is employed to downscale coarse-resolution data to 1 km at 15-minute intervals, which then serves as input for a ConvLSTM-based nowcasting model. The resulting framework provides accurate short-term intraday LST forecasts, outperforming standard statistical benchmarks in urban environments.

## Key Contributions

- Proposed a U-Net-based spatiotemporal downscaling framework that fuses SEVIRI and MODIS data to achieve 1 km spatial resolution at 15-minute intervals.
- Developed a ConvLSTM-based nowcasting model for urban land surface temperatures with lead times of 15 to 75 minutes.
- Achieved an RMSE of 1.92°C for downscaled LST estimation and outperformed persistence and climatological benchmarks for nowcasting (RMSE 0.57-1.15°C).

## Open Questions & Future Work

- [[annual-cycle-lst-generalization]]
- [[incorporating-physical-urban-drivers]]

## Archivist Review

The paper provides a straightforward application of U-Net and ConvLSTM to LST downscaling and nowcasting. As these are standard architectures, no new concepts are approved. The open questions regarding seasonal generalization and physical driver integration were approved as they represent non-trivial research bottlenecks in remote sensing-based spatiotemporal forecasting.

### Approved Open Questions
- Year-round LST model generalization: Generalization across seasons is critical for the practical, continuous operational use of satellite-based LST monitoring for urban heat and climate applications.
- Incorporating physical urban drivers: Explicit inclusion of physical drivers could improve model performance, robustness, and interpretability, especially in diverse urban environments where implicit encoding might fail.

## Links

- [Abstract](https://arxiv.org/abs/2605.13566)
- [PDF](https://arxiv.org/pdf/2605.13566)

