# Customer Segmentation using Clustering

## Problem Statement

Perform customer segmentation for an Online Retail using an Unsupervised Clustering technique. 
The project aims to group customers into distinct segments based on their similarities in order to gain insights and facilitate targeted marketing strategies.

## Objectives

* extract summary level insight from a given customer dataset.

* handle the missing data and identify the underlying pattern or structure of the data.

* create an unsupervised model that generates the optimum number of segments for the customer base

* identify customer segments based on the overall buying behaviour

## Dataset

The dataset chosen for this project is the Online Retail dataset. It is a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.

The dataset contains 541909 records, and each record is made up of 8 fields.

Download the dataset : [click here](https://archive.ics.uci.edu/ml/datasets/Online+Retail)

## Project Setup
Follow the steps below to set up the project:

1. Clone the project repository or download the project files to your local machine.

2. Open it in Jupyter Notebook or in Google Colab.

3. Download the dataset from the link provided above

## Usage
1. Open the ipynb file.

2. Load the customer data into the notebook using the appropriate file reading function (e.g., pd.read_csv() in the case of a CSV file).

3. Preprocess the dataset by performing data cleaning, handling missing values, and scaling the features if necessary.

4. Implement the K-means and DBSCAN clustering algorithms using scikit-learn's KMeans and DBSCAN modules. Set the appropriate hyperparameters based on the dataset and problem requirements.

5. Fit the clustering models to the customer data and obtain the cluster labels for each customer.

6. Train a supervised algorithm on clustered data to predict clusters on unseen data.

## Troubleshooting
* Ensure that the dataset file is correctly specified and placed in the same directory as the ipynb Notebook file.

* Check for any missing libraries or dependencies and install them using the pip install command.
