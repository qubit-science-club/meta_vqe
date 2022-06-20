# Meta-VQE - different cases

This is the forked repository for the article "The Meta-Variational Quantum Eigensolver (Meta-VQE): Learning energy profiles of parameterized Hamiltonians for quantum simulation", Alba Cervera-Lierta, Jakob S. Kottmann, Alán Aspuru-Guzik, [arXiv:2009.13545[quant-ph]](https://arxiv.org/abs/2009.13545).

We wanted to analyze the behaviour of the Meta-VQE algorithm with the scaling of the size of the system under study. To do that we calculated the ground state energies, using a range of different methods, for 4 different systems - three 1D chains and one 2D square grid. Below we present our results.

__1D system - 7 qubits__

![](new_plots/1d_7q/plot1.png)
![](new_plots/1d_7q/plot2.png)
![](new_plots/1d_7q/plot3.png)
![](new_plots/1d_7q/plot4.png)

__1D system - 8 qubits__

![](new_plots/1d_8q/plot1.png)
![](new_plots/1d_8q/plot2.png)
![](new_plots/1d_8q/plot3.png)
![](new_plots/1d_8q/plot4.png)

__1D system - 9 qubits__

![](new_plots/1d_9q/plot1.png)
![](new_plots/1d_9q/plot2.png)
![](new_plots/1d_9q/plot3.png)
![](new_plots/1d_9q/plot4.png)

__2D system - 9 qubits__

![](new_plots/2d_9q/plot1.png)
![](new_plots/2d_9q/plot2.png)
![](new_plots/2d_9q/plot3.png)
![](new_plots/2d_9q/plot4.png)

We can see, that with the increasing size of the 1D lattice the algorithm is loosing precision. This is all the more apparent when we move to the 2D case, where the number of connections between different sites is significantly larger than in a simple chain.
