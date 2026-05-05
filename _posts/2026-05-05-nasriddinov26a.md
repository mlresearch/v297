---
title: 'Generating Natural-Language Surgical Feedback: From Structured Representation
  to Domain-Grounded Evaluation'
abstract: 'High-quality intraoperative feedback from a surgical trainer is pivotal
  for improving trainee performance and long-term skill acquisition. Automating natural,
  trainer-style feedback promises timely, accessible, and consistent guidance at scale–but
  requires models that understand clinically relevant representations. We present
  a structure-aware pipeline that learns a surgical action ontology from real trainer-to-trainee
  transcripts (33 surgeries) and uses it to condition feedback generation. We contribute
  by 1) mining Instrument-Action-Target ({IAT}) triplets from real-world feedback
  text and clustering surface forms into normalized categories, 2) fine-tuning a video-to-{IAT}
  model that leverages the surgical procedure and task contexts, as well as fine-grained
  temporal instrument motion (crucial for representing instruments and actions over
  time), and 3) demonstrating how to effectively leverage {IAT} triplet representation
  to guide {GPT}-4o in generating clinically-grounded natural, trainer-style feedback.
  We show that, on Task 1: Video-to-{IAT} recognition, our context injection and temporal
  tracking deliver consistent {AUC} gains – Instrument: 0.67 to 0.74, Action: 0.60
  to 0.63, Tissue: 0.74 to 0.79. For Task 2: Feedback text generation (1 [opposite/unsafe]
  - 3 [admissible] - 5 [perfect match] fidelity rubric against human trainer), {GPT}-4o
  from video alone scores 2.17; {IAT} conditioning reaches 2.44 (+12.4%), increasing
  the admissible generations with score $\geq$3: 21% to 42%. Traditional metrics also
  improve: Word Error Rate ({WER}): 15–31% lower and {ROUGE} (phrase/substring overlap):
  9–64% higher. Grounding generation in explicit {IAT} structure improves fidelity
  and yields clinician-verifiable rationales, supporting auditable use in surgical
  training.'
software: https://github.com/firdavsn/SurgFBGen
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: nasriddinov26a
month: 0
tex_title: 'Generating Natural-Language Surgical Feedback: From Structured Representation
  to Domain-Grounded Evaluation'
firstpage: 952
lastpage: 984
page: 952-984
order: 952
cycles: false
bibtex_author: Nasriddinov, Firdavs and Kocielnik, Rafal and Anandkumar, Anima and
  Hung, Andrew J.
author:
- given: Firdavs
  family: Nasriddinov
- given: Rafal
  family: Kocielnik
- given: Anima
  family: Anandkumar
- given: Andrew J.
  family: Hung
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
pdf: https://raw.githubusercontent.com/mlresearch/v297/main/assets/nasriddinov26a/nasriddinov26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
