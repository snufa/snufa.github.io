# Factorization and spatial encoding: how the genomic code may wire up a brain

**Authors:** Karim G. Habashy, Benjamin D. Evans, Dan F. M. Goodman, Jeffrey S. Bowers
                           


**Presentation type:** Poster at [SNUFA 2026 online workshop (4-5 Nov 2026)](https://snufa.net/2026)

## Abstract

The genomic mechanisms that efficiently encode the initial architecture and synaptic connectivity of neural circuits remain poorly understood. We hypothesise that two primary mechanisms — spatial encoding and factorisation — enable a limited genome to initialise networks of billions of neurons. Spatial encoding, a form of indirect representation, compresses neural network parameters while enforcing structural continuity. Complementarily, we introduce a factorisation mechanism inspired by reaction-diffusion models, comprising a spatially invariant reaction rule and spatially variant diffusion dynamics. Based on this insight, we can efficiently abstract a neural network layer as a spatially invariant weight kernel (or filter) and its spatially variant transformations along the spatial dimensions. Thus, coupling this variant-invariant decomposition with spatial encodings can substantially reduce the size of the solution space explored by the genome. In addition, we show that this coupling leads to efficient initialisation of cortical maps, such as V1 orientation maps, and neural networks with the ability to generalise. For spiking neural networks, coupling factorization with spatial encodings has the potential to offer functional and learning advantages. It does this by inducing interpretable structure in learned parameters and facilitating solution discovery by minimizing the search space.