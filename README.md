
<!-- README.md is generated from README.Rmd. Please edit that file -->

# SIR-SMR

<!-- badges: start -->
<!-- badges: end -->

    rm(list=ls())
    library(kableExtra)
    library(magrittr)
    library(dplyr)
    library(tidyverse)
    library(popEpi)
    library(DiagrammeR)
    library(biostat3)
    library(Epi)

# Overview

Standardized Incidence Ratio (SIR) or Standardized Mortality Ratio (SMR)
are common measures of event occurrence in epidemiology. They are used
to compare the occurrence of an event in a cohort to that observed in a
given population called reference population.

SIR and SMR help the investigator to have a global idea on the
occurrence of the event of interest in the followed population (the
cohort).

They are an indirect method of adjustment for a confounding factors
(age, sex, calendar year etc.) that describes in numerical terms how the
cohort average experience of the event during the follow-up compared
with that of the reference population as a whole.

In this post I will show three ways to estimate a SIR / SMR by indirect
standardization from your cohort using R.
