# Pedagogical approach of the course Introduction to Bayesian analysis

> Read this document and answer [these questions](https://github.com/VABAR/vibass_dev_introductory_training/issues/1). 
> You can also edit this file to fix things directly, or open [an issue](https://github.com/VABAR/vibass_dev_introductory_training/issues/new/choose) in order to start a discussion or propose a potentially controversial change.

- Meeting 2021-12-17: went through the proposal and the answers to the previous
questions, and revised the Goal of the training and the operational goals.
Here is a [summary of the conclusions of the meeting](20211227_minutes.md).

Below are the current goal and operational goals after incorporating all the
contributions.

## Goal of the training


> What participants will be able to __do__ after the training, that were not able to do before. Avoid verbs like _know_ or _understand_ and focus instead on what this knowledge or understanding enable people to perform.

At the end of the course, participants will be able to start applying Bayesian
methods to simple models in their field, having acquired an understanding of
Bayesian concepts and becoming aware of the possibilities for more specific and
more complex methods for in-depth analysis.


## Operational goals

> What specific skills (again, in terms of __action__ verbs) are necessary to develop during the training in order to achieve the overall goal above.

1. Identify the "Bayesian building blocks" (prior, likelihood, posterior, predictive) in any Bayesian analysis and interpret their meaning correctly.

1. Assess the appropriateness of the basic distributions from the exponential family for the various types of data (count, binary, continuous).

1. Summarise inferences and predictions of quantities of interest and derived
functions using random samples from posterior probability distributions.

1. Interpret the information contained in a posterior probability distribution by
visual inspection of its shape in a plot of the density or mass function.

1. Synthesise the main characteristics of three core approaches for Bayesian
computation: analytical conjugate derivations, Importance Sampling and Markov
Chain Monte Carlo.

1. Apply basic Importance Sampling and MCMC methods via available software for
fitting regression models

1. Assess the convergence quality of the Markov Chains by visual inspection 
their traces and by convergence indices like $\hat R$.

1. Summarise the landscape of available software packages, and their
characteristics.

  Specifically, whether they are flexible probabilistic programming languages
  (Bugs, Stan, Nimble, ...) or interfaces to a closed set of families of 
  statistical models, and their relative strengths and weaknesses.

1. Identify in which situations Bayesian analysis is particularly advantageous
with respect to frequentist alternatives.

  Specifically, the direct probabilistic interpretation of results, the treatment
  of the uncertainty in the model parameters (e.g. proper propagation, rather
  than marginalisation using MLEs), not relying on asymptotic theory,
  the probabilistic approach to hypothesis testing.


## Pre-requisites

- Target population: people with little to no previous knowledge of Bayesian statistics with some concrete motivation.

	E.g. master/PhD students who are going to use or work with Bayesian statistics, professionals in various fields (medicine, biology, ecology, industry, etc.) wanting to improve their quantitative skills.
