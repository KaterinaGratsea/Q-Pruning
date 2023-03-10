# Quantum circuit optimization with pruning

There are many pruning methods in the literature for classical machine learning models. On the contrary, this field is quite new for quantum machine learning models. 

Here we introduce a simple pruning method to optimize parametrized quantum circuits with the end goal of reducing the number of parameters needed while remaining within chemical accuracy. Importantly, the pruning method introduced could be applied to any Hamiltonian independent of the symmetries of the system. 

We apply this optimization technique to the BeH2 molecular Hamiltonian and compare the results with the recent work of <a href="https://www.nature.com/articles/nature23879" title="link"> Kandala et. al. </a>. Interestingly, we can reduce the number of parameters of the circuit by approximately 40% compared to the aforementioned work and still remain within chemical accuracy! 

All code is written in Python. Versions of the libraries used:
pennylane 0.18.0, numpy 1.21.4, matplotlib 3.5.1, scipy 1.7.3, jax 0.2.26.
