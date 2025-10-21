# Memory capacity in spiking neural networks with fixed synaptic weight distribution

**Authors:** Aaradhya Vaze, Maayan Levy, Tim P. Vogels 
                           


**Presentation type:** Flash talk at [SNUFA 2025 online workshop (5-6 Nov 2025)](https://snufa.net/2025)

## Abstract

Experimental evidence suggests that synaptic weight distributions in neural networks are lognormal and remain largely unchanged before and after learning. It is unclear how the brain forms new memories with such constraints. Previous modeling studies use learning rules that often drastically alter the initial distribution of synaptic weights. Here, we study a Gedankenexperiment in which neurons must trade synaptic weights to form memory assemblies (MA), which automatically preserves the weight distribution. We show that trading weights can allow the formation of stable MAs, with neurons exhibiting asynchronous irregular dynamics during baseline and recall activity. Our results reveal the best weight distributions for such trading are lognormal-like and depend on the engram and connectivity parameters. What's more, inhibitory synaptic weight distribution follows the excitatory weight distribution. We explore different trading strategies, from greedy to thrifty methods. We show that continual learning and graceful forgetting arises naturally as a consequence of greedy trading. Overall, our work shows the best-case scenario for learning in spiking neural networks with fixed weight distributions is ∼ 0.025N for a sparse network of 4000 neurons, and can support exponentially more memory patterns combinatorially.