# A spiking implementation of the incentive circuit model for mushroom body learning and behavior

**Authors:** Jordan Watts, Barbara Webb
                           


**Presentation type:** Poster at [SNUFA 2025 online workshop (5-6 Nov 2025)](https://snufa.net/2025)

## Abstract

To link mushroom body (MB) microcircuits to neuron dynamics and behavior, connectome-driven neural models are essential. The Drosophila offers an ideal starting point enabling tests of how MB learning rules shape neuron and motor output. By studying the brain in a realistic simulation environment, we probe how the MB supports adaptive behavioral control and extract learning principles relevant across species.

Building on the incentive circuit (IC) of (Gkanias et al., 2022), a full spiking implementation was created in Brian 2. Three conditioning paradigms—acquisition/extinction, unpaired, and reversal— are simulated while alternating odors A and B with clean air interludes. Spiking responses during each phase closely matched the original rate-based IC, validating the approach. The model preserves the original circuit motifs: feedforward PN→KC connections, plastic KC→MBON synapses, and MBON↔DAN recurrent loops that enable flexible formation and forgetting of valence memories. Leaky-integrate-and-fire equations govern DAN and MBON neurons; Kenyon cells are split into axon and dendrite compartments to represent calyx and lobe dynamics. Dopamine-dependent plasticity (DPR) relies on DAN release, KC activity, and synaptic weights relative to a resting baseline, which is explicitly non-Hebbian. In a virtual arena with pre-training, training, and post-training phases (shocks or sugar reinforcement), the SNN drove fruit-fly agents to behavioral preferences indistinguishable from those produced by the original model.

Moving from rate-based to spiking models captures the temporal precision and variability of real neurons, allowing investigation of millisecond-scale dynamics of the DPR that rate models average away. Finally, we can see how hardware-friendly SNNs influence learning and behavior, supporting eventual deployment on neuromorphic platforms for real-time, closed-loop experiments.

Gkanias, E., McCurdy, L. Y., Nitabach, M. N., & Webb, B. (2022). An incentive circuit for memory dynamics in the mushroom body of Drosophila melanogaster. Elife, 11, e75611.