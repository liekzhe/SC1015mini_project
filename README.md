# SC1015proj

## SC1015: Mini Project - Determining the most influential factors on the success of a movie

School of Computer Science and Engineering<br>
Nanyang Technological University<br>
Lab: Z130<br>
Team : 1<br>

## Members:

1. Wong Liek Zhe (U2220416D)
2. Iain Roderick Tay Rong Yu (U2221382K)
3. Tan Jie Ning, Jolynn (U2220577B)

---


## Table of Contents:
1. Problem Formulation<br>
2. Data Cleaning and Preperation<br>
3. Exploratory Data Analysis<br>
4. Dimension Reduction<br>
5. Numerical Insights<br>
6. Categorical Insights<br>


---

## Problem Formulation
**Our Dataset:** [TMBD Movie Dataset](https://www.kaggle.com/datasets/successikuku/tmbd-movie-dataset)<br>
**Our Question:** What factors have the greatest influence on the success of a movie?<br>

**Success definition:** Determined by the profit and popularity of the movie<br>

**Rationale:** To figure out what factors play a significant role in determining the success of a movie.<br>


## <a href="https://github.com/liekzhe/SC1015proj/blob/main/1:%20data_prep.ipynb">1. Data Cleaning and Preparation</a>
In this section of the project, we prepped and cleaned the dataset to help us analyze our data better and also to help us use our data for the purposes of machine learning in the later sections.<br>

a. We have filtered out the *factors* that we identified to have relevance to the *success* of a movie <br>
b. Remove null/missing values within the dataset<br>
c. Splitting of data <br>
d. One-hot encoding<br>
e. Pickle data<br>


## <a href="https://github.com/liekzhe/SC1015proj/blob/main/2.%20EDA.ipynb">2. Exploratory Data Analysis</a>
Exploratory data analysis (EDA) is an approach to analyzing and summarizing data sets that involves visualizing and exploring the data to gain insights and identify patterns, trends, and outliers.<br>

a. Used box plots, histograms, kde plots in visualising numeric factors: 'budget', 'runtime', 'profit', 'popularity'<br>
b. used barplots for categorical factors: 'genres', 'production_companies', 'director', 'casts', 'release_year', 'release_month'<br>
c. Explored correlation between the 2 success factors: 'popularity' and 'profit'<br>


## 3. Dimension Reduction
Dimension reduction refers to the process of reducing the number of variables or features in a dataset while retaining as much relevant information as possible. The goal of dimension reduction is to simplify the dataset, make it more manageable, and reduce noise and redundancy in the data.<br>

a. Comparing dependent vairables against success factors<br>
b. Removing noisy data to analyse data more efficiently<br>

## 4. Numerical Insights
In this section, we will be analysing numerical factors that can influence the success of a movie and determine if it is an infuential factor <br>

Machine learning models used are:<br>
Linear regression model <br>
Random forest classification (utilising confusion matrix)<br>

a. Explored bi-variate relationships with a scatter plot <br>
b. Plot a linear regression line for numerical dataset against variables of success <br>
c. Visualising distribution through swarmplot <br>
d. Random forest classification <br>
e. Optimisation through confusion matrix <br>

## 5. Categorical Insights
In this section, we will be analysing categorical factors that can influence the success of a movie and determine if it is an infuential factor <br>

Machine learning models used are:<br>

a. Visualising the mean profit and popularity for each variable of the determining factors<br>
b. Identifying the top 10 variables of each factor<br>
c. Exploring correlation between the variables and the success factors<br>


## Machine Learning
*Decision tree*<br>
*Linear Regression*<br>


# What we have learnt from this project
- How to justify the suitability of a model based on readings from classification report
- Using newly learnt data processing methods such as one-hot ecoding, pickling of files and pivot table.
- Factors that have greater influence on the success of the movie are budget and genre
- Factors that do not really influence success of movie are runtime, release_year and release_month
- Interesting fact we found was that in order to create the ultimate movie of all time (based on our dataset)...
- Most profitable movie: Rupert Grint(cast), Lucasfilm(production company), Joss Whedon(director), Fantasy(genre), 92.5mill USD - 99.5mill USD or 164.0 USD - 172.5mill USD(budget)
- Most popular movie: Chris Pratt(cast), Syncopy(production company), George Miller(director), Science Fiction(genre), 270.0mill USD - 362.5mill USD or 102.5mill USD - 252.5mill USD(budget)



# References
- https://www.geeksforgeeks.org/ml-one-hot-encoding-of-datasets-in-python/
- https://www.datacamp.com/tutorial/pickle-python-tutorial
- https://www.datacamp.com/tutorial/understanding-logistic-regression-python 
- https://stackoverflow.com/questions/55229301/one-hot-encoding-multiple-columns-in-sklearn-and-naming-columns 
- https://dzone.com/articles/correlation-between-categorical-and-continuous-var-1 





    

