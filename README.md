# Phase 2 Project Description



## Overview

During this project, we will be investigating real estate datasets using multiple linear regression analysis. 
The customer is a real estate agency, who want to give better price recommendations to their customers. For the sake of research, we will use the following dataset (with formats): 

 - King County, WA Real Estate, CSV

 
We will employ Pandas, Statsmodel, NumPy, MatPlotLib, and SeaBorn libraries. 
 
Considering the task and dataset natures where we need to predict price against explicitly and a relatively limited number of parameters, we decided to use linear regression analysis due to its simplicity, transparency, and versatility which makes it appropriate for our task. 

## Business Problem

The customer, a real estate agency, wants to have a tool for home price prediction based on different parameters, like Living Area, Number of Bedrooms, or house conditions. 

The goals are:
- Reveal factors that influence home prices the most;
- Provide advice to homeowners on how home RENOVATION affects the price.

## Methods

For the analysis, we used OLS Linear Regression method. The following libraries have also been used. 
- Pandas 
- Statsmodel
- Matplotlib
- Scipy
- Seaborn
- Numpy


## Findings


The overall regression was statistically significant (R2 = .552, p < .000).

It was found that the Square Footage of the Living Area significantly predicted price (β = 272.5097, p < .000).
It was also found that:

- Number of bathrooms significantly predicted price (β = 1.069e+04, p < .000)
- Number of bedrooms significantly predicted price (β = -4.638e+04, p < .000).


It was found that every additional square foot increases the home price by $272.51 

It was also found that:

- Every additional bathroom increases the home price by $10,690.00  
- Every additional bedroom decreases the home price by $46,380.00 

## Business recommendations.

Based on the modeling results, we recommend our customers:

- Increasing Living Aera (by, for example, adding a second floor, our outdoor expansion);
- Adding more bathrooms;
- Decreasing the number of bedrooms.

## Further investigation:

We suggest further investigation of how features such as 'Grade' and 'View' affect home prices.



## Repository Structure

├── README.md                  <- The top-level README for reviewers of this project
├── project.ipynb              <- Narrative documentation of analysis in Jupyter notebook
├── presentation.pdf           <- PDF version of project presentation
├── data                       <- Compressed dataset
└── project.pdf                <- PDF version of the Jupyter Notebook
 
