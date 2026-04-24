---
created_at: '2026-04-24T05:52:33Z'
source_papers:
- '[[openalex-250913178-covariance-filters-and-neural-networks-over-hilbert-spaces]]'
title: HVN Convergence and Transferability Bottleneck
---

**Background:** Discrete Hilbert coVariance Filters (HVF) and Networks (HVN) are defined by the empirical covariance operator of sampled signals within a Hilbert space. The convergence of these discrete approximations to their infinite-dimensional counterparts as the discretization resolution increases remains to be established.

**Question / Future Work:** It is unknown how the discrete implementations of Hilbert coVariance Filters and Networks converge to the underlying infinite-dimensional operators as the discretization resolution (number of samples or discretization points) increases. Formal analysis of this convergence, as well as the associated transferability properties when moving between different discretization resolutions or Hilbert spaces, is required.

**Why It Matters:** Establishing convergence and transferability is fundamental for justifying the use of empirical, finite-dimensional neural network architectures as reliable approximations of theoretical models defined in infinite-dimensional Hilbert spaces.