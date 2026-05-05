---
title: 'Topoformer: Topology-Infused Transformers for Medical Imaging'
abstract: Deep learning has transformed 2D medical imaging, but scaling to 3D volumes
  remains difficult due to high compute, scarce annotations, and the loss of global
  context in patch-based pipelines. We present Topoformer, a transformer framework
  that makes 3D classification both data- and compute-efficient by integrating topological
  priors. First, we introduce a sliding-band cubical filtration that replaces a single
  global persistent-homology pass with overlapping intensity bands, yielding an ordered
  sequence of Betti tokens (components, tunnels, cavities). These tokens act as transformer
  inputs, enabling multi-scale topological reasoning without early saturation. Second,
  we propose Topological Supervised Contrastive Learning (TopoSupCon), which treats
  the image and its label-preserving topological view as complementary modalities,
  reducing reliance on brittle geometric or generative augmentations. A lightweight
  TopoGate further lets the image softly weight multiple band widths per case. On
  3D brain MRI tumor grading and chest CT benchmarks in low-data regimes, Topoformer
  achieves consistent gains over strong 3D CNN and ViT baselines, including improvements
  up to 12 AUC points and 8 accuracy points. Our results show that sequential, topology-aware
  representations provide a powerful inductive bias for volumetric medical image analysis.
software: https://github.com/philmorefkoung/Topoformer
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: chakraborty26a
month: 0
tex_title: "{Topoformer}: Topology-Infused Transformers for Medical Imaging"
firstpage: 23
lastpage: 40
page: 23-40
order: 23
cycles: false
bibtex_author: Chakraborty, Sayoni and Koung, Philmore and Coskunuzer, Baris
author:
- given: Sayoni
  family: Chakraborty
- given: Philmore
  family: Koung
- given: Baris
  family: Coskunuzer
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
pdf: https://raw.githubusercontent.com/mlresearch/v297/main/assets/chakraborty26a/chakraborty26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
