# Using SNN for the Radio Authorization Problem

**Authors:** Mark Henkel, Francois Laignelot, Guillaume Marthe, Leonardo S. Cardoso, Claire Goursaud
                           
**Presenting author:** Mark Henkel

**Presentation type:** Poster at [SNUFA 2024 online workshop (5-6 Nov 2024)](https://snufa.net/2024)

## Abstract

In military and marine applications, very high frequency (VHF) signals are commonly used for sensitive communications. As of now, prior to transmission, radios communicate their identity to their intended receivers, however their real identity are not further verified. Meanwhile, radio emitters have intrinsic radio frequency (RF) properties that make them unique. 

We propose to exploit their uniqueness to validate the actual identity of the radio emitters so as to make marine and, in general, military communications more secure. The goal of our work is to train a spiking neural network (SNN) for the authorization problem, which is to distinguish transmitters between two classes: authorized and unauthorized.

For this, we use a dataset that was created with the help of CorteXlab, a radio testbed at INSA Lyon. It contains recorded packets of several identical radios, whose RF characteristics are slightly different, as they only depend on manufacturing variability. The dataset is based on all identical packets for every radio, which are not identifiable through regular means.

Our findings show that a SNN can indeed recognize authorized from non-authorized radios with a accuracy of up to 99% while achieving a false positive rate of 0.15% which shows promising perspectives for adding reliability to military communications.