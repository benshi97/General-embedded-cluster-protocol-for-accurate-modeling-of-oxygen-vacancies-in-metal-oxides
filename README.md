[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/benshi97/Data_Embedded_Cluster_Protocol/HEAD?labpath=analyse_data.ipynb)

This repository accompanies the paper **General embedded cluster protocol for accurate modeling of oxygen vacancies in
metal-oxides** by Benjamin X. Shi, Venkat Kapil, Andrea Zen, Ji Chen, Ali Alavi and Angelos
Michaelides ([arXiv 2202.04633 ](https://arxiv.org/abs/2202.04633)).

The data for plotting all of the graphs in the main text and supplemental material can be found in the folder `02-Simulation_Data`. The folder `01-Input_Generation` provides the scripts (with examples) for generating the metal-oxide quantum clusters with the SKZCAM approach. The notebook `analyse_data.ipynb` can be explored interactively with [Binder](https://mybinder.org/v2/gh/benshi97/Data_Embedded_Cluster_Protocol/HEAD?labpath=analyse_data.ipynb). The figures generated by `analyse_data.ipynb` are stored in the `03-Figures` folder.


## Paper abstract

The O vacancy (Ov) formation energy, *E*<sub>Ov</sub>, is an important property of a metal-oxide, governing its performance in applications such as fuel cells or heterogeneous catalysis. These defects are routinely studied with density functional theory (DFT). However, it is well-recognized that standard DFT formulations (e.g. the generalized gradient approximation) are insufficient for modeling the Ov, requiring higher levels of theory. The embedded cluster method offers a promising approach to compute *E*<sub>Ov</sub> accurately, giving access to all electronic structure methods. Central to this approach is the construction of quantum(-mechanically treated) clusters placed within suitable embedding environments. Unfortunately, current approaches to constructing the quantum clusters either require large system sizes, preventing application of high-level methods, or require significant manual input, preventing investigations of multiple systems simultaneously. In this work, we present a systematic and general quantum cluster design protocol that can determine small converged quantum clusters for studying the Ov in metal-oxides with accurate methods such as local coupled cluster with singles, doubles plus perturbative triples excitations \[CCSD(T)\]. We apply this protocol to study the Ov in the bulk and surface planes of rutile TiO<sub>2</sub> and rocksalt MgO, producing the first accurate and well-converged determinations of *E*<sub>Ov</sub> with this method. These reference values are used to benchmark exchange-correlation functionals in DFT and we find that all studied functionals underestimate *E*<sub>Ov</sub>, with the average error decreasing along the rungs of Jacob’s ladder. This protocol is automatable for high-throughput calculations and can be generalized to study other point defects or adsorbates.