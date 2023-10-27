# Noise cancellation and visual processing using Resonate-and-Fire neurons

**Authors:** Reem Al Fata, Jules Lecomte

**Presentation type:** Flash talk

## Abstract

Spiking neural Networks (SNN) are designed as the most biologically realistic neural networks. The Leaky Integrate and Fire (LIF) neuron is the simplest and most widely used neuron model, but it lacks biological realism. Another neuron model has been described in literature as much more accurate: the resonator neuron. Its simplest implementation, which is similar to the LIF neuron, and as computationally effective, outclasses it with regards to biological accuracy. It is called the Resonate-and-Fire (RF) neuron. The RF neuron can be used in different ways and solve multiple tasks, such as optical flow estimation, object classification and proves to reach better accuracy in terms of performance than LIF-only networks.  

One of the most interesting features of the RF neuron which we will present is noise cancellation. This neuron, rather than replacing the LIF neuron, is used in conjunction with it to solve a wider variety of tasks. As each neuron resonates at a specific frequency, it can filter out non periodic signals. Thus, it behaves like a Short-Time-Fourier-Transform with an exponential window. As such, we explored the use of a population of RF neurons ahead of a LIF network as a preprocessing tool. 

We demonstrated a way to combine RF neurons and a LIF Dynamic Neural Field network to solve a visual asset identification task. Initial results demonstrate the potential of the RF neuron in a real-world application, as well as showcasing the possibilities they can offer in SNN. Furthermore, we explore multi-RF neurons connectivity to emulate other biological features such as memorizing phase shifts between two neurons. The biological realism of these neurons combined with its low computational cost presents an untapped potential in a wide range of applications. 