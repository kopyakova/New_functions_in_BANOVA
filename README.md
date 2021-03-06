New_functions_in_BANOVA is a repository, which showcases the new functions developed in my master's thesis: "Mediation and Moderation Analyses with the BANOVA R-package and Everything You Need to Know to Do it Right". 

BANOVA is an R-package for Bayesian Analysis of Variance originally developed for experiments in the social sciences. It allows its users to analyze dependent variables with a wide range of distributions, such as Normal, T, Bernoulli, Binomial, Poisson, ordered Multinomial, and Multinomial. During my thesis, I have extended this list further with Multivariate and Truncated Normal distributions. The main contribution of my thesis was the development of two new functions relevant in the domains of mediation and moderation analyses. The first function is called BANOVA.simple, and it is designed to calculation conditional (simple) effects of factors and their interactions, which are moderated by a categorical variable. The second function is called BANOVA.multi.mediation, and it calculates mediated effects of a causal variable transmitted through multiple possibly correlated (parallel) mediators. Each folder in this repository includes the R code of the new function and corresponding files with documentation. 

Note that these functions are only for display purposes. To see them in action the whole package should be installed from CRAN* in a usual manner. Furthermore, the whole package can be found here: https://github.com/BANOVAapp/BANOVA_R.

*Currently CRAN submission team is on a holiday and the package will be available after the 4th of January.

