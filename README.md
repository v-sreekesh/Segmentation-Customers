# Customer Segmentation

Use Machine Learning to create a model that performs Customer Segmentation

# Author

Sreekesh V

 Created on 17th August, 2021

## Acknowledgements

 - [Mall Customer Segmentation Data](https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial-in-python)
 
## Libraries Used
- Numpy
- Pandas
- Matplotlib
- Seaborn
- Scikit learn

## Project Pipeline

- Business Understanding
- Analytical Approach
- Data requirements
- Data collection
- Data Understanding
- Data Preparation
- Modeling

## Business Understanding

The goal of this project is to divide customers into groups based on common characteristics in order to maximize the value of each customer to the business.


## Analytical Approach 

Clustering of Customers based on similar characteristics is an Unsupervised Learning as for each observation we do not have any target variable. 

For this project, I will use two Machine Learning models
- KMeans Clustering 
- Hierarchical clustering


## 3,4. Data Requirements and Data Collection

We would require a dataset that gives us information regarding customers from a market. 

For this project, the dataset has been provided to us on Kaggle. [Mall Customer Segmentation Data](https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial-in-python)


## 5. Data Understanding

- There is a total of 200 observations with each having 5 variables.
- The column of the dataset includes CustomerID, Gender, Age, Annual Income, Spending Score.
- There are no missing values 😀
- There is one categorical variable - Gender
{{ img:d1e5fd }}


## 6. Feature Engineering

- Dropped CustomerID (not useful as it is unique for each customer) 
- Created Dummy Variable for Gender 

## 7. Modelling

K Means Clustering
- First, we determine the optimal number of clusters
- Then we determine starting values for each cluster

## Hierarchical clustering

The endpoint is a set of clusters, where each cluster is distinct from the other cluster, and the objects within each cluster are broadly similar to each other.