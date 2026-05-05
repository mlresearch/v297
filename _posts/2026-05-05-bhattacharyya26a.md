---
title: Offline Surgical QA with Decomposed Retrieval and Synthesis for Resource-Constrained
  Settings
abstract: Digital access to critical medical knowledge in resource-limited settings
  is often hindered by a lack of internet connectivity and the computational demands
  of {AI} systems. This paper introduces the Surgical Information Assistant, a fully
  deployable, large language model ({LLM})-driven multi-agent system designed to provide
  reliable surgical information in offline, resource-constrained environments. Our
  system is powered by a workflow that orchestrates question decomposition, information
  retrieval, grounded generation, and information synthesis to perform complex reasoning
  on consumer-grade hardware. Grounded in the Open Manual of Surgery for Resource-Limited
  Settings, we evaluated DeRetSyn on a new question-answer ({QA}) dataset of over
  14,000 surgical question-answer pairs. We compare our system to other alternatives,
  perform ablation experiments on components of the agentic system, and interrogate
  sensitivity to retrieval parameters. The results show that our agentic orchestration
  enables a compact 3B Llama model to achieve 63% top-1 accuracy, significantly outperforming
  both a baseline GPT-4o (42.5%) and a larger 8B Llama model with conventional {RAG}
  (53%). We further test whether this performance enhancement from agentic orchestration
  for information retrieval generalizes to the PubMedQA dataset. Additionally, the
  entire system consumes <3.5 GB of RAM and generates responses within 8–15 seconds
  working on a consumer laptop. Our work serves as a practical blueprint for how agent-based
  systems can empower small, efficient models for medical domain information retrieval
  and synthesis, offering a tangible application of {AI} technology that could help
  advance health equity. We will release our dataset, code base, and prompts to foster
  further research in deployable and responsible clinical {AI}.
software: https://github.com/MiningMyBusiness/surgical-information-assistant
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: bhattacharyya26a
month: 0
tex_title: Offline Surgical QA with Decomposed Retrieval and Synthesis for Resource-Constrained
  Settings
firstpage: 449
lastpage: 472
page: 449-472
order: 449
cycles: false
bibtex_author: Bhattacharyya, Kiran
author:
- given: Kiran
  family: Bhattacharyya
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
pdf: https://raw.githubusercontent.com/mlresearch/v297/main/assets/bhattacharyya26a/bhattacharyya26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
