---
# CSL-compatible fields
title: "Prior elicitation for Bayesian estimation of single-subject connectivity networks"
author:
  - literal: "Yiye Jiang"
  - literal: "Alice Chevaux"
  - literal: "Wendy Meiring"
  - literal: "Alex Petersen"
  - literal: "Guillaume Kon Kam King"
  - literal: "Julyan Arbel"
  - literal: "Sophie Achard"
issued:
  date-parts:
    - [2026, 5, 4]
url: "https://arxiv.org/abs/2605.02587"

# Custom fields
paper_id: "2605.02587"
paper_source: "openalex"
domain: "neuroimaging"
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
processed_at: "2026-05-07T06:04:54Z"
created_at: "2026-05-07T06:04:54Z"
---

# Prior elicitation for Bayesian estimation of single-subject connectivity networks

**Authors**: Yiye Jiang, Alice Chevaux, Wendy Meiring, Alex Petersen, Guillaume Kon Kam King, Julyan Arbel, Sophie Achard
**Date**: 2026-05-04
**Paper ID**: [openalex:2605.02587](https://arxiv.org/abs/2605.02587)

## Summary

This paper addresses the challenge of inferring functional connectivity networks from single-subject resting-state fMRI data by leveraging Bayesian estimation. The authors propose novel priors on correlation matrices coupled with an elicitation framework that allows domain experts to translate expectations into robust hyperparameter choices. By moving beyond point estimation to inferring posterior distributions, the approach enables uncertainty quantification and rigorous significance testing for individual connectivity edges. Experimental results demonstrate that the method outperforms existing single-subject Bayesian models in connectivity accuracy.

## Key Contributions

- Introduces a Bayesian framework for single-subject functional connectivity network inference from resting-state fMRI.
- Develops a prior elicitation procedure that maps expert beliefs into hyperparameter configurations for correlation matrix priors.
- Provides a methodology for identifying significant connectivity edges using posterior distributions and credible sets.

## Open Questions & Future Work

- [[fixed-weight-mixture-posterior-robustness]]

## Archivist Review

I have approved the open question regarding fixed-weight mixture posteriors as it addresses a fundamental limitation in Bayesian inference robustness. The proposed concept of a 'prior elicitation framework' was rejected because it lacks the necessary level of methodological abstraction required for a generalizable vault concept beyond its specific neuroimaging application.

### Approved Open Questions
- Fixed-weight mixture posterior robustness: This addresses a fundamental limitation of the standard Bayes rule in mixture models by preventing beneficial, robust shrinkage components from vanishing during posterior updates when evidence is sparse.

### Rejected Candidates
- [concept] Bayesian prior elicitation framework (`bayesian-prior-elicitation-framework`) - paper_local: The framework is specific to neuroimaging connectivity correlation matrices and does not generalize as a distinct, reusable methodology outside of this application.

## Links

- [Abstract](https://arxiv.org/abs/2605.02587)
- [PDF](https://arxiv.org/pdf/2605.02587)

