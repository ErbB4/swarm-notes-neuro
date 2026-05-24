---
# CSL-compatible fields
title: "TimeGuard: Channel-wise Pool Training for Backdoor Defense in Time Series Forecasting"
author:
  - literal: "Quang Duc Nguyen"
  - literal: "Siyuan Liang"
  - literal: "Yiming Li"
  - literal: "Fushuo Huo"
  - literal: "Dacheng Tao"
issued:
  date-parts:
    - [2026, 5, 21]
url: "https://arxiv.org/abs/2605.22365"

# Custom fields
paper_id: "2605.22365"
paper_source: "openalex"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "channel-wise-pool-training"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-24T06:18:23Z"
created_at: "2026-05-24T06:18:23Z"
---

# TimeGuard: Channel-wise Pool Training for Backdoor Defense in Time Series Forecasting

**Authors**: Quang Duc Nguyen, Siyuan Liang, Yiming Li, Fushuo Huo, Dacheng Tao
**Date**: 2026-05-21
**Paper ID**: [openalex:2605.22365](https://arxiv.org/abs/2605.22365)

## Summary

This paper presents a systematic evaluation of backdoor defenses in time series forecasting, revealing that existing methods struggle due to channel-level signal dilution and training-loss degeneration. To address these issues, the authors introduce TimeGuard, a training-time defense mechanism that employs a channel-wise pool training strategy. By initializing a high-confidence data pool and refining it through distance-regularized loss selection, TimeGuard effectively sanitizes the training process without sacrificing accuracy on clean samples. Experimental results confirm significant robustness gains across diverse forecasting architectures and attack scenarios.

## Key Contributions

- Identified two fundamental failure modes of existing backdoor defenses in TSF: channel-level signal dilution and training-loss degeneration.
- Proposed TimeGuard, a training-time defense that utilizes channel-wise pool training and distance-regularized loss selection to improve robustness.
- Demonstrated that TimeGuard improves MAE_P by 1.96x over leading baselines while maintaining high performance on clean data.

## Key Concepts

- [[channel-wise-pool-training]]: A training-time backdoor defense paradigm for time series that isolates channel-specific signal patterns to prevent the dilution caused by contaminated windows.

## Archivist Review

I approved 'Channel-wise Pool Training' because it captures a distinct, reusable paradigm for addressing backdoor threats in multivariate time series where channel dependency often complicates sample-level filtering. The overarching framework 'TimeGuard' was rejected as it is a specific implementation of these principles, and I followed the policy to favor more fundamental, reusable sub-mechanisms.

### Approved Concepts
- Channel-wise Pool Training: It addresses the specific challenge of channel-level signal dilution in time series backdoor defense by isolating signals within channels to prevent poisoning contamination.

### Rejected Candidates
- [concept] TimeGuard (`timeguard`) - subcomponent_of_broader_mechanism: This is the name of the overall framework; the individual core mechanisms (channel-wise pool training) are more reusable as concepts.

## Links

- [Abstract](https://arxiv.org/abs/2605.22365)
- [PDF](https://arxiv.org/pdf/2605.22365)

