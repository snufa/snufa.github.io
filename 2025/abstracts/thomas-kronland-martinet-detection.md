# Detection of spiking motifs of arbitrary length in neural activity using bounded synaptic delays

**Authors:** Thomas Kronland-Martinet, Stéphane Viollet, Laurent Perrinet
                           


**Presentation type:** Poster at [SNUFA 2025 online workshop (5-6 Nov 2025)](https://snufa.net/2025)

## Abstract

How can the brain recognize complex temporal patterns—like words in speech or sequences in motor movements—that last much longer than individual neurons can process? This fundamental challenge in neuroscience has puzzled researchers because neurons have short memory spans, yet we effortlessly process extended patterns.
We tackled this problem by developing a novel approach that mimics a relay race: instead of one neuron trying to detect an entire long pattern, we use multiple neurons working in sequence. Each neuron detects a short segment of the pattern, then passes the "baton" to the next neuron. This overcomes the brain's natural limitation of short synaptic delays.
We tested our method on audio data converted to spike patterns, simulating how the ear processes sound. Our network successfully recognized complex audio patterns with 60-80% accuracy even though multiple overlapping patterns occurred simultaneously—a challenging scenario close to the well-known cocktail party problem.
This breakthrough provides a new framework for understanding how biological neural networks encode temporal information and offers practical applications for neuromorphic computing systems that could recognize speech, gestures, or other time-based patterns with brain-like efficiency.