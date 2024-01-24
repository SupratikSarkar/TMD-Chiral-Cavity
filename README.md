## TMD-Chiral-Cavity

This repository contains the main simulations and data analysis files (except Lumerical FDTD simulations) for the manuscript [arXiv:2308.04574](https://arxiv.org/abs/2308.04574).

Parts of the code were developed by Dr. Daniel Suarez and Dr. Andrey Grankin. Parts of Transfer_matrix_method.nb were taken from the Fresnel equation solver written by [Steven Byrnes](https://sjbyrnes.com/).

The repository is divided into 3 folders:
1. **Transfer_Matrix_Method** has a Mathematica notebook _Transfer_matrix_method.nb_ which has the code used for transfer matrix method (TMM) simulations. All necessary files to run the code are present in the Transfer_Matrix_Method/Files folder. One only needs to set the proper path to the files in the notebook after downloading it.
2. **1D_waveguide_model** has a Mathematica notebook _1D_waveguide_model.nb_. In this notebook we simulate the reflection spectrum and electric field profile of the cavity by simulating it as two two-level emitters coupled to a 1D waveguide.
3. **Magnetic_field_sweep** has a python notebook _MagneticField.ipynb_ for analysis of the magnetic field sweep data NKT_B_sweep.txt. All necessary files to run the code are present in the folder. One only needs to set the proper path to the files in the notebook after downloading it.
