This repository contains the code for MAT4900 on supersingular isogeny graphs. I suggest running the SageMath code CoCalc for minimal setup.

The notebook contains the following functions:
supersingular_isogeny_graph(p, l): a function to generate a supersingular l-isogeny graph over the closure of Fp
supersingular_isogeny_graph_with_levels(p, l, N): a function to generate a supersingular l-isogeny graph with level-N structures over the closure of Fp
ihara_zeta(G): a function to compute the Ihara zeta function of a l+1-regular graph
modular_curve_zeta_function(p, l, N): a function to compute the Hasse-Weil zeta function of the X0(pN) modular curve over Fl. If not using level structures, then N = 1 can be used.
zeta_product_no_levels(p, l): a function to compute the expected product of the Ihara zeta function and X0(p) modular curve as proven by Sugiyama in https://arxiv.org/abs/1905.04297
zeta_product_with_levels(G): a function to compute the right hand side of the relationship between a supersingular l-isogeny with level-N structure graph and 
the modular curves X0(pN) and X0(N) as proven by Lei and Müller in https://arxiv.org/abs/2307.01001

Some examples that were used in the report are included. Including a toy example of the SIDH protocl over F97^2. 
