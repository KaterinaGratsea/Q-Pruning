# Quantum circuit optimization with pruning

In this demo, we present a quantum circuit optimization with pruning which successfully reduces the number of one- and two- qubit parameterized gates of the variational quantum circuit up to a significant degree while remaining within chemical accuracy.

Interestingly, the given parameter optimization method works independent of the Hamiltonian of the system and its symmetries. 

We start by an overparametrized circuit and gradually reduce the parameters by pruning the gates that are close to the Identity operator at each pruning run and use jax to speed-up the otpimization process.

 The main goal of this tutorial is to show that the idea of pruning that comes from classical neural networks works also well for quantum variational circuits and leads to parametrized quantum circuits with a significant less number of parameters while remaining within chemical accuracy!
