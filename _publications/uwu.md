---
title: "Utilitarians Without Utilities: Maximizing Social Welfare for Graph Problems using only Ordinal Preferences"
collection: publications
permalink: /publication/UWU
excerpt: 'This paper describes a class of problems where the goal is to form a subgraph from the edges of a graph, subject to a set of constraints, such that the sum of edge weights is maximized. The key difficulty is that the edge weights are unknown.'
year: '2018'
venue: 'AAAI'
paperurl: 'https://arxiv.org/abs/1711.10588'
---


### Abstract
We consider ordinal approximation algorithms for a broad class of utility maximization problems for multi-agent systems. In these problems, agents have utilities for connecting to each other, and the goal is to compute a maximum-utility solution subject to a set of constraints. We represent these as a class of graph optimization problems, including matching, spanning tree problems, TSP, maximum weight planar subgraph, and many others. We study these problems in the ordinal setting: latent numerical utilities exist, but we only have access to ordinal preference information, i.e., every agent specifies an ordering over the other agents by preference. We prove that for the large class of graph problems we identify, ordinal information is enough to compute solutions which are close to optimal, thus demonstrating there is no need to know the underlying numerical utilities. For example, for problems in this class with bounded degree b a simple ordinal greedy algorithm always produces a (b+1)-approximation; we also quantify how the quality of ordinal approximation depends on the sparsity of the resulting graphs. In particular, our results imply that ordinal information is enough to obtain a 2-approximation for Maximum Spanning Tree; a 4-approximation for Max Weight Planar Subgraph; a 2-approximation for Max-TSP; and a 2-approximation for various Matching problems.

[Download paper here](https://arxiv.org/pdf/1711.10588.pdf)
