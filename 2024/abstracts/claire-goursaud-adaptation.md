# Adaptation of SNN for Sequence Detection in a Wake Up Receiver

**Authors:** Pierrick JOSEPH, Guillaume MARTHE, Claire GOURSAUD
                           
**Presenting author:** Pierrick JOSEPH

**Presentation type:** Poster at [SNUFA 2024 online workshop (5-6 Nov 2024)](https://snufa.net/2024)

## Abstract

Wake up radio receivers are already studied as an efficient solution to limit the energy consumption of the signaling process in an IoT network. The principle is to use a very simple receiver whose only goal is to continuously monitor the channel. Its aim is to detect if a specific activation sequence is transmitted : if so, it awakes the main tranceiver for handling the communication. 
However, they currently rely on classical processors, and thus still consume too much. In this work, to reduce this energy consumption, we propose to exploit a SNN architecture to perform the sequence recognition. 
However, as the channel conditions are evolving in time, we need to train the SNN so as to be efficient independantly of these various conditions. We thus focused on the way to apply the STDP learning rule. In particular, we focused on the noise impact on the learning strategy and the performances. 
We first show that the SNN succeeds in performing the sequence detection accurately, and almost the same accuracy than the conventional receiver. Besides, we show that the SNN can be trained with a noiseless dataset, and can still generalize to the noisy case. The next step is to extend this study to evolving channel coefficients.
