# Short-term synaptic plasticity reshapes credit assignment through eligibility traces in recurrent E/I spiking networks

**Authors:** Mauricio A. Diaz, Janina Hesse
                           


**Presentation type:** Flash talk at [SNUFA 2026 online workshop (4-5 Nov 2026)](https://snufa.net/2026)

## Abstract

Stress can alter presynaptic release in prefrontal circuits, but how these synaptic changes affect learning and adaptive behaviour remains unclear. E-prop provides a biologically plausible framework for this question because synaptic updates combine a learning signal with synapse-local eligibility traces. We therefore asked whether short-term plasticity (STP), by transforming presynaptic spikes into dynamic transmitter release, can reshape which synapses receive credit during learning.

We trained Dale-constrained recurrent LIF/ALIF networks on temporal tasks spanning timing, decision-making, and trajectory generation. To incorporate short-term synaptic dynamics, we extended random-feedback e-prop by replacing the presynaptic spike with Tsodyks–Markram transmitter release, both in the network dynamics and in the eligibility trace, using literature-derived cortical STP profiles.

We then mapped how learning credit is distributed across excitatory and inhibitory pathways. Preliminary results from 260-neuron networks (80% excitatory) show that, without STP, credit is approximately proportional to synapse abundance. With STP, release phenotype becomes a major determinant of where credit is assigned. Facilitating E→I synapses make up only 6% of synapses but carry a large share of the gradient, and depressing E→I synapses, with the same source and target populations, receive 2–10× less credit than facilitating ones. The shift is also present in the BPTT gradient, and it largely disappears when eligibility is computed from spikes instead of release.

These results suggest that short-term release dynamics can act as a local filter on which synapses become eligible for task-related credit. We are now using this framework to test how stress-motivated perturbations and neuromodulatory changes in release probability alter credit allocation and learning.