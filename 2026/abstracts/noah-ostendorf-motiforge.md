# Motiforge: Flexible Motif-Constrained Network Generation

**Authors:** Noah Ostendorf, Barna Zajzon, Abigail Morrison
                           


**Presentation type:** Flash talk at [SNUFA 2026 online workshop (4-5 Nov 2026)](https://snufa.net/2026)

## Abstract

Network motifs—connectivity patterns involving two or more nodes that occur more frequently than expected by chance [1]—occur in biological neural circuits [2, 3, 4, 5]. Simple connectivity patterns can already strongly affect the dynamics of biologically inspired networks [6, 7, 8], suggesting that higher-order motifs may play a central role in shaping cortical computation. However, systematic studies of how such motifs influence network structure and dynamics remain rare, partly because tools cannot reliably generate networks with prescribed higher-order motif statistics.
We introduce Motiforge, a framework to generate networks with controlled higher-order motif distributions. Existing approaches are often limited to motif counting, undirected connectivity patterns, directed second-order constraints, or very sparse networks [6, 9, 10, 11]. Motiforge constructs directed networks with specifiable three-node motif distributions. The method is based on Markov Chain Monte Carlo sampling within an exponential random graph model and exploits the local nature of three-node motif constraints for efficient network generation. Motiforge supports motif control both within and across multiple node populations, allowing users to create structured, heterogeneous networks. It also allows the location of motifs, enabling applications including targeted perturbation experiments.
Using Motiforge, we construct networks reproducing empirically observed motif statistics [3, 4, 5] and compare their structural and dynamical properties to those of commonly used random network models, such as the Brunel network [12]. These motif-constrained networks exhibit emergent features such as long-tailed degree and firing-rate distributions that more closely resemble biological data [13, 14]. These differences highlight the importance of higher-order connectivity in shaping network behavior and suggest that standard random models may not fully capture the structural conditions relevant for biologically inspired computation.
Overall, Motiforge provides a practical framework for exploring networks with biologically inspired connectivity patterns and opens new avenues for studying, designing, and evaluating spiking neural networks.

[1] R. Milo et al., Science, 298 (5594), 824–827, 2002.
[2] H. Markram,et al., J Physiol, 500, 409–440, 1997.
[3] S. Song et al., PLoS Biology, 3 (3), e68, 2005.
[4] S. Rieubland et al., Neuron, 81 (4), 913–929, 2014.
[5] Y. Peng et al., Science Advances, 7 (25), eabg4693, 2021.
[6] L. Zhao et al., Front. Comput. Neurosci., 5, 1-16, 2011.
[7] D. Dahmen et al., bioRxiv, 2023.
[8] Y. Shao,et al., PRX Life, 3 (2), 023008, 2025.
[9] T. Mäki-Marttunen, IEEE/ACM Transactions on Computational Biology and Bioinformatics, 2016.
[10] S. Patra, A. Mohapatra, IET Syst. Biol., 14 (4), 171-189, 2020.
[11] B. Mornie et al., PLOS ONE, 20 (8), e0328639, 2025.
[12] N. Brunel, J Comput Neurosci, 8 (3), 183–208, 2000.
[13] G. Buzsáki, K. Mizuseki, Nat. Rev. Neurosci., 15 (4), 264-278, 2014.
[14] E. Gal et al., Nat. Neurosci., 20 (7), 1004-1013, 2017.