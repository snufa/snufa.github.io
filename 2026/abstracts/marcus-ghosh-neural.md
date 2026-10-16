# Neural heterogeneity promotes robust learning by increasing representational separability

**Authors:** Priyam Rai, Hardik Rajpal, Marcus Ghosh
                           


**Presentation type:** Flash talk at [SNUFA 2026 online workshop (4-5 Nov 2026)](https://snufa.net/2026)

## Abstract

Biological neurons display diverse intrinsic timescales, and spiking neural networks with heterogenous membrane time constants outperform their homogenous counterparts. However, the mechanism underlying this advantage remains unclear. To address this, we trained pairs of recurrent spiking neural networks, with learnable homogenous or heterogenous membrane time constants, on an auditory classification task. In line with prior work, our heterogenous networks averaged 10% better test performance and 90% of them outperformed their homogenous partner. To understand what advantage heterogeneity provides, we then compared our trained networks’ patterns of hidden unit activations. Both types of networks used similar numbers of active units and were dominated by redundant information processing. But critically, heterogenous networks learned a significantly higher dimensional neural representation. The advantage of this representation is that it allows networks to better separate arbitrary classes, as measured by shattering dimensionality and manifold capacity, and we observed strong relationships between these metrics and task performance across all networks (r = 0.87 and r = 0.74). This leads us to conclude that heterogenous time constants promote robust learning by increasing representational separability. A finding with relevance for both neuroscience and machine learning, as it helps to explain the functional benefits of neural heterogeneity and suggests a path towards better machine learning models. 