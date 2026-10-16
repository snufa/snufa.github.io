# When a correlation metric cannot tell learning from non-learning in a spiking sensorimotor network

**Authors:** Pan haimeng
                           


**Presentation type:** Poster at [SNUFA 2026 online workshop (4-5 Nov 2026)](https://snufa.net/2026)

## Abstract

We report a negative result together with a methodological caution. We trained a spiking network — a fixed reservoir of 1000 LIF neurons with a plastic STDP readout — to map visual shapes onto vocal-tract motor trajectories. Under the evaluation used in the project, the Pearson correlation between produced and target trajectory, the local STDP readout appeared statistically indistinguishable from an offline ridge-regression baseline (0.865 ± 0.022 vs 0.873 ± 0.010, p = 0.29).

We then examined the evaluation itself. The three target trajectories are mutually correlated at 0.836, and the network's outputs across the three shapes are mutually correlated at 0.992. The score therefore sits near 0.86 regardless of whether the network actually discriminates shapes. Across 20 hyperparameter configurations, this metric correlated with true shape competence — whether the output matched its own target better than the other two — at r = −0.016. The configuration the metric ranked highest was at chance; the one it ranked lowest was the best in the sweep.

A confusion-matrix / rank-based measure exposes the gap: local STDP readout 47%, global ridge readout 77%, chance 33%. Shape information is nevertheless present throughout the network — decodable at 100% from reservoir activity and 87% from the final motor output — so the failure is one of weak target correspondence, not of lost information.

We also found an implementation confound: the STDP readout consumed instantaneous spikes while the baselines consumed PSP-filtered firing rates. Aligning them raised STDP from 40% to 47%, still short of ridge.

We recommend rank-based or confusion-matrix measures whenever targets are mutually correlated.