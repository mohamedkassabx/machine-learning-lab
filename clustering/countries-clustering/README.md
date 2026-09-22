# Countries Clustering

A small practical Unsupervised Learning project that uses K-Means Clustering to group countries based on economic, health, and demographic indicators.

## Project Overview

The goal of this project is to group countries with similar characteristics without using a predefined target variable.

The project uses K-Means Clustering to identify groups of countries based on features such as income, GDP per capita, life expectancy, child mortality, inflation, and fertility rate.

## Workflow

The project follows a basic clustering workflow:

1. Load the dataset
2. Explore and understand the data
3. Select the numerical features
4. Preprocess and scale the features
5. Use the Elbow Method to evaluate different values of K
6. Use Silhouette Score as an additional evaluation method
7. Select the number of clusters
8. Train the K-Means model
9. Analyze the resulting clusters

## Dataset

The project uses the [Unsupervised Learning on Country Data](https://www.kaggle.com/datasets/rohan0301/unsupervised-learning-on-country-data) from Kaggle.

The dataset contains information about 167 countries and includes economic, health, and demographic indicators.

The `country` column is kept as an identifier for interpreting the resulting clusters and is not used as a clustering feature.

## Features

The clustering is based on numerical features including:

* Child Mortality
* Exports
* Health
* Imports
* Income
* Inflation
* Life Expectancy
* Total Fertility
* GDP per Capita

## Preprocessing

The preprocessing includes:

* Separating the country identifier from the numerical features
* Standardizing the numerical features using `StandardScaler`

Feature scaling is important for K-Means because the algorithm relies on distances between data points.

## Choosing the Number of Clusters

Two methods are used to evaluate different values of K:

### Elbow Method

The Elbow Method is used to examine how the model's inertia changes as the number of clusters increases.

### Silhouette Score

Silhouette Score is used as an additional measure of how well-separated the clusters are.

The final number of clusters is selected based on the results of these evaluation methods.

## K-Means Clustering

K-Means is used to group countries into clusters with similar characteristics.

Each country receives a cluster label that can be used to analyze the characteristics of the resulting groups.

## Cluster Analysis

The resulting clusters are analyzed based on the economic, health, and demographic characteristics of the countries assigned to each cluster.

This helps identify the main differences between the groups.

## Results

The project demonstrates how K-Means can be used to discover groups of countries with similar characteristics using unsupervised learning.

The clusters are evaluated using the Elbow Method and Silhouette Score, then analyzed to understand the characteristics of each group.

## Tech Stack

* Python
* Pandas
* Scikit-learn
* Matplotlib
* Jupyter Notebook

## Purpose

The goal of this project is to practice Unsupervised Learning and understand the practical workflow of K-Means Clustering, from preprocessing and feature scaling to cluster selection and interpretation.

This project is part of my **Machine Learning Lab**, which contains small practical projects built while learning and applying Machine Learning concepts.

Larger and more complete projects are maintained in separate repositories.
