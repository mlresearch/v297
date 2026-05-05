---
title: Group-Sparse Manifold-Aware Integrated Gradients for Multimodal Transformers
  on EHR Trajectories
abstract: 'Integrated Gradients ({IG}) is a popular method for explaining clinical
  deep models—including widely used multimodal, pretrained Transformers—but its utility
  on {EHR} code sequences is hampered by (i) the lack of principled baselines for
  sequence of discrete tokens and (ii) dense, hard-to-interpret generated attributions.
  To address both, first, we introduce a manifold-aware baseline: the mean input embedding
  (computed on the validation set), which keeps {IG}’s interpolated points close to
  typical sequences in embedding space. Second, we introduce {GS-IG}, which preserves
  the straight path geometry but re-parameterizes the schedule $\alpha(t) = t^\theta$
  and selects $\theta$ per input by minimizing a token-level $\ell_{2,1}$ (group-sparsity)
  objective, producing concise, practitioner-friendly explanations. On {MIMIC-IV}
  (incident heart failure) and {MDC} (early mortality), the manifold-aware baseline
  improves faithfulness (higher Comprehensiveness, lower Sufficiency), and {GS-IG}
  reduces token-level $\ell_{2,1}$ by 9–18% with negligible change in those metrics
  on the manifold-aware baseline. The method is lightweight and yields faithful, sparse,
  and actionable explanations.'
software: https://github.com/ali-amirahmadii/Group-Sparse-IG
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: amirahmadi26a
month: 0
tex_title: Group-Sparse Manifold-Aware Integrated Gradients for Multimodal Transformers
  on EHR Trajectories
firstpage: 740
lastpage: 758
page: 740-758
order: 740
cycles: false
bibtex_author: Amirahmadi, Ali and Etminani, Farzaneh and Ohlsson, Mattias
author:
- given: Ali
  family: Amirahmadi
- given: Farzaneh
  family: Etminani
- given: Mattias
  family: Ohlsson
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
pdf: https://raw.githubusercontent.com/mlresearch/v297/main/assets/amirahmadi26a/amirahmadi26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
