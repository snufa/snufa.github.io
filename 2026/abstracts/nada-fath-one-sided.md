# One-sided saturation in spiking neurons: the inhibitory dynamic range equals the operating point

**Authors:** Nada Fath, Feng Wang, Daoshu Luo
                           


**Presentation type:** Poster at [SNUFA 2026 online workshop (4-5 Nov 2026)](https://snufa.net/2026)

## Abstract

A rate-coding spiking neuron cannot represent a negative rate. The consequence for the function it implements is less trivial: its response to a conductance perturbation is bounded below by the negative of its own operating point and unbounded above, so perturbations of equal magnitude and opposite sign produce responses that differ in both amplitude and saturation behavior.

We quantify this in two models: an adaptive exponential integrate-and-fire neuron, and a ten-conductance biophysical model of a dorsal raphe serotonergic neuron parameterized from voltage-clamp data. The second was ported from the original authors' deposited source and verified against it — all 24 gating functions agreeing to 5 × 10⁻¹⁰, and whole-model discharge rate to within 1.4%. Perturbations are matched by delivered current rather than conductance, since the two effectors compared differ 1.6-fold in driving force at subthreshold potentials.

Below saturation the two directions are comparable, with inhibition marginally the stronger. Above it they diverge without bound: in the biophysical model, silencing requires approximately 18-fold less delivered current than an excitatory change of matched magnitude. The reduced model shows discontinuous firing onset, but synaptic noise abolishes the discontinuity while leaving the bound and the asymmetry intact — the bound follows from non-negativity of rate, not from bifurcation structure. Where the readout is transmitter concentration rather than spike count, a second nonlinearity compounds: release facilitation renders output superlinear in rate upward, while silencing imposes a hard floor downward.

The motivating application is chemogenetics, in which excitatory and inhibitory receptors are compared to infer circuit necessity and sufficiency; we show that an asymmetric outcome need not imply an asymmetric circuit. More generally, the result characterizes how the operating point, rather than any parameter choice, bounds the class of functions a rate-coding spiking unit can implement.