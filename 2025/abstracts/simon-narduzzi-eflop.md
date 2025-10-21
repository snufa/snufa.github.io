# EFLOP: a sparsity-aware metric for evaluating computational cost

**Authors:** Simon Narduzzi, Friedemann Zenke, Shih-Chii Liu, L Andrea Dunbar
                           
**Presenting author:** Simon Narduzzi

**Presentation type:** Poster at [SNUFA 2025 online workshop (5-6 Nov 2025)](https://snufa.net/2025)

## Abstract

Deploying energy-efficient deep neural networks on energy-constrained edge devices is an important research topic in both machine learning and circuit design communities. Both artificial neural networks (ANNs) and spiking neural networks (SNNs) have been proposed as candidates for these tasks. In particular, SNNs are considered energy-efficient because they leverage temporal sparsity in their outputs. However, existing computational frameworks fail to accurately estimate the cost of running sparse networks on modern time-stepped hardware, which exploits sparsity by skipping zero-valued operations. Meanwhile, weight sparsity-aware training remains underexplored for SNNs and lacks systematic benchmarking against optimized ANNs, making fair comparisons between the two paradigms difficult. To bridge this gap, we introduce the effective floating-point operation (EFLOP), a metric that accounts for the sparse operations during pre-activation updates of both ANNs and SNNs. Applying weight sparsity-aware training to both SNNs and ANNs, we achieve up to 8.9x reduction in EFLOPs for gated recurrent unit models and 3.6x for LIF models by sparsifying weights by 80, without sacrificing accuracy on the Spiking Heidelberg Digits and Spiking Speech Command datasets. These findings highlight the critical role of network sparsity in designing energy-efficient neural networks and establish EFLOPs as a robust framework for cross-paradigm comparisons.