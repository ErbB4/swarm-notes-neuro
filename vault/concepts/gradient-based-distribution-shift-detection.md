---
title: "Gradient-Based Distribution Shift Detection"
slug: "gradient-based-distribution-shift-detection"
type: concept
generated_stub: true
source_papers:
  - "[[openalex-260412425-forecasting-the-past-gradient-based-distribution-shift-detec]]"
processed_at: "2026-04-17T05:46:04Z"
created_at: "2026-04-17T05:46:04Z"
---

# Gradient-Based Distribution Shift Detection

> *Auto-generated stub. Edit this file to add more details.*

A post-hoc, self-supervised method for detecting distribution shifts by monitoring the gradient norm of a secondary trajectory forecasting task.


## Why It Matters

This technique enables post-hoc, non-intrusive detection of distribution shifts in trajectory models, a critical requirement for safety in autonomous systems.

## Evidence

> The L2 norm of the gradient of this forecasting loss with respect to the decoder's final layer defines a score to identify distribution shifts.

## Related Papers

- [[openalex-260412425-forecasting-the-past-gradient-based-distribution-shift-detec]]
