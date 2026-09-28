---
title: "Outer Optimization"
collection: software
type: ""
permalink: /software/outeroptimization
venue: ""
date: 2021-04-15
location: "Argonne National Laboratory"
---
Open-source tool that decides how much weight each piece of data deserves when tuning a model. It sets the weights automatically instead of by experience and intuition, so results are reached efficiently and are less subjective.

Outer optimization ([CODE](https://bitbucket.org/iamholger/pyoo/src/master/)) is an open source package to assign weights and solve the tuning problem of finding optimal parameters that minimizes the a least-squares function between approximations of noisy simulations and experimental data or data observed in nature. Instead of setting weights manually based on experience and intuition, the weights are automatically adjusted using a bilevel optimization or a single level robust optimization formulation, thus yielding results efficiently that are less subjective.
