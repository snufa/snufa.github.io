# Deep-learning-assisted simulation of a cortical circuit: Integrating anatomy, physiology and function

**Authors:** Shinya Ito, Darrell Haufler, Javier Galván Fraile, Kael Dai, Joe Aman, Omid Zobeiri, Guozhang Chen, Claudio Mirraso, Wolfgang Maass, and Anton Arkhipov
                           


**Presentation type:** Poster at [SNUFA 2025 online workshop (5-6 Nov 2025)](https://snufa.net/2025)

## Abstract

We present a biorealistic model of mouse primary visual cortex (V1) represented as a recurrent spiking neural network (RSNN) in which anatomy and physiology fix the architecture, and functional recordings provide additional constraints for tuning synaptic weights. The column-scale model comprises ≈200k point neurons spanning 201 cell types with ≈170M thalamocortical, recurrent, and background synapses derived from MICrONS electron microscopy and multi-patch synaptic physiology, and is benchmarked to Neuropixels cell-type statistics. Training uses backpropagation through time with a biologically constrained, multi-objective loss to align firing rates, orientation selectivity index (OSI), direction selectivity index (DSI), and synchrony under a minimal stimulus set (gray baseline + drifting gratings). To keep learning on a physiological manifold, we introduce a sign-preserving exponentiated-gradient update (log-space, multiplicative) that enforces Dale’s law and maintains heavy-tailed, log-normal conductance distributions while permitting task-relevant adjustments.

After optimization, the model matches within-distribution (relative to the training stimuli) Neuropixels statistics and generalizes out-of-distribution: it reproduces contrast-dependent gain across inhibitory classes—vasoactive intestinal peptide (VIP) vs. somatostatin (SST) push–pull and divisive parvalbumin (PV) control—and maintains stable dynamics across contrasts and stimuli, including natural images not used during training. Analyzing the trained synaptic weights reveals emergent wiring rules consistent with V1 physiology: like-to-like excitation and deep-layer anti-like-to-like inhibition concentrating onto layer 5/6 excitatory targets, yielding falsifiable, layer-specific predictions for excitatory/inhibitory control of selectivity.

Conceptually, the advance is methodological: activity statistics can be treated as explicit optimization targets that constrain synaptic weights in anatomically grounded RSNNs. Practically, the log-space, sign-preserving update offers a lightweight route to train large spiking models while preserving biological plausibility. The same pipeline extends to multi-area, biorealistic models and supports systematic circuit dissection—linking trained RSNNs to proposed mechanisms rather than just performance.