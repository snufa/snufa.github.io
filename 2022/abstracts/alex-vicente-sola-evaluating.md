
# Evaluating the temporal understanding of spiking neural networks on event-based action recognition with DVS-Gesture-Chain

**Authors:** Alex Vicente-Sola

**Presentation type:** Poster

## Abstract

Enabling artificial neural networks (ANNs) to have temporal understanding in visual tasks is an essential requirement in order to achieve complete perception of video sequences. A wide range of benchmark datasets is available to allow for the evaluation of such capabilities when using conventional frame-based video sequences. In contrast, evaluating them for systems targeting neuromorphic data is still a challenge due to the lack of appropriate datasets. In this presentation a new benchmark task for action recognition in event-based video sequences will be introduced, DVS-Gesture-Chain (DVS-GC) which is based on the temporal combination of multiple gestures from the widely used DVS-Gesture dataset. This methodology allows to create datasets that are arbitrarily complex in the temporal dimension. Using the newly defined task, we have evaluated the spatio-temporal understanding of different feed-forward convolutional ANNs and convolutional Spiking Neural Networks (SNNs). This study proves how the original DVS Gesture dataset could be solved by networks without temporal understanding, unlike the new DVS-GC which demands an understanding of the ordering of events. From there, we provide a study showing how certain elements such as spiking neurons or time-dependent weights allow for temporal understanding in feed-forward networks without the need for recurrent connections.