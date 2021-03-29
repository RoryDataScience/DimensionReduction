# DimensionReduction
Data Science Procedures to Reduce the dimensions of data sets
Methods to treat and deal with categorical data

## Project Title
Application of Dimension Reduction Algorithms and Treatment of Categorical Variables 

## Motivation & Project Scope
**Exploratory Data Analysis**
- Columns in train and not in test dataset
- Missing Value Analytics (msno package)
  - As we can see from the variables with missing values, it is a good idea to keep the missing values as a separate category value, instead of replacing them by the mode for instance.
- Colorama – Change the font colour in Jupyter notebook
- Assert methods to validate subsetting
 
**Categorical Data Analysis**
- Cardinality 
- Bar and Normalised Count plots
- Encoding Methods
  - One Hot 
 With one-hot encoding, the intercept term represents the global mean of the target variable, Target, and each of the linear coefficients represents how much ps_ind_02_cat on average target differs from the global mean.
  - Dummy
With dummy coding, the bias coefficient represents the mean value of the response variable target for the reference category, which in the example is ps_ind_02_cat. The coefficient for the ith feature is equal to the difference between the mean response value for the ith category and the mean of the reference category.
  -	Hash
Feature hashing is a technique that can be used to deal with categories with a large number of levels: We can clearly see how using feature hashing will benefit us computationally, sacrificing immediate user interpretability. This is an easy trade-off to accept when progressing from data exploration and visualization into a machine learning pipeline for large datasets
- Effect (Out of scope)

**Large number of categories**
- The challenge is to find a good feature representation that is memory efficient, yet produces accurate models that are fast to train
- Normalised Counts: Unbounded count categories

**Advanced Visualisations**
- The ‘boxenplot’, an expansion of the boxplot, seeks to address the problems of boxplots by adding more quantiles
- Clustered heatmaps are often used for correlation matrices (correlations between every combination of two features), but can be used for really any matrix, as long as its elements are on the same scale.

**Dimension Reduction & Evaluation Techniques**
- Missing Value Ratio
- Low Variance Filter 
- Correlation (High) Filter for Nominal and Ordinal Data inc. statistical significance 
  - PCA Linear combination of new variables which explain the largest amount of variance with associated plots
- Factor Analysis describing the covariance relationships between several variables in terms of a few underlying and unobservable random components
  - If you want to predict using the factors, use PCA, while if you want to understand the latent factors, use Factor Analysis
  - How to determine the optimal number of factors
- Correspondence Analysis for analysis of contingency tables

**Categorical Data Feature Selection**
- selectKBest and chi squared with ordinal and label encoding

## What are the types of Dimension Reduction?
- Linear Dimension Reduction (Cohort One):
  - Missing Value Ratio
  - Low Variance Filter
  - High Correlation Filter
  - PCA
  - Factor Analysis
  - Multiple Correspondence Analysis

- Linear Dimension Reduction (Cohort Two TBD):
  - BPDR
  - LDA (and applied to K-Means)
  - ICA
  - NNMF

- Other PCA Methods
  - Extended PCA
  - Incremental PCA 
  - Randomised PCA 
  - Kernal PCA
  - Probabilistic PCA
  - PCA Regression

- Non-Linear Dimension Reduction: 
  - LLE
  - t-SNE
  - UMAP
  - IsoMap
  - MDS

## Categorical Data Feature Selection
- Treatment of ordinal/nominal features
- SelectbestK
- Chiq Squared Test Statistics
- Feature Importance determination


## Build Status
Project in Development - Further Dimension Reduction Methods should be picked up from Cohort Two 

## Getting Started
Python version: 3.6.5 <br>
Notebooks: 20210215_DimensionReductionProject <br>
Branch: 20210215_DimensionReduction <br>
Last Commit: Completion of Dimension Reduction Project e5aeeae0a3c79dbd8940b06bc8247240215f2340 <br>
<br>
Additional Notes:
There is a quick methods to save requirements from the notebook by running pip3 freeze > requirements.txt once the project has been completed

### Installing
cd Documents/GitHub/DimensionReduction/ <br>
source .venv/bin/activate <br>
python -m pip install -r requirements.txt <br>

### Running the tests
Not implemented

**Break down into end to end tests** 
## Deployment
Not implemented

## Screenshots
Not implemented

## Versioning
Not implemented
