---
layout: paper
title: Asynchronous and Load-Balanced Union-Find for Distributed and Parallel Scientific Data Visualization and Analysis
authors: Jiayi Xu, Hanqi Guo, Han-Wei Shen, Mukund Raj, Xueqiao Xu, Xueyun Wang, Zhehui Wang, and Tom Peterka
journal: IEEE Transactions on Visualization and Computer Graphics
order: 2021-01
pubdate: April 2021
image: /mraj/images/jiayi_2021.png
image_text: Gantt charts for bulk synchronous and asynchronous super-level set extraction
links:
- path: "https://ieeexplore.ieee.org/document/9409642"
  title: paper
- path: "bib/jiayi_2021.bib"
  title: bibtex
category: selected
award: Best Paper IEEE Pacific Vis 2021
---

We present a novel distributed union-find algorithm that features asynchronous
parallelism and k-d tree based load balancing for scalable visualization and
analysis of scientific data. Applications of union-find include level set
extraction and critical point tracking, but distributed union-find can suffer
from high synchronization costs and imbalanced workloads across parallel
processes. In this study, we prove that global synchronizations in existing
distributed union-find can be eliminated without changing final results,
allowing overlapped communications and computations for scalable processing. We
also use a k-d tree decomposition to redistribute inputs, in order to improve
workload balancing. We benchmark the scalability of our algorithm with up to
1,024 processes using both synthetic and application data. We demonstrate the
use of our algorithm in critical point tracking and super-level set extraction
with high-speed imaging experiments and fusion plasma simulations,
respectively.
