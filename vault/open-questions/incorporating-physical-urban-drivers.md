---
created_at: '2026-05-16T06:02:18Z'
source_papers:
- '[[openalex-260513566-spatiotemporal-downscaling-and-nowcasting-of-urban-land-surf]]'
title: Incorporating physical urban drivers
---

**Background:** Urban Land Surface Temperature (LST) is influenced by various factors, including land cover composition, urban geometry, and anthropogenic activities. Current satellite-based models often implicitly encode these effects within the coarse-resolution input signal.

**Question / Future Work:** Future work is needed to systematically incorporate explicit auxiliary data—such as land cover, vegetation indices, urban morphology (e.g., sky view factor), and anthropogenic heat sources—into deep learning architectures to improve the physical interpretability and robustness of LST downscaling and nowcasting, particularly across heterogeneous urban environments. Integrating such features into models like ConvLSTM presents challenges in balancing spatial and temporal feature representation.

**Why It Matters:** Explicit inclusion of physical drivers could improve model performance, robustness, and interpretability, especially in diverse urban environments where implicit encoding might fail.