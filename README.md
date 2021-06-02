
# Introduction to the Bayesian framewrk for biometrics

<!-- badges: start -->
<!-- badges: end -->

Welcome to the 2021 PhD training course from the *Digital Public Health* programm at the University of Bordeaux.

## Slide decks

 1. slide deck #1: [Bayesian theory](slidesIntroBayesBiom_theory.pdf)
 2. slide deck #2: [Bayesian computations](slidesIntroBayesBiom_mcmc.pdf)

## Practicals
 - Exercise 1: [Monte-Carlo](piMCestimate.Rmd) -- [solutions](piMCestimate_sol.Rmd)
 - Exercise 2: [Inverse transform](inverseTransfo.Rmd) -- [solutions](inverseTransfo_sol.Rmd)
 - Exercise 3: [Metropolis-Hastings algorithm](MH.Rmd) -- [solutions](MH_sol.Rmd)
 - Exercise 4: [BUGS & JAGS](JAGSstart.Rmd) -- [solutions](JAGSstart_sol.Rmd)
 - Exercise 5: [Post-mortem analysis of an under-powered randomized trial](RRestim.Rmd)
 and [Goligher article](Goligher2018JAMA.pdf) -- [solutions](RRestim_sol.Rmd)
 
## Lecture notes

[here](IntroBayesBiom_lectureNotes.pdf)
 
## Technical requirements

 1. have an up-to-date working installation of `R`:
    - latest version of `R` (≥ 4.0) 👉 https://cran.r-project.org/
    - latest version of RStudio (≥ 1.4) 👉 https://www.rstudio.com/products/rstudio/download/#download
 2. have JAGS software installed and linked to `R`:
    - install the JAGS software from here 👉 https://sourceforge.net/projects/mcmc-jags/files/
    - install the `rjags` package in `R`
    - make sure it works: the command `library(rjags)` should give the following output:  
		`## Loading required package: coda`  
		`## Linked to JAGS 4.3.0`  
		`## Loaded modules: basemod,bugs`  
 3. have the following R packages installed: `coda`, `jagsUI`, `MCMCvis`

## Pre-requisites

 - Maximum Likelihood estimation
 - R functional programming

 
 
