# BurstFormer: a spiking Transformer trained with biologically inspired learning rules

**Authors:** Xingyun Wang,Richard Naud
                           
**Presenting author:** Xingyun Wang

**Presentation type:** Poster at [SNUFA 2025 online workshop (5-6 Nov 2025)](https://snufa.net/2025)

## Abstract

Transformers are a cornerstone of modern artificial intelligence (AI), but their training demands substantial energy on conventional von Neumann hardware. This has spurred interest in spiking Transformer models suitable for autonomous neuromorphic chips. However, existing spiking Transformers lack a local learning rule, jeopardizing on-chip learning and energy efficiency. Here, we adapt Burstprop, a biologically inspired local learning rule that harnesses burst-dependent synaptic plasticity, to enable supervised learning in a spiking Transformer. Inspired by nonlinear dendritic integration, we propose a dendritic architecture amenable to Burstprop training for a spiking Transformer (BurstFormer). We test the accuracy of BurstFormer in image classification tasks (MNIST, KMNIST, FashionMNIST, and EMNIST) and find that the performance is comparable to a Transformer with continuous-valued activations rather than spikes. We also find BurstFormer outperforms a similarly sized spiking multi-layer perceptron (MLP) trained with Burstprop (BurstMLP), highlighting the advantage of the Transformer architecture over MLP in spiking networks trained with Burstprop. While our work doesn't address the non-locality of weight sharing, it forms a significant step toward energy-efficient adaptation on neuromorphic systems. 