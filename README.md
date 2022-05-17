# PhD_Digital_Appendix_1.2_ENMeval_optimal_models

This repository is the second digital appendix created to suplement my PhD thesis "Resources to Aid Decision-Making in Conservation Translocations" submitted to the University of Otago in November 2021.

As these digital appendices are not intended to be stand alone, I intend to upload a pdf file of my thesis once it is accepted and finalised to provide further context for the repository content.

This second appendix provides further details of the optimal versions of correlative habitat suitability models that were averaged to generate the resultss presented in Chapter 4 of my thesis "Predictive Modelling: Relict Distribution Habitat Models".

The repository is split into two folders, containing replicates of conservative and extrapolative model replicates respectively (more details of the concepts behind these model categories are presented in the paper linked here: https://www.frontiersin.org/articles/10.3389/fcosc.2021.691714/full, with further methodological details contianed in the suplementary materials of this paper).

The conservative model and extrapolative model folders each contain a four files, each of which is a table containing detials of setting, output and result metrics of the 40 replicates identified as optimal models from each replication of ENMeval conducted as part of my thesis research. These tables are outputs from the ENMeval package in R (Muscarella R, Galante PJ, Soley-Guardia M, Boria RA, Kass JM, Uriarte M, Anderson RP 2014. ENMeval: An R package for conducting spatially independent evaluations and estimating optimal model complexity for Maxent ecological niche models. Methods in Ecology and Evolution 5(11): 1198–1205.), while details of model inputs and settings are contianed within the suplementary materials of the Fronteirs paper linked above.

The first and third files contain detials of the input settings for each optimal model along with corresponding output metrics generated for each optimal model (the .xlsx version of the 'Settings_and_Outputs' file also contains means and standard deviations accross these settings and metrics). The second file contains detials of all output metrics relating to each optimal model and the fourth file contains output values for percent contribution and permutation importance for each predictor variable and each model replicate (including means and standard deviations accross replicates).
