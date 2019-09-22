# Predator-prey Integrated Community Model

I have forked this repository to investigate potential projects using the combination of state-space models I am using in my PhD and the matrix population modelling I did for my masters research.

Below is a simple task list for this project with simple timelines.

1. Understand the current paper
2. Fit model in gitbook framework
3. Contact potential collaborators

## Resources

### Orginal content

This repository contains the codes to replicate the results in *Integrating multiple data sources to fit matrix population models for interacting species*, by Barraquand F. and Gimenez O. Ecological Modelling, 2019

* ``analysis_num_exp`` contains codes for plotting the main figures

* ``numerical_experiment`` contains both the numerical experiment of the paper and results shown in Appendix B. All codes, for both simulation and estimation are presented. Only the simulations files are contained within the folders, the estimation files within the ``fitted``subfolder have been deleted (heavy files). They can be reproduced by running the corresponding R scripts or obtained by request to frederic.barraquand@u-bordeaux.fr or olivier.gimenez@cefe.cnrs.fr
* ``difference_equations``: density-dependent matrix models (used in Appendix A)
* ``ipm_devel_codes``: features of the two species that can be considered in development IPMs (identifiability properties of the model discussed in Appendix C, tentative modelling of a saturating predator fecundity discussed in Appendix D).