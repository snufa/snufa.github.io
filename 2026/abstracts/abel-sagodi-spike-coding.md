---
links:
  - title: Interactive figures
    url: https://asagodi.github.io/scn2ppm/
  - title: Code
    url: https://github.com/Asagodi/scn2ppm
---  

# Spike-Coding Networks Are Exactly Solvable: Periodic Firing Patterns as Eigenvectors

**Authors:** Ábel Ságodi, William Podlaski, Ildefonso Ferreira Pica
                           


**Presentation type:** Poster at [SNUFA 2026 online workshop (4-5 Nov 2026)](https://snufa.net/2026)

## Abstract

Spiking network dynamics are usually analyzed by simulation or mean-field approximation. We show that spike coding networks (SCNs), a low-rank class whose collective firing approximates a target signal, are exactly solvable under constant input: the spike-and-decay dynamics reduce to a discrete map on the spike-triggering boundaries. The map is matrix-valued: each spike multiplies the state by one of a finite alphabet of matrices, and every periodic firing pattern is the dominant eigenvector of the matrix product along its cycle. Whether a sequence is realized, and how fast the network settles onto it, then follow from one eigendecomposition, in the signal dimension rather than the neuron count, so cost does not grow with population size. Two problems follow: from connectivity to firing pattern (forward), and from firing pattern to connectivity (inverse). For the forward problem, a single sign in the decoder geometry decides global behavior: when every pairwise decoder cosine is positive, so that recurrent connectivity is uniformly inhibitory, the map preserves a positive cone and contracts in the Hilbert metric, every realized orbit is stable, and for two neurons the firing ratio traces a complete devil's staircase in the drive, constant over whole intervals. When one cosine turns negative, cone preservation fails and the same algebra permits positive topological entropy and chaos. For the inverse problem, we recast the search for connectivity realizing a prescribed sequence as a semi-algebraic feasibility problem with a differentiable admissibility margin. Auxiliary constraints on the same objective yield persistent sequence memory, multistability with several sequences coexisting at fixed parameters, and continuous-attractor storage on the boundary of the cone. The margin decreases systematically with sequence length, which bounds how long a sequence a given network can hold.  This gives a toolkit for analyzing and designing spike sequences in recurrent spiking networks, for neuroscience and neuromorphic computing.
