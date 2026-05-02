---
created_at: '2026-05-02T05:50:22Z'
source_papers:
- '[[openalex-260426240-reduced-order-modeling-of-a-viscoelastic-turbulent-jet-with]]'
title: Multi-scale turbulent dynamics bottleneck
---

**Background:** Proper orthogonal decomposition (POD) is a standard linear dimensionality reduction technique used in fluid mechanics, but it often struggles to capture the complex, multi-scale dynamics of turbulent flows without requiring a large number of modes. While hybrid models can combine POD with deep learning to mitigate this, they face challenges in balancing computational efficiency with the faithful representation of fine-scale turbulent features.

**Question / Future Work:** There is a need to determine the optimal trade-off between the number of POD modes utilized and the capacity of the associated neural network to capture multi-scale turbulent dynamics, particularly as the complexity of the viscoelastic flow increases. Further research is required to refine these hybrid models to accurately capture small-scale features in the wake of the jet without the excessive computational cost associated with high-dimensional latent spaces.

**Why It Matters:** Understanding how to effectively represent multi-scale turbulent dynamics in ROMs is essential for balancing predictive accuracy, model interpretability, and computational cost, especially for high-Weissenberg number viscoelastic flows where simulation is prohibitively expensive.

**Evidence:** Even though the model still underperforms reproducing the dynamics in the wake, the prediction is significantly improved in the near-field, where the POD-rDL is able to capture more complex dynamics in the flow compared to the model that uses 25 POD modes.