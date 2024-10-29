# DPSNN: Spiking Neural Network for Low-Latency Streaming Speech Enhancement

**Authors:** Tao Sun, Sander Bohte
                           


**Presentation type:** Poster at [SNUFA 2024 online workshop (5-6 Nov 2024)](https://snufa.net/2024)

## Abstract

Speech enhancement (SE) improves communication in noisy environments, affecting areas such as automatic
speech recognition, hearing aids, and telecommunications. With these domains typically being power-constrained
and event-based while requiring low latency, neuromorphic algorithms in the form of spiking neural networks
(SNNs) have great potential. Yet, current effective SNN solutions require a contextual sampling window imposing
substantial latency, typically around 32ms, too long for many applications. Inspired by Dual-Path Spiking Neural
Networks (DPSNNs) in classical neural networks, we develop a two-phase time-domain streaming SNN framework –
the Dual-Path Spiking Neural Network (DPSNN). In the DPSNN, the first phase uses Spiking Convolutional Neural
Networks (SCNNs) to capture global contextual information, while the second phase uses Spiking Recurrent Neural
Networks (SRNNs) to focus on frequency-related features. In addition, the regularizer suppresses activation to further
enhance energy efficiency of our DPSNNs. Evaluating on the VCTK and Intel DNS Datasets, we demonstrate that
our approach achieves the very low latency (approximately 5ms) required for applications like hearing aids, while
demonstrating excellent signal-to-noise ratio (SNR), perceptual quality, and energy efficiency.