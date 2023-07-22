---
title: "MAMS-A*: Multi-Agent Multi-Scale A*"
collection: publications
permalink: /publications/mams20
citation: 'Lim, J., and Tsiotras, P., "MAMS-A*: Multi-Agent Multi-Scale A*," <i>2020 IEEE International Conference on Robotics and Automation (ICRA)</i>, 2020, pp. 5583-5589, doi: 10.1109/ICRA40945.2020.9197045.'
---

[[Paper]](https://ieeexplore.ieee.org/abstract/document/9197045)
[[Video]](https://www.youtube.com/watch?v=aKr5JQd-qAM&list=LL&index=14)
[[Code]](https://github.com/DCSLgatech/mams-astar)

## Abstract
We present a multi-scale forward search algorithm for distributed agents to solve single-query shortest path planning problems. Each agent first builds a representation of its own search space of the common environment as a multi-resolution graph, it communicates with the other agents the result of its local search, and it uses received information from other agents to refine its own graph and update the local inconsistency conditions. As a result, all agents attain a common subgraph that includes a provably optimal path in the most informative graph available among all agents, if one exists, without necessarily communicating the entire graph. We prove the completeness and optimality of the proposed algorithm, and present numerical results supporting the advantages of the proposed approach.
