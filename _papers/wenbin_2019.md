---
layout: paper
title: InSituNet Deep Image Synthesis for Parameter Space Exploration of Ensemble Simulations
authors: Wenbin He, Junpeng Wang, Hanqi Guo, Ko-Chih Wang, Han-Wei Shen, Mukund Raj, Youssef S. G. Nashed and Tom Peterka 
journal: IEEE Transactions on Visualization and Computer Graphics
order: 2019-01
pubdate: August 2019
image: /mraj/images/wenbin_2019.png
image_text: Predicted images of the MPAS-Ocean dataset for different isosurfaces and viewpoints
links:
- path: "https://ieeexplore.ieee.org/document/8805426"
  title: paper
- path: "bib/wenbin_2019.bib"
  title: bibtex
category: selected
award: Best Paper IEEE Visualization 2019 (Scientific Visualization track)
---

We propose InSituNet, a deep learning based surrogate model to support
parameter space exploration for ensemble simulations that are visualized in
situ. In situ visualization, generating visualizations at simulation time, is
becoming prevalent in handling large-scale simulations because of the I/O and
storage constraints. However, in situ visualization approaches limit the
flexibility of post-hoc exploration because the raw simulation data are no
longer available. Although multiple image-based approaches have been proposed
to mitigate this limitation, those approaches lack the ability to explore the
simulation parameters. Our approach allows flexible exploration of parameter
space for large-scale ensemble simulations by taking advantage of the recent
advances in deep learning. Specifically, we design InSituNet as a convolutional
regression model to learn the mapping from the simulation and visualization
parameters to the visualization results. With the trained model, users can
generate new images for different simulation parameters under various
visualization settings, which enables in-depth analysis of the underlying
ensemble simulations. We demonstrate the effectiveness of InSituNet in
combustion, cosmology, and ocean simulations through quantitative and
qualitative evaluations.
