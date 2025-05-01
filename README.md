

## epotMicropolarFoam: An open-source solver for simulation of MHD micropolar flows based on OpenFOAM. This solver is based on the transient solver icoFoam to include micropolar effects and the influence of the applied magnetic field using the low-magnetic-Reynolds-number approximation (electric potential formulation).

## Copyright
epotMicropolarFoam is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version. See LICENSE or http://www.gnu.org/licenses/, for a description of the GNU General Public License terms under which you can copy the files.

## Directory structure
Applications: 
1. applications/solvers/epotMicropolarFoam

Tutorials:
1. tutorials/artery flow
2. tutorials/poiseuille flow


## Compiling 
1. The solver, epotMiropolarFoam, is developed based on OpenFOAM V6. Before installing the solver, please ensure you have installed OpenFOAM V6. Please refer to https://openfoam.org/download/6-ubuntu.

To compile epotMicropolarFoam execute:
   cd applications/solvers/epotMiropolarFoam
   ./wmake


## epotMicropolarFoam tutorials
To run a tutorial execute:
tutorials/artery flow
./epotMicropolarFoam
or
tutorials/poiseuille flow
./epotMicropolarFoam


## Getting help and reporting bugs
Please submit a GitHub issue if you found a bug in the program. If you need help with the software or have further questions, contact Kyriaki-Evangelia Aslani: kiriaki022@gmail.com and k.aslani@go.uop.gr.


## Citation
Please cite as: Kyriaki-Evangelia Aslani, Ioannis Sarris, Efstratios Tzirtzilakis. On the development of OpenFOAM solvers for simulating MHD micropolar fluid flows with or without the effect of micromagnetorotation. DOI: 10.48550/arXiv.2504.14543.

