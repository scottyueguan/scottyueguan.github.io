---
title: "Lazy Incremental Search"
collection: projects
permalink: /projects/lis
---
<img src='/images/piano.png' width=500>

The objective of lazy planning framework is to reduce the unnecessary edge evaluations during search by utilizing heuristic paths.
To achieve minimal edge evaluations, the lazy search algorithms first compute the heuristics paths without edge evaluations and then restrict the evaluations only to the optimal path candidates found heuristically.
We leverage the idea of lazy search to improve the performance of incremental search algorithms which use previous search results to facilitate a new optimal path in a dynamic environment.  
Our proposed lazy incremental search method enables more efficient replanning than the existing incremental search algorithms.

<img src='/images/lis_pr2.png' width=400>


## Publications

<b>[Lazy Lifelong Planning for Efficient Replanning in Graphs with Expensive Edge Evaluation](https://jliminf.github.io/publications/lgls21)</b><br>
<b>Lim, J.</b>, Srinivasa, S., and Tsiotras, P., "Lazy Lifelong Planning for Efficient Replanning in Graphs with Expensive Edge Evaluation,” arXiv e-prints, [arXiv:2105.12076](https://arxiv.org/abs/2105.12076), May. 2021.
