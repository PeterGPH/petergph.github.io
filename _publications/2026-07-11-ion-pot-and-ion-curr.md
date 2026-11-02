---
title: "Ion-Pot and Ion-Curr: Ion-Aware Benchmarks for Electrostatic Field and Observable Prediction in Complex Geometries"
collection: publications
permalink: /publication/2026-07-11-ion-pot-and-ion-curr
excerpt: 'Two paired benchmarks for ion-aware surrogate models: electrostatic potential fields around biomolecules at varying ionic concentration, and ionic current through nanopore geometries.'
date: 2026-07-11
venue: 'ICML 2026 Workshop on AI for Physics (AI4Physics)'
paperurl: 'https://openreview.net/forum?id=wuJjHvzTwC'
citation: 'Liu, Jingqian, Pinhao Gu, and Aleksei Aksimentiev. "Ion-Pot and Ion-Curr: Ion-Aware Benchmarks for Electrostatic Field and Observable Prediction in Complex Geometries." <i>ICML 2026 Workshop on AI for Physics (AI4Physics)</i>, Seoul, 2026.'
---

Ion-Pot and Ion-Curr are two benchmarks for machine-learned surrogates of ion-aware
electrostatics. Ion-Pot covers electrostatic potential fields around biomolecules across
a range of ionic concentrations, a high-dimensional field-reconstruction task. Ion-Curr
covers ionic current through complex nanopore geometries, an observable-level transport
task. Both are addressed with voxel-based convolutional models.

Two results stand out. Conditioning the model explicitly on ion concentration improves
prediction over baselines that take no ionic input. And the two tasks do not need models
of comparable size: the ionic-current task is modelled accurately by a lightweight
architecture of roughly 39K parameters, which suggests that the complexity a surrogate
needs depends on the structure of the target rather than on the complexity of the
underlying physics.

Presented as a poster at the AI4Physics workshop, ICML 2026, Seoul, on 11 July 2026.

[OpenReview](https://openreview.net/forum?id=wuJjHvzTwC) | [ICML page](https://icml.cc/virtual/2026/72563)
