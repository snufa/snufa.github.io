
# Historically Dependent NMDA-modulated Resonant Synapses for Decoding Time Structured Spike Trains

**Authors:** Nigel Crook, Alex Rast, Eleni Elia

**Presentation type:** Poster

## Abstract

Biological neurons communicate with each other using spike events. Two broad categories of spike event coding (rate-based and temporal) are thought to contribute to brain activity. Rate-based coding communicates analog information on a continuous scale through the intensity of bursts of spikes. Temporal coding, on the other hand, communicates information through the timing of spike events. It has been shown that temporal coding has higher information capacity than rate based coding. On the other hand, it is relatively easy to develop working learning mechanisms for rate based coding, which can leverage the statistic of the firing rate. However, temporal coding is more challenging in this respect because computing the statistics of temporal correlations is significantly more computationally intensive and more sensitive in variation of the signal.

In this paper we explore how historically dependent NMDA-modulated ‘resonant’ synapses provide a convenient mechanism for decoding temporally structured spike trains. We model synapses using a Generalised Beta Distribution which captures the NMDA kinetics. These Beta Distributions model the range of interspike interval (ISI) sensitivities present in temporal coded synapses, so that a given synapse responds preferentially to a particular ‘resonant’ interspike interval. To enable the decoding of temporal spike trains with different characteristic ISI patterns, multiple synapses acquire a resonant tuning that encodes the timing pattern and which result in coherent groups of spike activity on the postsynaptic neuron. 

Using Brian2 we have developed models that learn to decode temporally coded spike trains between neuron pairs.  Our experiment results demonstrate a plausible adaptive mechanism 
whereby groups of neurons can acquire a temporal coding sensitive to local input patterns.