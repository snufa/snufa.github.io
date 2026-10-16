# Ion-Channel State and Neuronal Firing: A Quantum Signal Processing Case Study

**Authors:** Chitaranjan Mahapatra
                           
**Presenting author:** Chitaranjan Mahapatra

**Presentation type:** Poster at [SNUFA 2026 online workshop (4-5 Nov 2026)](https://snufa.net/2026)

## Abstract

Can a compact polynomial representation preserve the ion-channel dynamics underlying neuronal firing? We investigated this question using simulated Hodgkin–Huxley action potentials, focusing on the sodium activation term (m^3). A Chebyshev fit based on membrane voltage alone cannot recover this term when the firing trajectory revisits the same voltage with different activation states. Retaining the gating variable (m) resolves that ambiguity and accurately reproduces the activation term with a low-degree polynomial. We then explored a proof-of-concept, single-input quantum signal-processing circuit representation of a bounded polynomial target. In idealized circuit simulations, fidelity varied non-monotonically with polynomial degree and circuit depth, with peaks at intermediate depths. These results highlight a modeling requirement for compact neuron surrogates: retain channel state when voltage alone does not uniquely determine the underlying dynamics. The circuit study suggests one route for connecting state-aware biophysical representations to quantum computation. Further work is needed to encode the complete Hodgkin–Huxley system and test whether this approach benefits simulations of spiking circuits.