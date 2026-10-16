# Multi-Delay-Driven Hopfield Networks: High-Capacity Sequence Memory via Global Remapping

**Authors:** Julius Rosenberg, Lilli Kiessling, Pau Vilimelis Aceituno, Matthew Cook, Georg Reich
                           
**Presenting author:** Georg Reich

**Presentation type:** Poster at [SNUFA 2026 online workshop (4-5 Nov 2026)](https://snufa.net/2026)

## Abstract

Traditional Hopfield networks and their modern variants model the storage of many static patterns within a single recurrent network. We introduce Multi-Delay-Driven (MuDD) Hopfield networks, which can store and recall spatiotemporal patterns with almost-linear memory capacity in the number of neurons.
MuDD networks consist of N place cell populations, which are recurrently connected through D uniformly spaced transmission delays. The D*N^2 weights are learned by local temporal association (Delta rule) during pattern presentation. We choose chaotic attractor dynamics as spatiotemporal memories, and generate discrete sequences by partitioning the attractor set into disjoint place fields, such that only one place cell population is active at a time. Inspired by global remapping, place fields are shuffled between different attractors. Retrieval is initiated by a noisy starting sequence of length D, but generated sequences can be significantly longer. Intuitively, this sequence generation approach avoids catastrophic interference because all D delay lines from one memory agree on the correct successor population, while the remapped background memories distribute their predictions incoherently. Hundreds of shuffled Lorenz attractor dynamics can be stored in a MuDD network with N=2000 and D=15, with an empirically determined linear capacity scaling in N. For periodic patterns, we analytically derive a memory capacity scaling of N^((D-1)/D). Lastly, we demonstrate storage and recall of 70 different chaotic attractor dynamics beyond Lorenz.