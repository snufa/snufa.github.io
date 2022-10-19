
# Seeing Through Uncertainty with Spikes not Bayes

**Authors:** Paul Kirkland

**Presentation type:** Poster

## Abstract

Neuromorphic low SNR tracking challenge:
The most typical approach to object tracking is to extract one/few position measurements via sensor signal processing and then pass this information on to the tracking function. Measurement extraction (initial detection) is usually via some thresholding process, resulting in an inevitable loss of information. This is of little consequence if the object has a signal-to-noise ratio (SNR) that is high, meaning a high probability of detecting the target can be achieved on discrete measurements. However, for low SNRs objects (usually small objects a few pixels in total) information loss may be significant, so in principle, it would be better for the tracking function to operate directly on the raw sensor signal. This method of skipping the detection phase is known as Track Before Detect (TBD). This scenario is more common than most would think, often occurring when detection happens at the edge of sensor capability. This example provides a more accurate representation of signal processing in the wild than what is reflected in most large datasets. A few examples of this problem and its applications are space-based detection and tracking, earth observation, microfluidics, and object counting. In these scenarios the object of interest is typically 1 or a few pixels in size and has no spatially identifying features, meaning you must accumulate information over time to identify the object using spatio-temporal features.  Neuromorphic sensor signal processing introduces a paradigm shift in both sensing and processing with multiple features that appear to be well suited for this complex task. This research presents both a simple example in the form of a challenge and a unique solution using SNNs and STDP. Our solution is compared and outperforms typical Bayesian approaches for this task of Kalman and Particle Filtering.

