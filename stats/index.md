---
layout: single
title: "Statistics"
toc: true
---
Here is a general overview and workflow guide for statistical analysis in R programming. 

If you are unfamiliar (or need a refresher), check out the <a href="/statistics/IntrotoR.nb.html" title="Introduction to R">Introduction to R</a>.


# Specific Help Pages
## <a href="/stats/Descriptive%20Stats.nb.html" title="Descriptive Statistics in R">Descriptive Statistics</a>
Descriptive statistics are a way of *describing* the data. This includes summary statistics such as mean, median, standard deviation and standard error. Recall, standard error is simply standard deviation divided by the square root of our sample size. 

## <a href="/stats/Parametrics.nb.html" title="Parametric Tests in R">Parametric Tests</a> 
Parameterics encompass a broad range of statistical tests that operate according to a normal distribution. As such, one of the assumptions is that the data must be normal for a parametric test to be appropriate. One of these is the Student's t-test, which compares two groups based on a categorical independent variable. Linear regression is another key parametric model, determining the degree of effect that a continuous independent variable explains variation in the response. 
 

## <a href="/stats/Multisample-Hypotheses.html" title="Introduction to Multisample Hypotheses">Multisample Hypotheses</a>
Multisample hypotheses expands upon the parametric toolkit to include comparisons of more than two groups. Thus, the ANOVA (Analysis of Variance) is the main statistical model here. The ANOVA weighs between-group variation (effect) to within-group variation (error) to determine the effect of a categorical independent variable. 

## <a href="/stats/GLM's.nb.html" title="Generalized Linear Models">Generalized Linear Models</a>
Generalized linear models (GLM's) are a powerful tool that allows the application of regression to accommodate data that are better suited for other distributions. This may be because the data are simply not normally distributed, and a transformation doesn't seem appropraite; or because the data are *better described* by a different distribution. This may be the case if the data are bound by zero or are count date (Poisson distribution); bounded by 0 and 100 (beta distribution); or the response variable is binary (logistic regression). 

## <a href="/stats/Linear.Mixed.Effects.Models.nb.html" title="Linear Mixed Effects Models">Linear Mixed Effects Models</a>
Linear mixed effect models incorporate other variables that may explain variation in the response. This is in improvement upon regression to better explain as much variation as possible, including that of potentially confounding variables.

## <a href="/stats/Ranomization_Bootstrapping.nb.html" title="Randomization Tests">Randomization Tests</a>
Randomization test provide a nonparametric way to assess the likelihood of your observation. The tests rely on the assumption that the independent variable has no effect on the dependent; thus, "assignment" of the independent variable is randomized. From the random data we generate our **test statistic**. By repeating this over many iterations, we generate a null distribution of our response. By then comparing our observed statistic to the null distribution, we can generate a probability of it's likelihood. 

