# Information-Theoretic Graph Neural Networks for Modeling Brain Connectivity

**Authors:** Abolfazl HaqiqiFar, Majid Saberi, Reza Jafari
                           


**Presentation type:** Poster at [SNUFA 2025 online workshop (5-6 Nov 2025)](https://snufa.net/2025)

## Abstract

Understanding how the brain works is an important goal in computational neuroscience and brain-inspired AI. The brain functions as a network where different regions communicate with each other. This communication relies on feedback, and when feedback is disrupted, brain function can be affected. Autism Spectrum Disorder (ASD) is one case where this network activity may differ from healthy controls (HC).
In this study, transfer entropy (TE) is used to measure how information flows between brain regions. TE captures both the direction and strength of these flows. By applying TE, the brain is modeled as a directed graph. This allows us to detect where information mainly comes from and where it goes. The results show that HCs have stronger feedback loops than ASDs. This suggests that information transfer may serve as a biomarker for distinguishing ASD from HC.
Graph Neural Networks (GNNs) are useful tools for studying brain networks. They can handle non-Euclidean data and model complex relationships. This thesis introduces a new way of combining TE with GNNs to create directed graph neural networks (Dir-GNNs). Unlike undirected models, Dir-GNNs preserve the direction of connections. They separately process incoming and outgoing signals, which helps capture brain asymmetries more accurately. Considering the special property of brain graphs, we design novel ROI-aware Graph Convolutional (Ra-GConv) layers that integrate both topological and functional information extracted from fMRI. This design allows the model to better preserve region-specific dynamics while respecting the structural constraints of brain connectivity. The integration of TE and GNNs makes it possible to perform tasks such as classification, subgraph detection, and biomarker identification in a biologically meaningful way.
Overall, the thesis contributes to causal connectomics. It shows that directed approaches, grounded in causal measures like TE, provide richer and more realistic insights into brain function than traditional undirected graphs.
