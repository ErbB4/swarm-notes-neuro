---
created_at: '2026-05-01T06:04:49Z'
source_papers:
- '[[openalex-260425664-deflation-free-optimal-scoring]]'
title: DFSOS convergence rate characterization
---

**Background:** The proposed deflation-free sparse optimal scoring (DFSOS) algorithm utilizes a splitting method for orthogonally-constrained optimization that requires the selection of a penalty parameter for the augmented Lagrangian. While the algorithm is known to converge for sufficiently large penalty values, the precise rate of convergence remains theoretically uncharacterized.

**Question / Future Work:** Investigate and establish the convergence rates for the DFSOS algorithm to provide a deeper theoretical understanding of its performance and behavior, as the current results only guarantee convergence to a stationary point.

**Why It Matters:** Characterizing the convergence rate is essential for comparing DFSOS efficiency with other manifold optimization methods and for setting practical stopping criteria in large-scale applications.