---
layout: paper
title: IExchange Asynchronous Communication and Termination Detection for Iterative Algorithms
authors: Dmitriy Morozov, Tom Peterka, Hanqi Guo, Mukund Raj, Jiayi Xu, and Han-Wei Shen
journal: IEEE Symposium on Large Data Analysis and Visualization (LDAV)
order: 2022-01
pubdate: (accepted)
image: /mraj/images/morozov_2021.png
image_text: Streamlines traced in a Nek5000 data set using asynchronous communication
links:
- path: ""
  title: paper
- path: ""
  title: bibtex
category: all
---

Iterative parallel algorithms can be implemented by synchronizing after each
round. This bulk-synchronous parallel (BSP) pattern is inefficient when strict
synchronization is not required: global synchronization is costly at scale and
prohibits amortizing load imbalance over the entire execution, and termination
detection is challenging with irregular data-dependent communication. We
present an asynchronous communication protocol that efficiently interleaves
communication with computation. The protocol includes global termination
detection without obstructing computation and communication between nodes. The
user’s computational primitive only needs to indicate when local work is done;
our algorithm detects when all processors reach this state. We do not assume
that global work decreases monotonically, allowing processors to create new
work. We illustrate the utility of our solution through experiments, including
two large data analysis and visualization codes: parallel particle advection
and distributed union-find. Our asynchronous algorithm is several times faster
with better strong scaling efficiency than the synchronous approach.
