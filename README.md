# rFM

Work in progress - Developing a R package for Factorization Machines (FM)

From libfm.org: "Factorization machines (FM) are a generic approach that allows to mimic most factorization models by feature engineering. This way, factorization machines combine the generality of feature engineering with the superiority of factorizatin models in estimating interactions between categorical variables of large domain." <p><libFM,https://github.com/srendle/libfm></p> is a software implementation for factorization machines that features stochastic gradient descent (SGD) and alternating least squares (ALS) optimization as well as Bayesian inference using Markov Chain Monte Carlo (MCMC).

This uses stochastic gradient descent with adaptive regularizatin as a learning method, which adapts the regularization automatically while training the model parameters. See [2] for details. 

[1] Steffen Rendle (2012): Factorization Machines with libFM, in ACM Trans. Intell. Syst. Technol., 3(3), May. 
[2] Steffen Rendle: Learning recommender systems with adaptive regularization. WSDM 2012: 133-142


