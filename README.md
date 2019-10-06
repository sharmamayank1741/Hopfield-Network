# Hopfield-Network
Artificial Neural Networks (ANN) - Hopfield Network

A Hopfield network is a form of recurrent artificial neural network.
Updating one unit (node in the graph simulating the artificial neuron) in the Hopfield network is performed using the following rule:

{\displaystyle s_{i}\leftarrow \left\{{\begin{array}{ll}+1&{\mbox{if }}\sum _{j}{w_{ij}s_{j}}\geq \theta _{i},\\-1&{\mbox{otherwise.}}\end{array}}\right.}s_{i}\leftarrow \left\{{\begin{array}{ll}+1&{\mbox{if }}\sum _{{j}}{w_{{ij}}s_{j}}\geq \theta _{i},\\-1&{\mbox{otherwise.}}\end{array}}\right.

where:

{\displaystyle w_{ij}}w_{ij} is the strength of the connection weight from unit j to unit i (the weight of the connection).
{\displaystyle s_{j}}s_{j} is the state of unit j.
{\displaystyle \theta _{i}}\theta _{i} is the threshold of unit i.
