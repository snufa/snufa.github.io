# Kairos: A Novel Neuromorphic Architecture for Efficient Simulation of SNNs with Long-range Synaptic Delays

**Authors:** Amirreza Movahedin, Lennart P. L. Landsmeer, Said Hamdioui, Christos Strydis
                           


**Presentation type:** Poster at [SNUFA 2026 online workshop (4-5 Nov 2026)](https://snufa.net/2026)

## Abstract

Recent advances in training Spiking Neural Networks (SNNs) have promoted variable-length synaptic delays to a first-class network parameter, improving temporal expressiveness and performance on temporally rich tasks. Yet, architectural support for long-range delays remains highly inefficient. Existing neuromorphic architectures generally follow one of two design approaches, dictated by whether spike delays are applied before or after the synapses. Presynaptic designs store delayed spikes compactly but repeatedly perform costly source-to-destination, synaptic resolutions across timesteps. Postsynaptic designs resolve spike destinations immediately but rely on delay buffers whose memory cost and underutilization grow with maximum supported delay. In effect, both design approaches struggle to scale efficiently to larger, trainable synaptic delays.

We present Kairos, a new design approach that rethinks delay handling at the architectural level by combining compressed presynaptic storage for long-term spikes with a bounded postsynaptic short-term delivery window. This combination allows for a novel spike-delivery method where source-to-destination resolution is performed periodically. This decouples the supported delay range from the size of the postsynaptic memory while reducing the bandwidth overhead of conventional presynaptic designs. The architecture further exploits parallelism across neurons and delay ranges, incorporates dedicated fast processing for short delays, and employs compiler-driven workload balancing and aggressive spike eviction to improve efficiency.


To evaluate our proposed neuromorphic architecture, we build a configurable cycle-level, architectural simulator that models Kairos and other, competitive state-of-the-art architectures for fair energy, latency, and area comparisons and evaluate all of them across diverse SNN benchmarks. Against Intel Loihi 2 (a postsynaptic design), Kairos supports at least 5x larger delays at the same memory and energy budgets and exhibits a 4.6x higher energy-latency product. Overall, Kairos achieves on average 78x and 2.5x improvements in the energy-latency product over presynaptic and postsynaptic designs, respectively, while generally demonstrating sublinear scaling with an increasing supported delay range.