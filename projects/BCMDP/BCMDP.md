My MSc thesis was on Burstiness-Constrained Markov Decision Processes (BCMDPs), a class of constrained optimization problems applied to dynamic systems. This work was conducted at the Technion - Israel Institute of Technology, within the Faculty of Electrical Engineering, and supervised by Prof. Nahum Shimkin.

## Key Concept: Burstiness Constraints

The research imposed standard Markov Decision Processes (MDPs) with $(\sigma, \rho)$-burstiness constraints. Originally derived from network calculus, these constraints are used to limit an additive quantity (like data transmission, energy consumption, or queue length) to a given long-term rate $(\rho)$, while allowing for limited, occasional overages (bursts, $\sigma$).

The main contribution was developing an **augmented-state model** to transform the inherently history-dependent problem into one solvable by standard dynamic programming methods. Building upon this model, I **proposed efficient algorithms** to solve the BCMDP problem and **proved their convergence and correctness (optimality of the resulting policy)**.

<p align="center"><img src="BCMDP.png" width="500"/></p>

## Thesis
[Full Thesis (pdf)]("BCMDP thesis.pdf")
```bibtex
@misc{alma990026208320203971,
    title = {Burstiness-constrained Markov decision processes / Michal Golan; [supervision: Nahum Shimkin].},
    author = {Golan, Michal. and Shimkin, Nahum and Technion - Israel Institute of Technology. Faculty of Electrical Engineering},
    publisher = {[s.n.]},
    year = {2016},
    url = {https://technionmail.sharepoint.com/:b:/r/sites/library-storage/Shared%20Documents/thesis/ele/2620832.pdf?web=1&parent=Technion},
}
```

## Paper
[Published Paper on EJOR (pdf)]("BCMDP EJOR publicaion.pdf")
```bibtex
@article{GOLAN2024877,
    title = {Markov decision processes with burstiness constraints},
    author = {Michal Golan and Nahum Shimkin},
    journal = {European Journal of Operational Research},
    volume = {312},
    number = {3},
    pages = {877-889},
    year = {2024},
    issn = {0377-2217},
    doi = {https://doi.org/10.1016/j.ejor.2023.07.045},
    url = {https://www.sciencedirect.com/science/article/pii/S0377221723006045},
}
```


