# ML-protocol-topo-indices-1d



Contains code for <a href="https://arxiv.org/abs/2008.07268">https://arxiv.org/abs/2008.07268</a>. 

This work is closely related to <a href=https://github.com/mats-granath/topo-augmentation-ML-protocol>topo-augmentation-ML-protocol</a> based on <a href="https://arxiv.org/abs/1908.03469">https://arxiv.org/abs/1908.03469</a>.


Here we show how:

1. Produce datasets of topologically equivalent samples: Create symmetry-respecting matrices, stack the parents with the atomic-limit states, continuously deform the states via topological data augmentation.



2. Train a neural network classifier for extracting the topological indices. The training is done within TensorFlow (Keras).



Oleksandr Balabanov and Mats Granath



## Prerequisites



Python 3



## Installation



The required libraries are matplotlib, numpy, jupyter, and tensorflow (tensorflow-gpu).



## The code



The code is given in format of jupyter notebooks. There are three folders correspoding to three different cases considered in our article: 1d topological systems respecting the chiral (class AIII), particle-hole (class D), or inversion symmetry. Each folder contains seperate files for creating the symmetry-respecting matrices, generating the parents, producing the training data from the parents, training the neural network classifiers. 

