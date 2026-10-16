# Creating functional engrams by swapping synaptic weights in spiking neural networks

**Authors:** Aaradhya Vaze, Maayan Levy, Tim Vogels
                           


**Presentation type:** Poster at [SNUFA 2026 online workshop (4-5 Nov 2026)](https://snufa.net/2026)

## Abstract

Experimental evidence suggests that the synaptic weight distribution in neural networks is lognormal and remains largely unchanged before and after learning. Models of synaptic plasticity, on the other hand, usually produce bimodal weight distributions, and it is unclear how the brain forms new memories throughout its lifetime under a lognormal weight constraint. 
Towards this end, we implement a model in which excitatory neurons can swap synaptic weights to form engrams, automatically preserving the weight distribution. We show that by swapping weak incoming synaptic weights for stronger ones, functional engrams can be created that still exhibit asynchronous irregular spiking during both baseline activity and recall. The memory performance, defined as successful recall and stability, of engrams created by this algorithm is optimal (highest performance while the network is dynamically stable) under a lognormal-like, right-skewed weight distribution. We show that a network of N = 4000 excitatory neurons can store at least 2.5%N (100) such non-overlapping engrams that can be individually recalled without engaging any other stored engram. We then continue to create engrams beyond this capacity by selecting random subsets of neurons, and find that performance across all stored engrams declines gradually rather than catastrophically, with the most recent ~3%N engrams being most reliably recalled, forming a rolling buffer of recent engrams while the network remains stable. As episodic memories are understood to combine multiple elements, we test whether engrams can be co-activated. We show that any combination of up to 4 of the 100 non-overlapping engrams can be successfully co-activated without engaging other stored engrams, resulting in >4 million distinct combination patterns.
Overall, our model presents a proof of principle for how the brain might form functional engrams throughout its lifetime under a fixed weight distribution.
