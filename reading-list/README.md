# Selected reading material for the project

The analysis of the dataset is mainly focused on *Generalised linear models*. These are regression models that can be used when the outcome variable can**not** be safely assumed to be generated from a process described by a Normal distribution. Instead, relevant cases are when the data are binary (modelled using a Binomial or Bernoulli distribution) or counts (modelled using a Poisson distribution).

Here are some relevant supporting material that you can have a look at

## Bayesian GLM and Bayesian modelling in general

- [Chapter 12 of *Bayes Rule*](https://www.bayesrulesbook.com/chapter-12). This is a very good book on Bayesian modelling and it's useful in general. This chapter is specifically about Poisson regression. 
- [Chapter 13 of *An Introduction to Bayesian Reasoning and Methods*](https://bookdown.org/kevin_davisross/bayesian-reasoning-and-methods/poisson.html). This is also a relevant book guiding you through the basics of Bayesian analysis and specifically looking at Poisson regression.
- [Bayesian inference with INLA](https://becarioprecario.bitbucket.io/inla-gitbook/index.html). This is a very good book on the basics of Bayesian modelling, but using "Integrated Nested Laplace Approximation" for computation. It may be a bit technical, but useful, particularly when dealing with larger datasets.

## GLM 

- [Chapter 8 of *Data analysis in `R`*](https://bookdown.org/steve_midway/DAR/glms-generalized-linear-models.html). A good book on modelling using `R`, mainly using frequentist procedures. This can be helpful to understand how to manipulate the data and using `R` to prepare and analyse them.
- [*Tutorial on Poisson regression*](https://www.dataquest.io/blog/tutorial-poisson-regression-in-r/). This is a relatively simple tutorial on running Poisson regressions in `R`. It may be helpful to go through it...

## General stats

- [*Introduction to statistical concepts*](https://gianluca.statistica.it/teaching/intro-stats/). A basic description of fundamental statistical concepts (from both Bayesian and frequentist perspective). Chapter 5 does contain some brief introduction to regression analysis and GLMs.

## `R` programming

`R` is the statistical language used for the project. There are a number of useful packages that you can use to pre- and post-process the data (e.g. to create new variables from existing ones).

- [*tidyverse*](https://www.tidyverse.org/). This is a collection of R packages designed for data science (including data manipulation via [dplyr](https://dplyr.tidyverse.org/) and graphing via [ggplot2](https://ggplot2.tidyverse.org/)). None of these are essential and you could do the analysis using mostly `base` `R` (which is the standard and default implementation of the programme), but the `tidyverse` is more modern and in many cases more efficient, so it is good to familiarise with it.

- [*lubridate*](https://lubridate.tidyverse.org/). This is a very good package to deal with time and dates, in `R`. It can be used to extract information from variables formatted as dates (for example, extracting the day of the week from a given date, or isolating the year of a given date). These are helpful to generate new variables from a single field including the full date and time at which an event happens (in this case, the date and time at which bike rentals have been observed/counted).

- [*quarto*](https://quarto.org/). This is a very powerful add-on to `R` and [`Rstudio`](https://posit.co/download/rstudio-desktop/), which can be used to integrate your write-up with your code. `quarto` allows you to create a single file (typically with extension `.qmd`) in which you have parts that are in plain English (e.g. you can typeset your thesis by explaining all the modelling, using equations etc) and then include "chunks" of code, which are executed everytime that the document is compiled. The result is a dynamic output (in either `pdf`, `docx` or `html`), which allows you to run a single version of your report/dissertation --- every time you change the data/code/analysis, everything will be automatically updated. You don't have to save graphs and tables separately --- you can use the output from your `R` analysis directly into the report, which is very helpful for your dissertation.

## `R` books

- [*R for data science*](https://r4ds.had.co.nz/). This is very good and contains a lot of information on how to manipulate data in `R`.
- [*ggplot2: Elegant Graphics for Data Analysis (3e)*](https://ggplot2-book.org/). This is the definitive book for `ggplot2`, to make nice plots using the "grammar of graphics", an advanced and layered system to intergrate data and graphs. You don't **have to** use `ggplot2` and can make all your graphs using `base` `R`, but you can also take the opportunity to learn this...

