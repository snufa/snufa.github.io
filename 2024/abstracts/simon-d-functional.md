# Functional Composition of Spiking Neural Networks with Application to Cascade Control

**Authors:** Simon D. Levy
                           


**Presentation type:** Poster at [SNUFA 2024 online workshop (5-6 Nov 2024)](https://snufa.net/2024)

## Abstract

Function composition -- the chaining-together of functions in which the output of each function becomes the input to the next -- is ubiquitous in computing. In cascade control, for example, the output of one controller (e.g., PID controller) is used as a setpoint for a subsequent controller, with the other input to the subsequent controller being a sensor reading. In this paper we present a technique for composing Spiking Neural Networks -- either evolved using a genetic algorithm, or designd by hand -- into chains of functions. Using the TeNNLab Neuromorphic Computing Framework, we show an example application to a simulated quadcopter, in which the inputs are (1) an open-loop ("stick") demand; (2) a lateral velocity reading (from a simulated optical-flow sensor); and (3) an Euler angle (from a simulated accelerometer), and the output is a target angular velocity in degrees per second. To solve the problem of unit scaling and conversion (e.g., lateral velocity in meters-per-second to angles in degrees), we employ the Framework's encoder/decoder mechanism to scale all inputs (open-loop demand, sensor readings) to the interval [-1,+1] and the output to the desired units (degrees per second). Our results compare favorably with standard cascaded PID control, keeping the vehicle stable and within a constrained position radius, and are easily reproduced using the Framework and our open-source quadcopter simulator. We conclude with a discussion for future refinements and the possibility of transferring our cascade-control SNNs to an actual quadcopter vehicle.