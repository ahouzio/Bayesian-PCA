## Overview

 This repository contains the code for the project for the “Bayesian Machine Learning” course of the MVA master. Our exploration centered around the Bayesian PCA (BPCA) and the Probabilistic PCA (PPCA) framework which BPCA is based on. We studied these methods from a statistical viewpoint by comparing their performance on a synthetic dataset. Additionally, we explored their potential role in the estimation of missing data.

 ## Structure

**Jupyter Notebooks**: 
* `PPCA Notebook.ipynb`: PPCA implementation and comparison with PCA on a synthetic data. We run various experiments : 
    * Comparison of the PPCA and PCA on the iris dataset.
    * Robustness of PPCA to noise on synthetic datasets(Isotropic vs Anisotropic noise).
    * Rotational ambiguity of PPCA.
    * Estimation of missing data using PPCA.

    * The following functions were implemented: 
        * `PPCA_EM`: Runs the EM algorithm for PPCA 
        * `project_to_latent_space`: Projects the data to the latent space



* `BPCA notebook.ipynb`: BPCA implementation and comparison with PCA on a synthetic data. Experiments consisted of : 
    * Choosing an appropriate number of dimensions for the latent space using BPCA. This was tested on toy datasets of various sizes.
    * Projection of the data to the latent space with a known number of effective dimensions.
      
    * The following functions were implemented: 
        * `BPCA_EM`: Runs the EM algorithm for BPCA
        * `project_to_latent_space`: Projects the data to the latent space

        


