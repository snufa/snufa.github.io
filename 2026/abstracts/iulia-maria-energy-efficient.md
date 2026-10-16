# Energy-Efficient Spike-driven Transformer for Satellite-Streak Segmentation in Space Surveillance

**Authors:** Iulia Maria Filimon, Radu Danescu
                           


**Presentation type:** Flash talk at [SNUFA 2026 online workshop (4-5 Nov 2026)](https://snufa.net/2026)

## Abstract

Recent advances in machine learning and generative
AI have increased the need for computational power and energyefficient
processing. Neuromorphic computing offers an alternative
by using brain-inspired Spiking Neural Networks (SNN)
models and event-driven neuromorphic hardware.
In this work, that contributes to space surveillance applications,
we present a feasibility study on applying a Spike-
Driven Transformer to satellite streak segmentation. We choose
a transformer deliberately: a large backbone pretrained on
broad and varied imagery is more likely to respond sensibly to
the unfamiliar sensors and observing conditions a surveillance
system meets in practice, but models of this size are not usually
considered for edge deployment. We therefore ask whether spikedriven
execution can carry that capacity at an edge power budget.
We fine-tune a Spike-Driven Transformer backbone to segment
satellite streaks and we estimate its energy consumption on
the BrainChip Akida neuromorphic chip after evaluating the
model in a label-free cross-sensor setting. The SNN-based model
achieves competitive performance relative to more compact UNet
baselines and energy consumption on a neuromorphic chip
is projected, rather than hardware-measured, at 33.0mJ per
512 × 512 image inference.