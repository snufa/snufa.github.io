# Packet-based stimulus encoding compatible with neuromorphic processors

**Authors:** Filippo Costa, Chiara De Luca
                           


**Presentation type:** Poster at [SNUFA 2024 online workshop (5-6 Nov 2024)](https://snufa.net/2024)

## Abstract

Stereotyped spiking patterns or ‘packets’ are observed in the cortex, where they provide a scaffold for information processing and transmission. To process different stimuli, these stereotyped sequences present single neuron variations that encode stimulus properties. Encoding information within a packet requires neurons with heterogeneous response properties to create a rich spatio-temporal spiking pattern.
We present a shallow network of heterogeneous spiking neurons that can encode stimulus properties in packets, where each neuron can spike at most one time. This encoding scheme preserves the rank order between stimulus parameters on 4 different signal types (Kendall rank correlation > 0.8 for optimal network size). Although maximum performance is achieved when both weight and timescale heterogeneities are present, weights are shown to be more important for encoding performance. We then deployed this encoding scheme in DYNAP-SE neuromorphic chips, where device mismatch provides neuronal heterogeneity. We tested the encoding on 6 cores from 3 different chips, achieving the same performance as the simulated networks.
The trained networks encode stimuli into stereotyped patterns (average between-packets Kendall rank correlation = 0.76), producing a backbone sequence that does not depend on the network size. This bio-inspired encoding scheme combines neural heterogeneity with precise spike-timing, making it ideal for fast and low-power applications on analog neuromorphic substrates.