---
title: Investigating RAG-based Approaches in Clinical Trial and Patient Matching
abstract: 'The task of matching clinical trials and patients involves predicting whether
  a patient meets the eligibility criteria of a clinical trial, via evidences from
  patient records, such as clinical notes. Given that both the trial eligibility criteria
  and the clinical notes of patients are unstructured texts, Large Language Models
  (LLMs) hold the potential to improve performance on this task. Nevertheless, LLMs
  come with their own challenges of transparency and accountability. Current methods
  use Retrieval-Augmented Generation (RAG) in order to predict patient eligibility.
  In this work, we systematically investigate three aspects of these RAG-based approaches:
  (i) the complexity of the task, (ii) data retrieval for longitudinal records, and
  (iii) the effect of abstention on prediction quality. We show that criteria complexity,
  model abstention and chunking longitudinal patient records have noticeable effects
  on model performance. We also show that the choice of embedding models and ranking
  methods has little effect on the evidences retrieved from patient history. We hope
  that the findings of our study encourage research in improving the transparency
  and accountability of RAG approaches in clinical decision-making tasks.'
software: https://github.com/leontramontini97/clinical_trial-patient_matching
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: leon-tramontini26a
month: 0
tex_title: Investigating {RAG}-based Approaches in Clinical Trial and Patient Matching
firstpage: 76
lastpage: 87
page: 76-87
order: 76
cycles: false
bibtex_author: Le{\'o}n Tramontini, Daniel and Ghosh, Shrestha and Eickhoff, Carsten
author:
- given: Daniel
  family: León Tramontini
- given: Shrestha
  family: Ghosh
- given: Carsten
  family: Eickhoff
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
pdf: https://raw.githubusercontent.com/mlresearch/v297/main/assets/leon-tramontini26a/leon-tramontini26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
