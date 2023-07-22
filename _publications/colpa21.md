---
title: "Class-Ordered LPA*: An Incremental-Search Algorithm for Weighted Colored Graphs"
collection: publications
permalink: /publications/colpa21
citation: 'Lim, J., Salzman, O., and P. Tsiotras, "Class-Ordered LPA*: An Incremental-Search Algorithm for Weighted Colored Graphs," <i>2021 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)</i>, 2021, pp. 6907-6913, doi: 10.1109/IROS51168.2021.9636736.'
---

[[Paper]](https://ieeexplore.ieee.org/abstract/document/9636736)
[[Video]](https://www.youtube.com/watch?v=DAVAYhZTHww&ab_channel=DCSLGeorgiaTech)

## Abstract
Replanning is an essential problem for robots operating in a dynamic and complex environment for responsive and robust autonomy. Previous incremental-search algorithms efficiently reuse existing search results to facilitate a new plan when the environment changes. Yet, they rely solely on geometric information of the environment encoded in an edge-weighted graph. However, semantic information often provides valuable insights that cannot easily be captured quantitatively. We encode both semantic and geometric information of the environment in a weighted colored graph, in which the edges are partitioned into a finite set of ordered semantic classes (e.g., colors), and then we incrementally search for the shortest path among the set of paths with minimal inclusion of inferior classes, using information from the previous search using ideas similar to LPA*. The proposed Class-Ordered LPA* (COLPA*) algorithm inherits the strong theoretical properties of LPA*, namely, optimality and efficiency, but optimality now is with respect to the total path order. Numerical examples show that semantic information helps reduce the relevant search space in a dynamic environment.
