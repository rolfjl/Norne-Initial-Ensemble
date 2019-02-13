# Norne-Initial-Ensemble
This repository contains Matlab code and description for generating an initial ensemble for the Norne model. 

File description:

- NorneInitialEnsemble.m: 

The main function for generating the ensemble. The input to the function are ensemble size and a number used to initialize the random generator. For more information we refer to the paper: 

Lorentzen, R., Luo, X., Bhakta, T., Valestrand, R.: "History Matching the Full Norne Field Model Using Seismic and Production Data ", SPE Journal, January 2019. DOI: https://doi.org/10.2118/194205-PA.
 
We also ask that the above paper is cited in publications aided by this code.

- NorneGeostat.m: 

All geostatistical parameters used to generate the ensemble. Edit this file to change the properties of the ensemble. 

- FastGaussian.m: 

Generates random vector from distribution satisfying Gaussian variogram in 2-D.

- ACTNUM_0704.prop: 

The Eclipse datafile specifying active gridcells.

- FAULTMULT_AUG-2006.INC:

The Eclipse datafile specifying the fault multipliers. 

- NTG_0704.prop:

The Eclipse datafile specifying the Net-To-Gross values.

- PERM_0704.prop:

The Eclipse datafile specifying the permeability values.

- PORO_0704.prop:

The Eclipse datafile specifying the porosity values.
