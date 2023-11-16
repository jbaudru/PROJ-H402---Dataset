# PROJ-H402 - Physarum Polycephalum Algorithm in Road Networks
## Introduction
Venturing into the interdisciplinary realm of biology, graph theory, and artificial life, this student project delves into the intriguing world of physarum polycephalum, commonly known as slime mould. This unique organism, initially classified as a fungus, has garnered attention for its adaptive and intelligent behavior in exploring and optimizing its environment. Tying together concepts from graph theory, artificial life, and mathematical modeling, the project aims to implement a mathematical model inspired by the behavior of physarum polycephalum.

Graph theory, a fundamental branch of mathematics, provides the framework for understanding relationships between interconnected points, while artificial life explores the emulation of life-like behaviors in computational systems. Physarum polycephalum, with its ability to find efficient pathways in its environment, serves as an inspiring biological model for the project. The primary objective is to leverage a known mathematical model of slime mould behavior to discover the shortest paths within a graph connecting specified points. Through this cross-disciplinary exploration, students will unravel the intricacies of both biological phenomena and mathematical abstractions, fostering a deeper understanding of adaptive systems and their applications in problem-solving scenarios.

The shortest path problem (SPP) stands as a classic conundrum in computer science, and its exploration has led to the development of various algorithms to efficiently navigate complex networks. While solutions such as Dijkstra's algorithm and the A* algorithm have long been employed, the application of biological models, like physarum polycephalum, offers a novel perspective. In this project, students will delve into the rich landscape of algorithmic solutions, exploring their strengths and limitations in the context of slime mould-inspired models. The ultimate goal is to contribute insights that could aid researchers in assessing the viability of such algorithms for solving practical challenges, specifically in the domain of car-sharing. By investigating the potential application of these models in identifying optimal meeting points within a real road network, the project seeks to bridge the gap between theoretical concepts and real-world problem-solving, fostering a deeper understanding of the intersection between biology, computer science, and transportation planning.

## Goal

For this project, we're asking you to develop a graphical simulation of physarum polycephalum algorithm on the road network of the city of Brussels in Python. We want you to select two random points in this network, in the context of car-sharing, the point $a$ corresponding to starting point of the users and one point corresponding to the destination $d$ of the user. Next, the physarum polycephalum algorithm, if correctly implemented, should evolve to produce the shortest paths between points $a$ and $d$. One of the core issues in network optimization is the "shortest path problem," or SPP. Given a network, the goal is to identify a path between two nodes such that the total of its edge weights is as low as possible. Figure \ref{fig:spp} shows an example of an expected result in terms of the shortest path.

Next, you'll need to carry out some experiments. To do this, you'll be asked to run your simulation several times, in order to analyze the algorithm in terms of execution time and the quality of the proposed solution.
