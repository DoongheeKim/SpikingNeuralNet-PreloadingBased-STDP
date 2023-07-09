##  A STDP-based Spiking-Neural-Network for Time Series Data and Synapatic Weight Initialization

This project aims at investigating a new approach to
synapatic weight initialization in STDP-based spiking neural 
networks.
Spike-Time Dependent Plasticity(STDP) is a learning rule 
for Spiking Neural Network(SNN) that simulates human brain activity. It is known to be simple and hardware-friendly.
There are various parameters to affect
the performance of SNN.
We believe that one of major parameters is synaptic weight initialization.

STDP-based SNN shows so-called generative property. 
The weights of all the synapses connected to a neuron at the output layer, 
if rearranged in form of a 2d data (i. e. image) after training,
depicts the pattern that the neuron has learned.

In this project, we normalize the input data used for learning and
then initialize synatics weights using it.
We analyzed the usefulness of our approach 
for a time-series data set in SNN for classification.

## Data Set
- Transient gas responses of different types and concentrations, measured using a semiconductor sensor
- additional measurements that are generated using noise addition and interpolation
based on the directly obtained ones.


## Results
In a few experiments, it is shown that
our approach achieves the learning speed and
better classification, compared to 
weight initialization by randomness.


## Paramters
The are a large number of parameters that play a role in 
the performance of STDP-based SNN.
More studies are needed to investigate how
the performace of our approach is affected according to various settings of paramters.


## Implementation
The source code is based on reference [1].
Refer to NOTE file for more detail.

## Acknowledgement
I was helped on this project by my colleagues 
for in-depth SNN study and advices on implementation.


## Reference
[1] https://github.com/Shikhargupta/Spiking-Neural-Network


