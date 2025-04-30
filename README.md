# Ground States of Nonlinear Schrödinger Equation on the Tadpole Graph with a Repulsive Delta-Vertex Condition

This repository contains the Jupyter notebook used to perform the numerical computations and generate the figures presented in Section 5 of the article _Ground States of Nonlinear Schrödinger Equation on the Tadpole Graph with a Repulsive Delta-Vertex Condition_ by Romain Duboscq, Elio Durand-Simonnet and Stefan Le Coz.

## Grafidi library

This notebook uses the Grafidi library in order to perform computations on metric graphs. You can have access to the Grafidi library here: https://plmlab.math.cnrs.fr/cbesse/grafidi. Put the Grafidi.py file in the active directory.

## Details of the notebook
- The first chunk provides all libraries necessary for the code, including the Grafidi library.
- The second chunk provides the functions used in the gradient descent algorithm, see (5.1) in the paper.
- The third chunk provides the parameters omega, gamma and Length (which is a list) used for the simulations in Figures 7 and 8. You may change those parameters in order to try other simulations, as the one in Figure 9. Other parameters, as the stop criterion of the gradient descent algorithm, are provided.
- The fourth chunk computes the ground state of the cubic nonlinear Schrödinger solution of the tadpole graph with a Delta-vertex condition (associated with the parameter $gamma$) for the lengths stacked in the list Length.
- The fifth and the sixth chunk 


