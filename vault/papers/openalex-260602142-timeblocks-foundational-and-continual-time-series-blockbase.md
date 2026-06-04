---
# CSL-compatible fields
title: "TimeBlocks: Foundational and Continual Time-Series Blockbase -- Extended Version"
author:
  - literal: "David Campos"
  - literal: "Bin Yang"
  - literal: "Tung Kieu"
  - literal: "Lei Chen"
  - literal: "Chenjuan Guo"
  - literal: "Christian S. Jensen"
issued:
  date-parts:
    - [2026, 6, 1]
url: "https://arxiv.org/abs/2606.02142"

# Custom fields
paper_id: "2606.02142"
paper_source: "openalex"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "timeblocks-framework"
  - "streamcore"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-06-04T06:34:01Z"
created_at: "2026-06-04T06:34:01Z"
---

# TimeBlocks: Foundational and Continual Time-Series Blockbase -- Extended Version

**Authors**: David Campos, Bin Yang, Tung Kieu, Lei Chen, Chenjuan Guo, Christian S. Jensen
**Date**: 2026-06-01
**Paper ID**: [openalex:2606.02142](https://arxiv.org/abs/2606.02142)

## Summary

TimeBlocks is a lightweight, modular framework designed for real-time time-series stream processing by dynamically routing interchangeable model blocks. To address the limitations of static, large-scale foundational models, it incorporates StreamCore for continuous calibration via representative stream subsetting. This approach enables the construction of task-specific, hardware-efficient models capable of adapting to non-stationary environments. Evaluation across multiple datasets shows superior performance compared to existing models under stringent computational constraints.

## Key Contributions

- Introduces TimeBlocks, a modular framework that constructs lightweight time-series models from an interchangeable block pool.
- Implements StreamCore, a streaming data subset selection method ensuring guaranteed approximations for continual model calibration.
- Demonstrates that TimeBlocks-derived models outperform traditional baselines in computational efficiency and predictive accuracy across multiple streaming tasks.

## Key Concepts

- [[timeblocks-framework]]: A modular framework that constructs lightweight time-series models from a pool of interchangeable blocks using a dynamic routing strategy.
- [[streamcore]]: A data streaming subset selection method that maintains a guaranteed approximation of the stream for continual calibration.

## Archivist Review

I approved the TimeBlocks framework and the StreamCore mechanism as they represent a significant departure from monolithic foundation models toward modular, continual, and hardware-efficient time-series processing. The review adhered to the selective policy by filtering out routine benchmarks and generic task descriptions, focusing only on the novel architectural and calibration primitives introduced in the paper. No datasets were approved as none provided explicit novelty or foundational standing within the vault's standards.

### Approved Concepts
- TimeBlocks Framework: The framework provides a distinct approach to constructing lightweight models by assembling modular components rather than using monolithic architectures.
- StreamCore: This mechanism addresses the fundamental problem of continual model calibration in resource-constrained streaming contexts.

### Rejected Candidates
- [concept] TimeBlocks (`timeblocks-framework`) - duplicate_existing: Renamed to match specific framework naming convention.

## Links

- [Abstract](https://arxiv.org/abs/2606.02142)
- [PDF](https://arxiv.org/pdf/2606.02142)

