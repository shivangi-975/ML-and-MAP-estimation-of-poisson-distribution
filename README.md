# ML-and-MAP-estimation-of-poisson-distribution



Poisson distribution has been introduced to model deaths of soldiers in Prussian army from 1875 to 1894 across corps. Please find the data below.

Model the horse kick deaths using the Poisson distribution with different parameters for each of the corps. Learn Poisson distribution parameters for each of the corps using first 13 years of data and make predictions on remaining 7 years and compute the RMSE of predictions for each of the corps.
1. Use maximum likelihood estimation to learn the parameters.
2. Use maximum aposteriori estimation to learn the parameters
a. Assume appropriate prior distribution over parameters and justify your assumption
b. Plot prior, likelihood and posterior and provide your observations in terms of mode of the distributions for corps 2, 4 and 6.



Project Setup:
Estimation_Horsekicks Jupyter notebook is attached and hence it must be downloaded by the user to
run the project.

Problem Statement:
Deaths by horse kicks for each corps has to be modeled using the Poisson distribution .

Description:
Modeled the horse kick deaths using the Poisson distribution . Poisson distribution parameters for each
of the corps were learned using Maximum likelihood estimation and Maximum aposteriori estimation
using first 13 years of data and predictions were made on remaining 7 years .

In question deaths from horse kicks followed a random pattern. The Maximum Likelihood Estimate of
Poisson was calculated using mean of observations. The results for the same is shown in table .
In MAP calculation Since the number of deaths are positive and have skewed distributions, the
gamma distribution was used as a prior. Values of alpha and beta were determined based on data
analysis.
Prior, likelihood and posterior graphs were plotted and observations in terms of mode
of the distributions for corps 2, 4 and 6 were carried out.

Coding Language:
Python is used as a programming language.

Libraries used:
Pandas, Numpy ,Seaborn ,Matplotlib , scipy are used.

Live code, visualizations and narrative text:
Jupyter notebook is used for live coding and for proper visualizations with the help of graphs.

