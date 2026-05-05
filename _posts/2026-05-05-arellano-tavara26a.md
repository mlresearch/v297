---
title: 'Prostate-VarBench: A Benchmark with Interpretable TabNet Framework for Prostate
  Cancer Variant Classification'
abstract: Variants of Uncertain Significance ({VUS}) limit the clinical utility of
  prostate cancer genomics by delaying diagnosis and therapy when evidence for pathogenicity
  or benignity is incomplete. Progress is further limited by inconsistent annotations
  across sources and the absence of a prostate-specific benchmark for fair comparison.
  We introduce Prostate-VarBench, a curated pipeline for creating prostate-specific
  benchmarks that integrates {COSMIC} (somatic cancer mutations), ClinVar (expert-curated
  clinical variants), and {TCGA}-{PRAD} (prostate tumor genomics from The Cancer Genome
  Atlas) into a harmonized dataset of 193,278 variants supporting patient- or gene-aware
  splits to prevent data leakage. To ensure data integrity, we corrected a Variant
  Effect Predictor ({VEP}) issue that merged multiple transcript records, introducing
  ambiguity in clinical significance fields. We then standardized 56 interpretable
  features across eight clinically relevant tiers, including population frequency,
  variant type, and clinical context. AlphaMissense pathogenicity scores were incorporated
  to enhance missense variant classification and reduce {VUS} uncertainty. Building
  on this resource, we trained an interpretable TabNet model to classify variant pathogenicity,
  whose step-wise sparse masks provide per-case rationales consistent with molecular
  tumor board review practices. On the held-out test set, the model achieved 89.9%
  accuracy with balanced class metrics and the {VEP} correction yields an 6.5% absolute
  reduction in {VUS}.
software: https://github.com/AbrahamArellano/uiuc-cancer-research/
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: arellano-tavara26a
month: 0
tex_title: 'Prostate-VarBench: A Benchmark with Interpretable TabNet Framework for
  Prostate Cancer Variant Classification'
firstpage: 886
lastpage: 897
page: 886-897
order: 886
cycles: false
bibtex_author: Arellano Tavara, Abraham Francisco and Kumar, Umesh and Pradeepkumar,
  Jathurshan and Sun, Jimeng
author:
- given: Abraham Francisco
  family: Arellano Tavara
- given: Umesh
  family: Kumar
- given: Jathurshan
  family: Pradeepkumar
- given: Jimeng
  family: Sun
date: 2026-05-05
address:
container-title: Proceedings of the Fifth Machine Learning for Health Symposium
volume: '297'
genre: inproceedings
issued:
  date-parts:
  - 2026
  - 5
  - 5
pdf: https://raw.githubusercontent.com/mlresearch/v297/main/assets/arellano-tavara26a/arellano-tavara26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
