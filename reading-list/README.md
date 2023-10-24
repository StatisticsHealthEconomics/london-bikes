# Selected reading material for the project

The analysis of the dataset is mainly focused on *Generalised linear models*. These are regression models that can be used when the outcome variable can**not** be safely assumed to be generated from a process described by a Normal distribution. Instead, relevant cases are when the data are binary (modelled using a Binomial or Bernoulli distribution) or counts (modelled using a Poisson distribution).

Here are some relevant supporting material that you can have a look at

## Bayesian GLM and Bayesian modelling in general

- [Chapter 12 of *Bayes Rule*](https://www.bayesrulesbook.com/chapter-12). This is a very good book on Bayesian modelling and it's useful in general. This chapter is specifically about Poisson regression. 
- [Chapter 13 of *An Introduction to Bayesian Reasoning and Methods*](https://bookdown.org/kevin_davisross/bayesian-reasoning-and-methods/poisson.html). This is also a relevant book guiding you through the basics of Bayesian analysis and specifically looking at Poisson regression.
- [Bayesian inference with INLA](https://becarioprecario.bitbucket.io/inla-gitbook/index.html). This is a very good book on the basics of Bayesian modelling, but using "Integrated Nested Laplace Approximation" for computation. It may be a bit technical, but useful, particularly when dealing with larger datasets.

## GLM 

- [Chapter 8 of *Data analysis in `R`*](https://bookdown.org/steve_midway/DAR/glms-generalized-linear-models.html). A good book on modelling using `R`, mainly using frequentist procedures. This can be helpful to understand how to manipulate the data and using `R` to prepare and analyse them.

## General stats

- [*Introduction to statistical concepts*](https://gianluca.statistica.it/teaching/intro-stats/). A basic description of fundamental statistical concepts (from both Bayesian and frequentist perspective). Chapter 5 does contain some brief introduction to regression analysis and GLMs.
