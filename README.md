# Model-Selection
Machine Learning: Model Selection 

# Objective
Explore different model selection strategies to determine the number of clusters required for a Gaussian mixture clustering of this data (in the 2D PCA space) and the correct choice of covariance matrix structure (from the options listed above).

The project will try multiple methods (BIC, AIC, Silhouette, and cross-validation)

Explore the clusterings suggested by each method, and look to see which digits are being grouped or split (if the optimal number is not 10 (digits 0-9).

# Mixture Models

Statistical mixture models are somewhat related to K-means but place the clustering problem within a statistical framework.

We will use Gaussian mixtures: models in which data from each cluster is assumed to come from a different Gaussian. With mixture models we have two model selection challenges: choosing 𝐾 and choosing the form of the Gaussian covariance matrices:

spherical: the covariance matrices are of the form 𝜎2𝐈 (where 𝐈 is an identity), i.e. the variance is the same in all dimensions and there is no correlation structure

diagonal: there is no correlation structure, but the variance can be different in each dimension

tied: all Gaussians share the same covariance matrix

full: each Gaussian can have a different covariance matrix that can have full correlation structure

# Reference 

https://scikit-learn.org/stable/auto_examples/mixture/plot_gmm_covariances.html

University of Glasgow COMPSCI 5090
