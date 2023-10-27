# Neuromorphic Intermediate Representation

**Authors:** Jens Egholm Pedersen, Steven Abreu, Matthias Jobst, Vittorio Fra, and Sadique Sheik

**Presentation type:** Flash talk

## Abstract

Despite the increased focus on neuromorphic technologies and hardware, we still lack a commonly agreed-upon modeling abstraction. The lack of standardization presently challenges reproducibility and generalizability, and will severely impede the adoption of neuromorphic algorithms and platforms in the long term. Here, we propose an abstraction layer based on networks of computational nodes, modeled as dynamical systems, called the Neuromorphic Intermediate Representation (NIR). NIR is strictly declarative and kept as simple as possible, avoiding platform-specific assumptions. NIR already integrates with 6 neuromorphic simulators (Lava-dl, Nengo, Norse, Rockpool, Sinabs, and snnTorch) and 4 hardware platforms (Intel Loihi, SpiNNaker2, SynSense Xylo, and SynSense Speck). Apart from unifying the computational abstraction across hardware types, NIR bridges computational theory and neuromorphic hardware, thus generalizing computation beyond models of purely symbolic or analog computation.
NIR is open-source and available at https://github.com/neuromorphs/NIR