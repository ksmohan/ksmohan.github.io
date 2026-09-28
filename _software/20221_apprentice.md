---
title: "Apprentice"
collection: software
type: ""
permalink: /software/apprentice
venue: ""
date: 2022-07-01
location: "Argonne National Laboratory"
---
Open-source tool that builds fast, simple formulas to stand in for slow, costly simulations. Because the formulas are quick to run, they can be optimized quickly.

Apprentice ([code](https://github.com/HEPonHPC/apprentice/tree/main) and [documentation](https://apprentice.readthedocs.io/en/latest/introduction.html)) is an open source package for construction of multivariate analytic surrogate model for computationally expensive Monte-Carlo predictions. The surrogate model is used for numerical optimization of a prediction function since it can be prohibitively expensive to perform optimization over functions with the Monte-Carlo predictions. To summarize, Apprentice can be used for performing three tasks:
  * Construct [surrogate models](https://apprentice.readthedocs.io/en/latest/surrogate_models.html#apprentice-surrogatemodels) to computationally expensive Monte-Carlo predictions
  * Formulate a [prediction function](https://apprentice.readthedocs.io/en/latest/functions.html#apprentice-functions) with surrogate models
  * Perform [numerical optimization](https://apprentice.readthedocs.io/en/latest/optimization.html#apprentice-optimization) over the prediction function
