---
title: "MÆSTRO"
collection: software
type: ""
permalink: /software/apprentice
venue: ""
date: 2022-07-20
location: "Argonne National Laboratory"
---
Mæstro ([code](https://github.com/HEPonHPC/maestro) and [documentation](https://mstro.readthedocs.io/en/latest/introduction.html)) stands for Multi-fidelity Adaptive Ensemble Stochastic Trust Region Optimization and it is an open source plug n play derivate fee stochastic optimization solver. The problem being considered in MÆSTRO involves fitting Monte Carlo simulations that describe complex phenomena to experiments by finding parameters of the resource intensive and noisy simulation that yield the least squares objective function value to a noisy experimental data. This problem is solved using an active machine learning algorithm where in each iteration, a local approximation of the simulation signal and of the simulation noise is constructed over data, which is obtained by running the simulation at strategically placed design points within a trust-region around the current iterate. Then the simulation components of the objective are replaced by their approximations and this analytical and closed-form optimization problem is solved to find the next iterate within the trust-region. Then the trust region is moved and the iterations continue until a satisfactory convergence criteria is met.
