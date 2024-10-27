---
layout: page
title: Topology & Hypergraphs
description: Understanding topology through hypergraphs
img: assets/img/PH_hypergraph2.png
importance: 2
category: research
---

Persistence diagrams summarize the presence of loops in data. However, they do not inform us of where the loops are. Can we understand which points are “integral” to the overall structure of the data? The goal is to develop a quantification of each point in the data according to its contribution to the overall structure.



<p align="center">
  <img width="750" src="https://irisyoon.com/assets/img/hyperTDA.png">
</p>
<div class="caption">
Figure 1. Pipeline for constructing and analyzing PH-hypergraph. <span style="font-weight:bold">A.</span> Given point cloud data, we compute the persistence
</div>

We use graph theory and network science to study the PH-hypergraph. We first compute hypergraph centrality, which ranks the original data according to their participation in large loops. We also perform community detection, which partitions the data according to how often a collection of points constitutes a

<p align="center">
  <img width="750" src="https://irisyoon.com/assets/img/hyperTDA_outputs.png">
</p>
<div class="caption">
Figure 2. Outputs of hypergraph analysis on a random curve. (Left) PH-centrality assigns a high importance score to vertices
</div>


Preprint: <a href="https://arxiv.org/abs/2210.07545">Hypergraphs for multiscale cycles in structured data</a>
 
Code: <a href="https://github.com/degnbol/hyperTDA">github:hyperTDA</a>

*Joint work with Agnese Barbensi (University of Melbourne), Christian Madsen (University of Melbourne), Deborah Ajayi (University of Ibadan), Heather Harrington (University of Oxford), and Michael Stumpf (University of Melbourne).*
