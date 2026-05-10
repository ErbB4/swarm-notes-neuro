---
created_at: '2026-05-10T06:04:35Z'
source_papers:
- '[[openalex-260506438-neural-actuarial-longevity-forecasting-anchoring-lstms-for-e]]'
title: Adaptive Uncertainty Calibration
---

**Background:** Uncertainty quantification in mortality forecasting typically involves distinguishing between epistemic (model) and aleatoric (process) uncertainty.

**Question / Future Work:** The current reliance on historical variability for process uncertainty calibration assumes that demographic regimes remain stationary, which may not hold under extreme exogenous shocks. Research is required to develop adaptive uncertainty calibration methods that better account for non-stationary demographic processes and the fat-tailed nature of extreme shocks.

**Why It Matters:** Improving uncertainty quantification is critical for accurate regulatory capital calibration, particularly when models are used for long-term longevity risk management where extreme tail events have significant financial impact.

**Evidence:** If the demographic regime shifts fundamentally (e.g., through a medical breakthrough or a pandemic), the calibrated noise may underestimate or overestimate the true process variability. In particular, the Gaussian assumption underlying the process noise term may fail to capture the fat-tailed nature of extreme exogenous shocks... a fully adaptive uncertainty calibration remains an open challenge.