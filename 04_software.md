---
layout: page
title: Software
permalink: /software/
---

# _pbbo_ ([github](https://github.com/hhau/pbbo))

An `R` package to help translate information about the prior predictive 
distribution (what you think your data might look like before collection) in to
an informative prior for complex models. Built atop a multi-stage, 
multi-objective Bayesian optimisation process to return plausible and useful 
priors.

# _wsre_ ([github](https://github.com/hhau/wsre))

An `R` package implementing the weighted-sample self-density ratio estimation
methodology developed in [this paper](https://arxiv.org/abs/2001.08038). 
Takes joint models written in [`Stan`](https://mc-stan.org) and returns 
self-density ratio estimates that are accurate in low probability regions of the 
prior distribution.

# _rjmonopoly_ ([github](https://github.com/hhau/rjmonopoly))

An `R` package for fitting monotone polynomials of varying degree, using a
reversible jump Markov chain Monte Carlo sampler.
