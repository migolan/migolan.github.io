My MSc thesis was on Burstiness-Constrained Markov Decision Processes (BCMDPs), a class of constrained optimization problems applied to dynamic systems. This work was conducted at the Technion - Israel Institute of Technology, within the Faculty of Electrical Engineering, and supervised by Prof. Nahum Shimkin.

## Key Concept: Burstiness Constraints

The research imposed standard Markov Decision Processes (MDPs) with $(\sigma, \rho)$-burstiness constraints. Originally derived from network calculus, these constraints are used to limit an additive quantity (like data transmission, energy consumption, or queue length) to a given long-term rate $(\rho)$, while allowing for limited, occasional overages (bursts, $\sigma$).

The main contribution was developing an **augmented-state model** to transform the inherently history-dependent problem into one solvable by standard dynamic programming methods. Building upon this model, I **proposed efficient algorithms** to solve the BCMDP problem and **proved their convergence and correctness (optimality of the resulting policy)**.

## Thesis
[Full Thesis (pdf)](BCMDP thesis.pdf)
```bibtex
@misc{alma990026208320203971,
author = {Golan, Michal. and גולן, מיכל. and שימקין, נחום and Shimkin, Nahum and Technion - Israel Institute of Technology. Faculty of Electrical Engineering},
address = {Haifa},
booktitle = {Burstiness-constrained Markov decision processes},
keywords = {Markov processes -- Mathematical models ; Constrained optimization ; Computer networks -- Mathematical models ; Telecommunication -- Traffic -- Mathematical models},
language = {eng},
publisher = {[s.n.]},
title = {Burstiness-constrained Markov decision processes / Michal Golan ; [supervision: Nahum Shimkin].},
url = {https://technionmail.sharepoint.com/:b:/r/sites/library-storage/Shared%20Documents/thesis/ele/2620832.pdf?web=1&parent=Technion},
year = {2016},
}
```



## Paper
[Published Paper (EJOR)](BCMDP EJOR publicaion.pdf)
Citation:
```bibtex
@article{GOLAN2024877,
title = {Markov decision processes with burstiness constraints},
journal = {European Journal of Operational Research},
volume = {312},
number = {3},
pages = {877-889},
year = {2024},
issn = {0377-2217},
doi = {https://doi.org/10.1016/j.ejor.2023.07.045},
url = {https://www.sciencedirect.com/science/article/pii/S0377221723006045},
author = {Michal Golan and Nahum Shimkin},
keywords = {Dynamic programming, Constrained Markov decision processes, Burstiness constraints},
abstract = {We consider a Markov Decision Process (MDP), over a finite or infinite horizon, augmented by so-called (σ,ρ)-burstiness constraints. Such constraints, which had been introduced within the framework of network calculus, are meant to limit some additive quantity to a given rate over any time interval, plus a term which allows for occasional and limited bursts. We introduce this class of constraints for MDP models, and formulate the corresponding constrained optimization problems. Due to the burstiness constraints, constrained optimal policies are generally history-dependent. We use a recursive form of the constraints to define an augmented-state model, for which sufficiency of Markov or stationary policies is recovered and the standard theory may be applied, albeit over a larger state space. The analysis is mainly devoted to a characterization of feasible policies, followed by application to the constrained MDP optimization problem. A simple queuing example serves to illustrate some of the concepts and calculations involved.}
}
```


