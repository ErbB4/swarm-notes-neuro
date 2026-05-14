---
created_at: '2026-05-14T06:10:53Z'
source_papers:
- '[[openalex-260510650-a-random-matrix-criterion-for-initializing-gated-recurrent-n]]'
title: Expressivity of zero-bias gated RNNs
---

**Background:** The stability of recurrent neural networks is influenced by the symmetry of hidden-state dynamics, which is typically preserved in zero-bias settings but broken when bias is introduced. Multiplicative gating mechanisms in architectures like LSTMs and GRUs further break the odd symmetry found in vanilla RNNs.

**Question / Future Work:** It remains an open research question whether the constraint imposed by zero-bias symmetry reduces the practical representational expressivity of gated recurrent neural networks compared to biased variants where this symmetry is explicitly broken.

**Why It Matters:** Determining the impact of symmetry constraints on expressivity is fundamental to understanding the design limits of reservoir computing architectures.

**Evidence:** it remains an open question whether the constraint reduces in practice the expressivity of the gated network.