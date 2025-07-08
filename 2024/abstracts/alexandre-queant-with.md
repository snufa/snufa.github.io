# A SNN with plastic delays could provide a mechanistic understanding of V1 responses to dynamic stimuli.

**Authors:** Alexandre Queant, Ulysse Rançon, Dan Goodman, Benoît Cottereau and Timothée Masquelier
                           
**Presenting author:** Alexandre Queant

**Presentation type:** Flash talk at [SNUFA 2024 online workshop (5-6 Nov 2024)](https://snufa.net/2024)

## Abstract

We trained a spiking neural network (SNN) with learnable delays on a neural response fitting task with visual stimuli, in order to find a mechanistic explanation for the observed activity. We aimed to determine how much learning the delays improved predictions on this task, as well as how the delays behaved in our network and shaped the latencies when learning to process natural videos.

We used an SNN constrained by Dale’s law, with trainable delays on a dataset containing macaque V1 neural responses to natural videos (Ringach and Nauhaus, Single- and multi-unit recordings from primary visual cortex, 2009). Our network performed remarkably well, outperforming state-of-the-art deep learning models such as gated recurrent units (GRUs) and achieving state-of-the-art accuracy on the dataset. We also found that trainable delays significantly improved performance, suggesting that myelin plasticity may play a major role in shaping these neural responses.

We are now working on quantifying motion direction selectivity in our trained neurons with a deep-dream inspired technique, and we are investigating whether this selectivity emerges from two different types of neurons in the population: one with short latencies in response to a stimulus, and another with longer latencies. This mechanism was proposed by De Valois in 1998 based on biological observations. More specifically, he posited that motion selectivity in primate visual cortex results from a delay between the neural responses of monophasic and biphasic cells. Our model could corroborate this theory.