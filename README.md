DPMM Baseball Case Replication

Replication of the Dirichlet Process Mixture Model (DPMM) for baseball batting averages, based on MacEachern's (1998) paper.
Overview

This project implements a DPMM to analyze baseball player batting averages, clustering players with similar performance profiles.
Files

    DPMM_baseball.ipynb - Main Jupyter notebook with DPMM implementation

Model Features

    Collapsed Gibbs sampling for cluster assignments

    Beta-Binomial likelihood for batting averages

    Automatic determination of number of clusters

    MCMC sampling with Metropolis-Hastings for hyperparameters

Requirements

    Python 3.x

    NumPy

    SciPy

    Matplotlib (for visualization)

Usage

Run the notebook sequentially to:

    Load baseball data

    Run MCMC sampling

    View cluster assignments and player groupings

Results

The model identifies latent performance clusters among players, with posterior estimates for individual batting abilities.
