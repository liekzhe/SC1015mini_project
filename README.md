# SC1015proj

## SC1015: Mini Project - Creating the Ultimate Movie EVER, in the history of mankind

School of Computer Science and Engineering
Nanyang Technological University
Lab: Z130
Group : 1??

## Members:

1. Wong Liek Zhe (U2220416D)
2. Iain Roderick Tay Rong Yu (U2221382K)
3. Tan Jie Ning, Jolynn (U2220577B)

=============================================

## Problem Definition:
- What is the profile 

## Table of Contents:
1. Problem Formulation
2. Data Cleaning and Preperation
3. 


2. SC1015 Mini Project.ipynb
   - Cleaning and preparation
   - Exploratory data analysis
   - Machine Learning: 

============================================

## Problem Formulation
**Our Dataset:** [TMBD Movie Dataset](https://www.kaggle.com/datasets/successikuku/tmbd-movie-dataset)
**Our Question:** What factors have the greatest influence on the success of a movie?

**Success definition:** Determined by the profit and popularity of the movie

**Rationale:** To figure out what factors play a significant role in determining the success of a movie.


## 1. Data Cleaning and Preparation
In this section of the project, we prepped and cleaned the dataset to help us analyze our data better and also to help us use our data for the purposes of machine learning in the later sections.

a. We have filtered out the *factors* that we identified to have relevance to the *success* of a movie 
b. Remove null/missing values within the dataset
c. Splitting of data 
d. One-hot encoding
e. Pickle data


## 2. Exploratory Data Analysis
Exploratory data analysis (EDA) is an approach to analyzing and summarizing data sets that involves visualizing and exploring the data to gain insights and identify patterns, trends, and outliers.<br>

a. Used box plots, histograms, kde plots in visualising numeric factors: 'budget', 'runtime', 'profit', 'popularity'
b. used barplots for categorical factors: 'genres', 'production_companies', 'director', 'casts', 'release_year', 'release_month'
c. Explored correlation between the 2 success factors: 'popularity' and 'profit'


## 3. Dimension Reduction
Dimension reduction refers to the process of reducing the number of variables or features in a dataset while retaining as much relevant information as possible. The goal of dimension reduction is to simplify the dataset, make it more manageable, and reduce noise and redundancy in the data.<br>

a. Comparing dependent vairables against success factors
b. Removing noisy data to analyse data more efficiently

## 4. Numerical Insights
In this section, we will be analysing numerical factors that can influence the success of a movie and determine if it is an infuential factor <br>

Machine learning models used are:
Linear regression model <br>
Random forest classification (utilising confusion matrix)

a. Explored bi-variate relationships with a scatter plot
b. Plot a linear regression line for numerical dataset against variables of success
c. Visualising distribution through swarmplot 
d. Random forest classification
e. Optimisation through confusion matrix

## 5. Categorical Insights
In this section, we will be analysing categorical factors that can influence the success of a movie and determine if it is an infuential factor <br>

Machine learning models used are:<br>

a. Visualising the mean profit and popularity for each variable of the determining factors
b. Identifying the top 10 variables of each factor
c. Exploring correlation between the variables and the success factors


## Machine Learning
*Random Forest Classifer*
*Logistic Regression*
*Neural Network*

# Conclusion of the analytical methods
*Machine Learning Comparisons*
- 
*Data Driven Insights*
- 

# What we have learnt from this project
- interesting fact we found was that in order to create the ultimate movie of all time (based on our dataset), 
- how to justify the suitability of a model based on readings from classification report
- Logistic Regression model 
- Neural Network model


# References





    

