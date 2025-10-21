# Probabilistic Inference of Precise Spiking Motifs

**Authors:** Adrien Fois, Laurent Perrinet
                           


**Presentation type:** Poster at [SNUFA 2025 online workshop (5-6 Nov 2025)](https://snufa.net/2025)

## Abstract

Neurons must detect and represent precise spiking motifs - structured, temporally patterned volleys of spikes - embedded within noisy activity. How they achieve this remains a fundamental question at the intersection of computational neuroscience and neuromorphic engineering. Conventional spiking models often rely on heuristic thresholds and nonlinearities, which capture some aspects of pattern detection but obscure the underlying computational principles.

We propose a generative model that treats spiking as probabilistic inference. Each output spike reflects an explicit decision about the likelihood that a motif is present, providing a direct and interpretable link between input statistics and firing probability. This formulation avoids ad hoc mechanisms and aligns naturally with established learning techniques.

Applied to the Spiking Heidelberg Dataset (SHD), the model achieves competitive accuracy with a compact architecture. More importantly, it offers a principled and transparent account of motif detection in spike trains. By combining statistical reasoning with spiking computation, this framework provides an interpretable building block for motif discovery, neural circuit analysis, and neuromorphic engineering.