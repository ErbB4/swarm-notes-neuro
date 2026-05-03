---
created_at: '2026-05-03T06:03:49Z'
source_papers:
- '[[openalex-260428161-ropedreamer-a-kinematic-recurrent-state-space-model-for-dyna]]'
title: Online System Identification Adaptation
---

**Background:** Robotic manipulation models trained in simulated environments often exhibit performance degradation when deployed on physical platforms due to discrepancies in material properties and environmental interactions. Bridging this sim-to-real gap requires adaptive methods capable of identifying and compensating for these varying parameters in real-time.

**Question / Future Work:** There is an unresolved need to integrate online system identification into latent dynamics models to allow them to adapt to varying physical material properties, such as cable stiffness or surface friction, during real-world deployment. Such adaptations are essential for closing the sim-to-real gap in high-dimensional deformable object manipulation.

**Why It Matters:** The authors explicitly mention this as a key research avenue for deploying their model on physical hardware, addressing the limitation that their current model is primarily evaluated in simulation.