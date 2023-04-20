# Evoverse codebase

This repo contains all the code created and used in the paper, from annotations to the final figures.

It is divided according to the main parts of the work, in particular we have:

1.mobsterh_sims -> MobsterH model and simulation
2.subclonal_analysis -> Subclonal analysis of WGS cohorts
3.driver_analysis -> Pipelien for driver calling and annotation
4.mutation_timing -> Scripts and plots for mutation timing
5.clinical_association -> Survival analysis and association of evolutionary features with clinical variables
6.signature_and_dn_ds -> Mutational Signature Analysis and DN/DS analysis
7.RNA_sequencing -> Hartwig RNA seq analysis
8.repeated_evolution -> Repeated evolution analysis using REVOLVER
9.paper_figures -> Code to reproduce the figures in the paper

The project has it's own Wiki with an in depth description of the sub-folders and script, plus a short paragraph on the rationale of the analysis.

The main R dependences to run this code can be installed by running this line, most of the functions are based on the R package [evoverse](https://github.com/caravagn/evoverse)
 
```{R}
Rscript install_deps.R
```
We use conda to install python packages and interface them with reticulate, upon installing conda you can set up the environment needed to run 
```{bash}
bash create_conda_envs.sh
```
We also provide (TODO) a docker image with all the necessary packages, that can be built by running:
```{bash}
```

EVOVERSE is an incredible collaborative effort across multiple accademic institutions. 
People involved in this project:
### ADD PEOPLE
