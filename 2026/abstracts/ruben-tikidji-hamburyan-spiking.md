# Spiking of locally connected parvalbumin-positive fast-spiking inhibitory interneurons encodes spatial network topography and maps excitatory drive in layer ⅔ of the medial entorhinal cortex. 

**Authors:** Roksolana Demchynska, Serhii Zavhorodnii, Bohdana Ruzhytska, Sergii Romanenko, Liubov Sadova, Yelyzaveta Razumikhina, Veronika Kisliakova, Yaroslav Subin,Ruben Tikidji-Hamburyan
                           
**Presenting author:** Roksolana Demchynska, Serhii Zavhorodnii

**Presentation type:** Poster at [SNUFA 2026 online workshop (4-5 Nov 2026)](https://snufa.net/2026)

## Abstract

Gamma oscillations (GOs, 30–100 Hz), fast brain rhythms critical for memory and attention, are produced by the parvalbumin-positive fast-spiking inhibitory interneurons (PV+FS). PV+FS exhibit type 2 excitability capable of post-inhibitory rebound (PIR). Previous studies[1] have shown that the PIR mechanism can generate GOs in randomly connected PV+FS networks. However, cortical PV+FS interneurons connect locally, with no connections beyond 150um from the soma[2]. Here, we investigate: whether PIR interneuron GOs emerge in locally connected networks and whether these oscillations are involved in any information processing.

We use a conductance-based model of PV+FS in layer ⅔ of the medial entorhinal cortex (MEC), adapted from[3], implemented in Brian2[4]. The network consists of 3038 neurons, uniformly arranged in 2D surface, reproducing 0.75x0.75 mm MEC patch with known PV+FS density[5]. The connection probability between any pair of neurons depends on the distance and was approximated by a log-normal distribution fitted to experimental data[2]. Inhibitory synapses were modeled as bi-exponential synaptic conductance with -75mV reversal potential. The network was activated by applied current (Iapp) with optional additive noise and modulated by theta oscillations mimicking septal inhibition. Spatial patterns of network activity were visualised using neuronal coordinates and spike times to examine the propagation of oscillatory activity. An information-theoretic analysis was used to measure mutual information (MI) between the network interspike-interval (ISIs) and topographical distances or Iapp differences[6].

In a noisy, theta-modulated, homogeneous network, time differences in spikes (time code) encode distances between neurons, i.e. network ISIs encode spatial information of the network topography. Also, in the case of distributed Iapp, network ISIs encode differences in Iapp. Although analyses of the heterogeneous PV+FS network produced MI of marginal to statistical significance, the presence of excitatory population and E/I balance could compensate for heterogeneity of neurons in the inhibitory population. Topographical information may provide a structure for grid-place cells interaction.

[1] doi:10.1523/JNEUROSCI.2601-15.2015
[2] doi:10.1523/ENEURO.0441-21.2022
[3] doi:10.1371/journal.pcbi.1010094
[4] doi:10.7554/eLife.47314
[5] doi:10.1016/j.isci.2020.101906
[6] doi:10.1523/JNEUROSCI.21-03-00961.2001

Acknowledgments (not part of the abstract)
The results presented in this study were obtained asf a student research project conducted during the Biological Data Science Summer School (BDS^3) 2026 in Uzhhorod, Ukraine.
