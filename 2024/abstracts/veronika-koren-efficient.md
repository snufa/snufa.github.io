# Efficient encoding, transmission and transformation of sensory features in a multilayer spiking network

**Authors:** Veronika Koren, Alan J Emanuel, Stefano Panzeri
                           


**Presentation type:** Talk at [SNUFA 2024 online workshop (5-6 Nov 2024)](https://snufa.net/2024)

## Abstract

How do biological neural systems efficiently encode, transform and propagate information between brain areas? While previous work has suggested that biologically plausible models of neural signal processing may be implemented efficiently within a single processing layer, how such computations extend across several processing layers is less clear. Here, we propose a multilayer spiking network that realizes these functions efficiently and is built with constraints from empirical data. 

We model propagation of two time-varying sensory features across a sensory pathway by extending the theory of efficient coding with spikes to efficient encoding, transformation and transmission of sensory signals across layers. At the entry level, feedforward networks of spiking neurons, which model sensory neurons, extract and encode a fast and a slow feature of a sensory stimulus. Activity of sensory neurons converges onto single excitatory and inhibitory neurons in the next layer and combined information is propagated to subsequent layers. We find that convergence of sensory features is beneficial because it lowers transmission error by pooling across multiple noisy encoders. In subsequent layers, recurrent excitatory-inhibitory networks of generalized leaky integrate-and-fire neurons optimally encode, transform and transmit these signals at the population level. 

Compared with previous works, we improved biological plausibility of neural implementation of efficient coding by deriving a mechanistic model of feedforward currents to single neurons where both excitatory and inhibitory neurons receive feedforward inputs from the upstream brain area, analogous to the anatomy of sensory afferent pathways. We tested specific structures of feedforward connectivity that efficiently realise a broad class of feature transformations, including mixing across features. We distinguish two qualitatively different types of mixing, one that results in a temporal contrast across the sensory features, and another that results in a synergistic interaction across features. We propose that these types of feature interactions could be relevant for signal processing throughout the cortex.
