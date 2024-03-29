---
title: 'Large-Scale Contextual Market Equilibrium Computation through Deep Learning'
date: 2024-02-01
permalink: /posts/2024/02/large-scale-contextual-market-equilibrium/
tags:
  - algorithmic game theory
  - market equilibrium
  - large-scale markets
---

Authors: Yunxuan Ma, **Yide Bian**, Hao Xu, Weitao Yang, Jingshu Zhao, Zhijian Duan, Feng Wang, Xiaotie Deng

**Abstract**: Market equilibrium is an important topic in the fields of economics and optimization. In this paper, we initiate the study of deep learning for large-scale contextual market equilibrium computation. We propose two methods, called MarketFCNet and MarketTransNet, to approximate the market equilibrium with a large number of buyers or markets. MarketFCNet uses a network to represent the allocation of one good to one buyer, while the complexity is independent of the number of buyers. MarketTransNet uses a transformer network to represent the whole allocations and prices given the market representation, which can fast approximate the market equilibrium for unseen markets. We also propose a measure called Nash Gap, to measure the distance of a given pair of allocations and prices to market equilibrium. Experimental results show that both MarketFCNet and MarketTransNet achieve better measures and lower running times over existing methods, demonstrating the success of deep learning-based methods in approximating large-scale contextual market equilibrium.

TLDR: We proposed two methods to approximate large-scale contextual market equilibrium.

**Keywords**: algorithmic game theory, market equilibrium, large-scale markets, function approximation, approximation measure

---
