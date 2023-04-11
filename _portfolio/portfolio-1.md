---
title: "Improving Metric Dimensionality Reduction with Distributed Topology"
excerpt: "<p>(with Elchanan Solomon and Paul Bendich) [arXiv preprint] We use our notion of distributed persistence and local geometry to define a new dimensionality-reduction algorithm called DIPOLE. <a href="https://arxiv.org/abs/2106.07613">[paper]</a>, <a href="https://github.com/aywagner/DIPOLE">[code]</a> </p> <img src='/images/mammoth.png'>" 
collection: portfolio
---

Abstract: We propose a novel approach to dimensionality reduction combining techniques of metric geometry and distributed persistent homology, in the form of a gradient-descent based method called DIPOLE. DIPOLE is a dimensionality-reduction post-processing step that corrects an initial embedding by minimizing a loss functional with both a local, metric term and a global, topological term. By fixing an initial embedding method (we use Isomap), DIPOLE can also be viewed as a full dimensionality-reduction pipeline. This framework is based on the strong theoretical and computational properties of distributed persistent homology and comes with the guarantee of almost sure convergence. We observe that DIPOLE outperforms popular methods like UMAP, t-SNE, and Isomap on a number of popular datasets, both visually and in terms of precise quantitative metrics. 

[paper](https://arxiv.org/abs/2106.07613), [code](https://github.com/aywagner/DIPOLE)
