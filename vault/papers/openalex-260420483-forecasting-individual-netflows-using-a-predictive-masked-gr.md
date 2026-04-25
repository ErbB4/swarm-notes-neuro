---
# CSL-compatible fields
title: "Forecasting Individual NetFlows using a Predictive Masked Graph Autoencoder"
author:
  - literal: "Georgios Anyfantis"
  - literal: "Pere Barlet-Ros"
issued:
  date-parts:
    - [2026, 4, 22]
url: "https://arxiv.org/abs/2604.20483"

# Custom fields
paper_id: "2604.20483"
paper_source: "openalex"
domain: "nlp"
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
processed_at: "2026-04-25T05:37:46Z"
created_at: "2026-04-25T05:37:46Z"
---

# Forecasting Individual NetFlows using a Predictive Masked Graph Autoencoder

**Authors**: Georgios Anyfantis, Pere Barlet-Ros
**Date**: 2026-04-22
**Paper ID**: [openalex:2604.20483](https://arxiv.org/abs/2604.20483)

## Summary

This paper proposes a Graph Neural Network (GNN) approach for predicting individual network flow (NetFlow) traffic by modeling network activity as a series of heterogeneous bidirectional graphs. The model uses sliding windows to capture temporal dependencies between IP, Port, and Connection nodes, enabling both structural and feature-based forecasting. Results demonstrate that the GNN framework excels at predicting connection attachment points while maintaining competitive performance on feature reconstruction tasks compared to established forecasting baselines.

## Key Contributions

- Introduces a GNN-based framework for per-flow NetFlow traffic prediction using heterogeneous graph representations of network connections.
- Demonstrates effective modeling of temporal evolution of both graph topology (IP/Port connections) and connection-specific features.
- Achieves superior performance in predicting flow attachment points (IP/Port) compared to standard time-series baselines.

## Open Questions & Future Work

- [[variable-graph-size-forecasting]]

## Archivist Review

The paper provides a specific application of GNNs to NetFlow prediction, but the architecture itself is a standard composition of known techniques (GNNs + masked autoencoders) rather than a novel, reusable concept. The open question regarding variable-size graph forecasting is a meaningful bottleneck in spatiotemporal network modeling, thus it was approved.

### Approved Open Questions
- Variable Graph Size Forecasting: Fixed-size constraints limit the scalability and realism of graph-based network traffic forecasting, acting as a critical bottleneck for production-grade deployment.

### Rejected Candidates
- [concept] Predictive Masked Graph Autoencoder (`predictive-masked-graph-autoencoder`) - not_novel: The proposed architecture is a straightforward application of masked autoencoders to graphs, lacking the distinct conceptual novelty required for a standalone vault entry.

## Links

- [Abstract](https://arxiv.org/abs/2604.20483)
- [PDF](https://arxiv.org/pdf/2604.20483)

