---
layout: paper
title: Toward Feature-Preserving 2D and 3D Vector Field Compression
authors:  Xin Liang, Hanqi Guo, Sheng Di, Franck Cappello, Mukund Raj, Chunhui Liu, Kenji Ono, Zizhong Chen and Tom Peterka
journal: IEEE Pacific Visualization Symposium
order: 2020-02
pubdate: May 2020
image: /mraj/images/liang_2020.png
image_text: Compressed data comparison with various methods
links:
- path: "https://ieeexplore.ieee.org/document/9086223"
  title: paper
- path: "bib/liang_2020.bib"
  title: bibtex
category: all
---

The objective of this work is to develop error-bounded lossy compression
methods to preserve topological features in 2D and 3D vector fields.
Specifically, we explore the preservation of critical points in piecewise
linear vector fields. We define the preservation of critical points as, without
any false positive, false negative, or false type change in the decompressed
data, (1) keeping each critical point in its original cell and (2) retaining
the type of each critical point (e.g., saddle and attracting node). The key to
our method is to adapt a vertex-wise error bound for each grid point and to
compress input data together with the error bound field using a modified lossy
compressor. Our compression algorithm can be also embarrassingly parallelized
for large data handling and in situ processing. We benchmark our method by
comparing it with existing lossy compressors in terms of false
positive/negative/type rates, compression ratio, and various vector field
visualizations with several scientific applications.
