# Code for: A priori control of zeolite phase competition and intergrowth using high-throughput simulations


[![DOI](https://zenodo.org/badge/400010078.svg)](https://zenodo.org/badge/latestdoi/400010078)


This repository has the code and data to reproduce all plots from the following paper:

D. Schwalbe-Koda et al. A priori control of zeolite phase competition and intergrowth using high-throughput simulations. Science **374** (6565), 308-315 (2021). DOI [10.1126/science.abh3350](https://doi.org/10.1126/science.abh3350).

All the raw data for the experimental and computational plots are found in the [data](data/) folder. The code used to reproduce the plots is available at the [code](code/) folder.

The Jupyter notebooks require the following packages to run correctly:

```
pandas
numpy
matplotlib
seaborn
```

The full atomistic simulation data can be downloaded at the Materials Data Facility under the DOI [10.18126/c5z9-zej7](https://doi.org/10.18126/c5z9-zej7). Instructions on how to download the data from a Python shell can be found in the [Foundry](https://github.com/MLMI2-CSSI/foundry) repository.

## Description of the data

The raw data folder contains all results shown in the paper, including:

 - Tabulated data for all main figures and for the figures in the Supporting Materials
 - NMR and XRD spectra for the as-prepared and calcined zeolites, as well as for the reference materials

## Related links

 - [VOID](https://github.com/learningmatter-mit/VOID): code to automate docking of molecules in zeolites.
 - [GULPy](https://github.com/learningmatter-mit/gulpy): Python interface to the GULP simulation software.
