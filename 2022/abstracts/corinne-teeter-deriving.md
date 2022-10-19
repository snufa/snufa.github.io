
# Deriving STDP from Backpropagation

**Authors:** Nicholas Alonso, Felix Wang, Corinne Teeter

**Presentation type:** Poster

## Abstract

How the brain learns to model complex sequences with long term dependencies is still an open question. In deep learning, the standard algorithm used to train recurrent artificial neural networks for sequence learning is backpropagation through time (BPTT). BPTT performs gradient descent by propagating loss gradients through the unrolled recurrent network. BPTT is typically considered biologically implausible, as it requires storing a computational graph through time. Recently, it has been shown that BPTT can be reformulated in a way that does not require storing a computational graph. This reformulation is called eligibility propagation (e-prop) [1]. Instead of storing a graph, e-prop stores eligibility traces, which are more biologically plausible because, unlike graphs through time, they are local to synapses and they resemble biological phenomena such as calcium-ion build up.  

Though e-prop provides a more biologically plausible alternative to BPTT, its connection to classic results on synaptic plasticity in the brain, known as spike time dependent plasticity (STDP), is largely unexplored. STDP is characterized by strengthening of the synapses when the presynaptic neuron fires before the post-synaptic neuron and weakening when post fires before the presynaptic neuron. The magnitude of the update decays exponentially as the time differences increase.  In this paper, we sketch a mathematical link between e-prop and STDP. We show that under certain assumptions, e-prop closely approximates STDP. The assumptions are 1) we use leaky integrate and fire neuron model, 2) spikes are approximately Poisson distributed, and 3) synapses are optimizing a local loss function measuring local prediction errors. In addition to deriving this rule and comparing to the classic formulation of STDP, we test the resulting learning rule and show it indeed can learn simple sequences. This result suggests that when e-prop is combined with classic predictive coding views of the brain, STDP naturally follows. 

1	Bellec, G. et al. A solution to the learning dilemma for recurrent networks of spiking neurons. Nature Communications 11, 3625, doi:10.1038/s41467-020-17236-y (2020).

