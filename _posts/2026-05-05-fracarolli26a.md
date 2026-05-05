---
title: Embedding-Space Data Augmentation to Prevent Membership Inference Attacks in
  Clinical Time Series Forecasting
abstract: Balancing strong privacy guarantees with high predictive performance is
  critical for time series forecasting ({TSF}) tasks involving Electronic Health Records
  ({EHR}). In this study, we explore how data augmentation can mitigate Membership
  Inference Attacks ({MIA}) on {TSF} models. We show that retraining with synthetic
  data can substantially reduce the effectiveness of loss-based {MIA}s by reducing
  the attacker’s true-positive to false-positive ratio. The key challenge is generating
  synthetic samples that closely resemble the original training data to confuse the
  attacker, while also introducing enough novelty to enhance the model’s ability to
  generalize to unseen data. We examine multiple augmentation strategies — Zeroth-Order
  Optimization ({ZOO}), a variant of {ZOO} constrained by Principal Component Analysis
  ({ZOO-PCA}), and {MixUp} — to strengthen model resilience without sacrificing accuracy.
  Our experimental results show that {ZOO-PCA} yields the best reductions in {TPR/FPR}
  ratio for {MIA} attacks without sacrificing performance on test data.
software: https://github.com/MariusFracarolli/ML4H_2025_Data-Augmentation-to-Prevent-MIA-in-TSF/
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: fracarolli26a
month: 0
tex_title: Embedding-Space Data Augmentation to Prevent Membership Inference Attacks
  in Clinical Time Series Forecasting
firstpage: 1412
lastpage: 1426
page: 1412-1426
order: 1412
cycles: false
bibtex_author: Fracarolli, Marius and Staniek, Michael and Riezler, Stefan
author:
- given: Marius
  family: Fracarolli
- given: Michael
  family: Staniek
- given: Stefan
  family: Riezler
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
pdf: https://raw.githubusercontent.com/mlresearch/v297/main/assets/fracarolli26a/fracarolli26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
