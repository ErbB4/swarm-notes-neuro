---
# CSL-compatible fields
title: "Markov reads Pushkin, again: A statistical journey into the poetic world of Evgenij Onegin"
author:
  - literal: "Angelo Maria Sabatini"
issued:
  date-parts:
    - [2026, 4, 22]
url: "https://arxiv.org/abs/2604.20221"

# Custom fields
paper_id: "2604.20221"
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
processed_at: "2026-04-25T05:38:35Z"
created_at: "2026-04-25T05:38:35Z"
---

# Markov reads Pushkin, again: A statistical journey into the poetic world of Evgenij Onegin

**Authors**: Angelo Maria Sabatini
**Date**: 2026-04-22
**Paper ID**: [openalex:2604.20221](https://arxiv.org/abs/2604.20221)

## Summary

This paper investigates the phonological structure of Alexander Pushkin's Evgenij Onegin using symbolic time series analysis and Markov modeling. By encoding the text into binary sequences of vowels and consonants, the study constructs four-state Markov chains capable of reproducing essential sequential statistics such as memory depth and autocorrelation. The analysis uncovers structural asymmetries between the original Russian text and its Italian translation, suggesting that minimalist probabilistic models can effectively reveal latent stylistic and narrative regularities in complex poetry.

## Key Contributions

- Introduces a symbolic time series analysis framework using binary vowel/consonant encoding to model the phonological structure of poetic texts.
- Demonstrates that a compact four-state Markov chain effectively captures key sequential features, such as autocorrelation and memory depth, in literary compositions.
- Identifies structural differences in phonological memory depth between the original Russian Evgenij Onegin and its Italian translation using phonological probes.

## Open Questions & Future Work

- [[semantic-integration-in-symbolic-models]]

## Archivist Review

The paper applies standard Markovian modeling to literary texts as a form of stylized time series analysis. While the linguistic application is interesting, the methodology does not introduce novel, reusable ML concepts that fit the current vault's focus on temporal forecasting and representation learning. I have approved the open question regarding semantic integration as it represents a meaningful limitation in applying symbolic models to complex sequential data.

### Approved Open Questions
- Semantic Integration in Symbolic Models: This question addresses the fundamental interpretability gap in computational stylometry, moving beyond surface statistical patterns toward modeling the interplay between form and content.

### Rejected Candidates
- [concept] Phonological probes (`phonological-probes`) - paper_local: This is a specific application-level tool for exploring the paper's text rather than a reusable machine learning framework for time series analysis.
- [concept] Symbolic time series V/C encoding (`symbolic-time-series-v-c-encoding`) - paper_local: Vowel/consonant encoding is a domain-specific representation for linguistics and does not constitute a reusable ML framework or method.

## Links

- [Abstract](https://arxiv.org/abs/2604.20221)
- [PDF](https://arxiv.org/pdf/2604.20221)

