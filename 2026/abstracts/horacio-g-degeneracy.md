# Degeneracy and unidentifiability in spiking and oscillatory neural networks: Two faces of the same coin

**Authors:** Horacio G. Rotstein
                           


**Presentation type:** Poster at [SNUFA 2026 online workshop (4-5 Nov 2026)](https://snufa.net/2026)

## Abstract

Networks of spiking neurons and, more generally, oscillatory nodes have been increasingly used for brain-inspired computation. Unlike conventional artificial neural networks (ANNs), spiking neural networks (SNNs) and oscillatory neural networks (ONNs) rely on precise temporal events, collective dynamics (e.g., phase, amplitude), or combinations of both. While this rich dynamic endows SNNs and ONNs with higher computational capacity and flexibility, it also introduces degeneracy—the existence of multiple distinct combinations of parameter values that produce identical observed network patterns. Consequently, the inverse mapping from observable data to learned model parameters is ill-posed, rendering parameters unidentifiable and reducing model interpretability.

Despite degeneracy being well-documented in biological neural systems, its structural and dynamic mechanisms in artificial SNNs and ONNs remain insufficiently understood. Here, we address this gap by analyzing how single-node degeneracy is communicated to the networks in which SNNs and ONNs are embedded, and how network-level degeneracy can emerge even when absent in isolated nodes. Using the leaky integrate-and-fire (LIF) spiking model and the Stuart-Landau (SL) oscillator—the normal form of a Hopf bifurcation widely used in brain network modeling—we show that degeneracy manifests through distinct mechanisms. In LIF nodes, degeneracy stems primarily from structural parameter redundancy; in SL nodes, it arises from dynamic balances among participating processes and underlying spatial/phase symmetries. Crucially, in both models, transient dynamics break these symmetries and lift degeneracy, meaning parameter unidentifiability is not automatically transmitted to the network level. We analyze several representative cases and discuss their broader implications for brain-inspired computing and model fitting.
