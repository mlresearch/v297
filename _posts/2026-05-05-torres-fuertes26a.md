---
title: Uncertainty-Aware Logistic Regression with Gray-Zone Refinement for Predicting
  Response to Neoadjuvant Chemotherapy in Breast Cancer
abstract: Predicting response to neoadjuvant chemotherapy ({NAC}) in breast cancer
  remains a clinical challenge. We developed a machine learning framework combining
  bibliographically-weighted Elastic Net for dimensionality reduction with regularized
  Logistic Regression ({LR}) as the primary model, and a selective escalation strategy
  using a multilayer perceptron ({MLP}) for ambiguous predictions. From GSE205568
  (n=2551), 730 robust genes were selected. {LR} achieved strong performance (nested-{CV}
  {AUCPR} = 0.82, {ROC}-{AUC} = 0.93), but uncertainty analysis identified a “gray
  zone” near the decision threshold, concentrating misclassifications. Routing these
  cases to an {MLP} and aggregating outputs via stacking with isotonic recalibration
  improved gray-zone {AUCPR} by +0.24 and yielded perfect calibration ({ECE} $\approx$
  0). External validation on GSE25065 (n=198) showed that while discrimination transferred
  ({ROC}-{AUC} = 0.94, {AUCPR} = 0.76), recalibration and local threshold adjustment
  were required to recover clinically useful performance (F1 = 0.74, Recall = 0.95)
  (de Hond et al., 2023). These findings support the use of {LR} as a reliable baseline,
  augmented by explicit uncertainty detection and selective complexity to improve
  robustness in clinical prediction.
software: https://anonymous.4open.science/r/chemo-response-prediction-5785/
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: torres-fuertes26a
month: 0
tex_title: Uncertainty-Aware Logistic Regression with Gray-Zone Refinement for Predicting
  Response to Neoadjuvant Chemotherapy in Breast Cancer
firstpage: 1336
lastpage: 1345
page: 1336-1345
order: 1336
cycles: false
bibtex_author: Torres Fuertes, Aixa Ximena and Jara Cuya, Fatima R. and Romero Tello,
  Rodrigo and Sullon Silva, Jesus A. and Villegas Suarez, Ariana M.
author:
- given: Aixa Ximena
  family: Torres Fuertes
- given: Fatima R.
  family: Jara Cuya
- given: Rodrigo
  family: Romero Tello
- given: Jesus A.
  family: Sullon Silva
- given: Ariana M.
  family: Villegas Suarez
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
pdf: https://raw.githubusercontent.com/mlresearch/v297/main/assets/torres-fuertes26a/torres-fuertes26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
