# Exploring the Generalizability of Directly Connected Hybrid Spiking-Nonspiking Neural Networks

**Authors:** Nalini Ramanathan, Maren Eberle, Erdem Varol
                           


**Presentation type:** Poster at [SNUFA 2025 online workshop (5-6 Nov 2025)](https://snufa.net/2025)

## Abstract

In many neural systems, from the locust locomotor system [1] to the mouse retinal system [2], spiking and nonspiking neurons interact. Studies such as amacrine cells’ transition from spiking to nonspiking during development [3] or graded responses and action potentials both occurring in bipolar retinal cells [4] suggest an evolutionary benefit to having both. However, most backpropagation-driven networks have only spiking or nonspiking networks, and hybrid implementations usually do not have the two neuron types interact directly. We hypothesize that directly connected hybrid neural networks are more generalizable than purely spiking (SNNs) or nonspiking neural networks (NSNs), and that our design will outperform “network to network” (N2N) models [5] and a typical RNN setup.
We test this hypothesis using an ablation study on a single-layer neural network on the Spiking Heidelberg Dataset (SHD) [6] using the recurrent setup from [7][8]. Test accuracy is on par with SNNs and NSNs for the full set of hidden neurons and test data, and outperforms N2N and RNN models. When trained on reduced hidden neurons or data, we sometimes see stronger performance for hybrid models relative to SNNs, and interestingly NSNs are sometimes on par as well. We hypothesize that generalizability emerges from the smoothness of loss landscape, which we explore via visualizations, Sharpness Awareness Minimization loss [9], and Exploratory Landscape Analysis metrics [10][11] on on both SHD and a simple Random Manifold [7] classification task. We also explore the spiking neuron ratio and its relationship with smoothness.
This work validates the viability of directly connected hybrid models, and open questions include applicability to other tasks. Further work will look at identifying neurons within a network flexibly as spiking or nonspiking with the eventual goal of applying it to connectomes where spiking and nonspiking neurons may be unknown.


References:
Burrows (1980). 10.1113/jphysiol.1980.sp013077
Chang et al. (2024). 10.3389/fncel.2023.1337768
Zhou and Fain (1996). 10.1073/pnas.93.15.8057
Saszik and DeVries (2012). 0.1523/JNEUROSCI.2739-08.2012
Wu et al. (2024). 10.1038/s41467-024-51641-x
Cramer et al. (2022). 10.1109/TNNLS.2020.3044364 
Zenke and Vogels (2021). 10.1162/neco_a_01367
Nefti et al. (2019). 10.1109/MSP.2019.2931595
Foret et al. (2020). 10.48550/arXiv.2010.01412
Munoz et al. (2014). 10.1109/TEVC.2014.2302006 #5
Kerschke et al. (2015). 10.1145/2739480.2754642 #6
