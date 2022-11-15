# Memory-and-criticality-in-Reservoir-Computing

This repository contains the scripts to train a Reservoir Computing (RC) network to perform memory and non-linear computaitonal tasks at different distances from the critical point. The repository also includes code to monitor the evolution of a Hopfield-like network developed by Derrida et al., 1987 (doi: 10.1209/0295-5075/4/2/007) when input is added to the network and for varying parameters, to see how sparsity, temperature and number of patterns stored affect the evolution of two spin configurations.

This repository contains the code for my MSc thesis, that shows that for computaitons requiring short-term memory in RC networks, sub-critical (slightly ordered) dynamics are beneficial.

- "reservoir_network_training.ipynb": Code to generate a given RC network, calculate the criticality conditions, train the network on two short-term memory tasks and test the network.

- "data_analysis.ipynb": Data analysis for statistical significance and result plots generated from training and testing in the RC network. A theoretical evolution of the probability of the input affecting the network is simulated computaitonally as well.

- "evolution_2config.ipynb": Evolution of two spin configurations as described in Derrida et al., 1987 that recieve a stream of binary input. If the two configurations diverge in time, the network setup is in the chaotic regieme, whereas if the configurations converge in state, the network is in the ordered regieme.
