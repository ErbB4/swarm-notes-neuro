---
# CSL-compatible fields
title: "Cross-Representation Benchmarking in Time-Series Electronic Health Records for Clinical Outcome Prediction"
author:
  - literal: "Tianyi Chen"
  - literal: "Min Zhu"
  - literal: "Zhiyao Luo"
  - literal: "Tingting Zhu"
issued:
  date-parts:
    - [2026, 4, 21]
url: "https://arxiv.org/abs/2510.09159"

# Custom fields
paper_id: "2510.09159"
paper_source: "openalex"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  - "mimic-iv"
  - "ehrshot"
concept_slugs:
  []
dataset_slugs:
  - "mimic-iv"
  - "ehrshot"
skill: "TimeSeriesSkill"
processed_at: "2026-04-24T05:50:45Z"
created_at: "2026-04-24T05:50:45Z"
---

# Cross-Representation Benchmarking in Time-Series Electronic Health Records for Clinical Outcome Prediction

**Authors**: Tianyi Chen, Min Zhu, Zhiyao Luo, Tingting Zhu
**Date**: 2026-04-21
**Paper ID**: [openalex:2510.09159](https://arxiv.org/abs/2510.09159)

## Summary

This paper provides a systematic, reproducible benchmark for evaluating patient data representations in clinical outcome prediction tasks. By standardizing evaluation across diverse modalities—multivariate time-series, event streams, and textual inputs for LLMs—the authors compare established modeling families like Transformers, CLMBR, and LLMs. The results indicate that event stream representations are generally superior, while optimal feature selection strategies are highly dependent on the specific clinical task and setting.

## Key Contributions

- Introduces the first systematic benchmark comparing EHR representation methods including multivariate time-series, event streams, and textual event streams.
- Identifies that event stream models outperform others in clinical outcome prediction across both ICU and longitudinal care settings.
- Demonstrates that feature selection strategy requirements depend on the clinical context, with ICU tasks favoring feature pruning and longitudinal tasks favoring retention of sparse features.

## Open Questions & Future Work

- [[optimal-ehr-representation-for-clinical-context]]

## Archivist Review

This paper provides a valuable benchmarking study for clinical time-series, but it primarily compares existing representation paradigms rather than proposing new ones. I approved the datasets for their value in the clinical EHR domain and the open question regarding the fundamental trade-offs in clinical representation selection.

### Approved Open Questions
- Optimal EHR Representation Method: Establishing which representation is most effective for specific clinical contexts is critical for developing reliable, scalable, and computationally efficient clinical decision support tools.

### Rejected Candidates
- [concept] EHR Representation Benchmarking Paradigm (`ehr-representation-benchmarking-paradigm`) - not_novel: The paper provides a benchmark study, but does not define a new, distinct methodological concept or framework that would be used by future papers independently of this specific benchmark.

## Datasets

- [[mimic-iv]]
- [[ehrshot]]

## Links

- [Abstract](https://arxiv.org/abs/2510.09159)
- [PDF](https://arxiv.org/pdf/2510.09159)

