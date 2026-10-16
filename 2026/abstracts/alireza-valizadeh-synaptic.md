# Synaptic plasticity selects transmission delays for resonant communication in spiking networks

**Authors:** Ali Ghadiri, Saeed Taghavi, Hedyeh Rezaei, Ad Aertsen, Arvind Kumar, Alireza Valizadeh
                           


**Presentation type:** Talk at [SNUFA 2026 online workshop (4-5 Nov 2026)](https://snufa.net/2026)

## Abstract

Efficient communication between neural populations requires signals to arrive when receiving circuits are most excitable. However, transmission delays are heterogeneous, raising the question of how learning coordinates communication with network dynamics. Here, we show that conventional Hebbian spike-timing-dependent plasticity (STDP) can select connections with appropriate delays while leaving individual transmission delays fixed.
We model two reciprocally connected populations of excitatory and inhibitory leaky integrate-and-fire neurons, with heterogeneous inter-population delays and plastic excitatory projections. We examine both asynchronous irregular networks that exhibit stimulus-evoked resonance and networks that generate spontaneous oscillations. STDP produces distinct temporal organization in the two projection directions: feedforward connections preferentially strengthen at shorter delays, whereas feedback connections are selected according to the networks’ resonance properties. Consequently, the combined feedforward and feedback delays approach the population oscillation period, approximately 40 ms for networks oscillating near 25 Hz.
This self-organization improves pulse-packet transmission and supports reverberation between populations, increasing signal-to-noise ratios in ways not explained by stronger overall connectivity alone. Spontaneous oscillations drive a similar organization without external pulse-packet stimulation and accelerate its formation relative to intermittently evoked activity. Delay selection persists with reduced projection density when total synaptic input is preserved, and with moderate differences in population resonance frequencies. Larger frequency mismatches progressively suppress feedback potentiation, yielding predominantly feedforward interactions.
These findings identify a mechanism through which local synaptic learning links circuit rhythms to the temporal organization of inter-population connectivity. They suggest that heterogeneous fixed delays provide a substrate for learning effective communication timing in biological and artificial spiking networks, without requiring a separate delay-plasticity rule.

