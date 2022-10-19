
# Optic Flow estimation from Event-based cameras and Spiking Neural Networks

**Authors:** CUADRADO Javier, RANÇON Ulysse, COTTEREAU Benoît, BARRANCO Francisco and MASQUELIER Timothée

**Presentation type:** Poster

## Abstract

Event-based cameras are raising interest within the computer vision community. These sensors operate with asynchronous pixels, emitting events, or “spikes”, when the luminance change at a given pixel surpasses a certain threshold. Thanks to their inherent qualities, such as their low power, low latency and high dynamic range, they seem particularly tailored to applications with challenging temporal constraints and safety requirements. Event-based sensors are an excellent fit for Spiking Neural Networks, since the coupling of an asynchronous sensor with neuromorphic hardware can yield to real-time systems with minimal power requirements. In this work, we seek to develop one such a system, using both Event sensor data (from the DSEC dataset) and spiking neural networks to estimate optical flow for driving scenarios. We propose a U-Net-like SNN which, after supervised training, is able to make dense optical flow estimations. To do so, we encourage both minimal norm for the error vector and minimal angle between ground-truth and predicted flow. In addition, the use of 3d convolutions allows us to represent the temporal context by increasing the bottleneck's temporal receptive field. Upsampling after each decoding stage ensures that each decoder's output contributes to the final estimation. Thanks to separable convolutions, we have been able to develop a light model (when compared to competitors) that can nonetheless yield reasonably accurate optical flow estimates.