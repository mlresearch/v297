---
title: 'RELATE: Relation Extraction in Biomedical Abstracts with LLMs and Ontology
  Constraints'
abstract: 'Biomedical knowledge graphs ({KG}s) are vital for drug discovery and clinical
  decision support but remain incomplete. Large language models ({LLM}s) excel at
  extracting biomedical relations, yet their outputs lack standardization and alignment
  with ontologies, limiting {KG} integration with free texts. We introduce {RELATE},
  a three-stage pipeline that maps {LLM}-extracted relations to standardized ontology
  predicates, e.g., the Biolink Model. The pipeline includes: (1) ontology preprocessing
  with predicate embeddings, (2) similarity-based retrieval enhanced with SapBERT,
  and (3) {LLM}-based reranking with explicit negation handling. This approach performs
  relation extraction from free-text outputs to structured, ontology-constrained representations.
  On the ChemProt benchmark, {RELATE} achieves 52% exact match and 94% accuracy@10,
  and in 2,400 {HEAL} Project abstracts, it effectively rejects irrelevant associations
  (0.4%) and identifies negated assertions. {RELATE} captures nuanced biomedical relationships
  while ensuring quality for {KG} augmentation. By combining vector search with contextual
  {LLM} reasoning, {RELATE} provides a scalable, semantically accurate framework for
  converting unstructured biomedical literature into standardized {KG}s.'
software: https://github.com/RENCI-NER/pred-mapping/releases/tag/v1.0
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: olasunkanmi26a
month: 0
tex_title: "{RELATE}: Relation Extraction in Biomedical Abstracts with {LLM}s and
  Ontology Constraints"
firstpage: 1178
lastpage: 1193
page: 1178-1193
order: 1178
cycles: false
bibtex_author: Olasunkanmi, Olawumi and Satusky, Matthew and Yi, Hong and Bizon, Chris
  and Lee, Harlin and Ahalt, Stanley
author:
- given: Olawumi
  family: Olasunkanmi
- given: Matthew
  family: Satusky
- given: Hong
  family: Yi
- given: Chris
  family: Bizon
- given: Harlin
  family: Lee
- given: Stanley
  family: Ahalt
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
pdf: https://raw.githubusercontent.com/mlresearch/v297/main/assets/olasunkanmi26a/olasunkanmi26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
