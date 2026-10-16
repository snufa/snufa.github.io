# Brain Age Prediction from EEG Features Using Spiking Neural Networks

**Authors:** William Klein, Jessica Fleck
                           


**Presentation type:** Poster at [SNUFA 2026 online workshop (4-5 Nov 2026)](https://snufa.net/2026)

## Abstract

Spiking neural networks (SNNs) have previously been shown to effectively predict biomarkers from a variety of biomedical signals. However, it is currently unknown if SNNs can be used to estimate brain age from electroencephalography (EEG) data. To test this, resting state EEG data was collected from 241 participants of various ages and preprocessed using the EEGLAB toolbox in MATLAB.  EEG data contain a substantial amount of useful information relating to aging, with the most predominantly used feature being the 1/f slope. The 1/f slope is obtained by decomposing the signal into its periodic and aperiodic components, a process known as spectral parameterization. The slope is shown to flatten (decrease) over the aging process, reflecting the natural age-based decrease in neural signal-to-noise ratio. Spectral parameterization is performed to determine the 1/f slope of each participant. Additionally, the Discrete Wavelet Transform (DWT) is applied in multiple levels to determine other important spectral features from EEG frequency bands (e.g., alpha). We show that by using these characteristics as input, SNNs can learn complex age-related features from EEG data while maintaining high predictive accuracy of chronological age over multiple metrics. Our work paves the way for real-world clinical and industrial applications where the portability and efficiency provided by SNNs are of great importance, such as in brain-computer interfaces (BCIs) and other technologies.