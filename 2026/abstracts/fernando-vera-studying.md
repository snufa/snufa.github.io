# Studying Minimal Complexity: From Neural Oscillators to Spiking Neural Networks for Robust Graph Reconstruction

**Authors:** Fernando Vera Buschmann, Horacio Rotstein, Vincent Oria
                           


**Presentation type:** Poster at [SNUFA 2026 online workshop (4-5 Nov 2026)](https://snufa.net/2026)

## Abstract

Biological neural networks encode structural interactions through collective dynamics and sparse connectivity, through spike-train patterns that communicate information across the network.  Yet artificial neural networks remain computationally expensive relative to the brain's efficiency. We investigate oscillatory regime dynamics as learnable graph encoders, systematically comparing three models across a complexity hierarchy: minimal Kuramoto (Ku), intermediate Stuart-Landau (SL), highly complex Wilson-Cowan (WC), which produces firing-rate dynamics interpretable as spike patterns, and spiking neural networks (SNNs) as the biologically most realistic level. We propose learnable neuro-inspired oscillatory layers as alternatives to standard graph encoders, examining which dynamical ingredients are necessary to encode graph structure through functional connectivity signatures extracted via spike-train analysis methods (transfer entropy, Granger causality).

Preprocessing baselines with fixed oscillatory parameters fail to generalize across graph topologies,  suggesting the dynamical parameters themselves are the bottleneck. To address this, we make the oscillatory layer learnable by jointly optimizing two parameter classes: (1) connectivity parameters (coupling strengths) and (2) intrinsic dynamics parameters (frequency, amplitude, threshold). Some intrinsic parameters govern whether the system oscillates, enabling temporal structure encoding. End-to-end optimization via differentiable ODE solvers discovers configurations that improve link prediction and node classification accuracy. A critical question emerges: Which complexity level (from minimal Kuramoto to full SNNs) most efficiently encodes graph structure compared to fixed-parameter preprocessing?

We investigate which level of oscillatory complexity optimally encodes graph structure through functional connectivity. Working hypothesis: Comparing across this model hierarchy reveals the minimal dynamical complexity necessary for effective graph encoding, outperforming fixed-parameter preprocessing and conventional GNN baselines.
