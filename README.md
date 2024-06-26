# Crypto Clustering Project

## Introduction
In this project, we'll utilize Python and unsupervised learning techniques to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.

## Before You Begin
Create a new repository for this project called CryptoClustering. Do not add this homework to an existing repository.

Clone the new repository to your computer.

Push your changes to GitHub.

## Files
Download the following files to help you get started:
- [Module 19 Challenge files](https://static.bc-edx.com/data/dl-1-2/m19/lms/starter/Starter_Code.zip)

## Instructions
Complete the following steps:

### Rename the Notebook
Rename the Crypto_Clustering_starter_code.ipynb file as Crypto_Clustering.ipynb.

### Load and Prepare the Data
- Load the crypto_market_data.csv into a DataFrame.
- Get the summary statistics and plot the data to see what the data looks like before proceeding.
- Use the StandardScaler() module from scikit-learn to normalize the data from the CSV file.
- Create a DataFrame with the scaled data and set the "coin_id" index from the original DataFrame as the index for the new DataFrame.

### Find the Best Value for k Using the Original Scaled DataFrame
- Use the elbow method to find the best value for k.
- Answer the question: What is the best value for k?
- Cluster Cryptocurrencies with K-means Using the Original Scaled Data.

### Optimize Clusters with Principal Component Analysis
- Perform a PCA and reduce the features to three principal components.
- Retrieve the explained variance to determine how much information can be attributed to each principal component.
- Answer the question: What is the total explained variance of the three principal components?

### Find the Best Value for k Using the PCA Data
- Use the elbow method on the PCA data to find the best value for k.
- Answer the question: What is the best value for k when using the PCA data? Does it differ from the best value for k that you found by using the original data?
- Cluster Cryptocurrencies with K-means Using the PCA Data.

### Visualize and Compare the Results
- Create a composite plot to compare the elbow curve created from the original data with the one created from the PCA data.
- Create a composite plot to compare the cryptocurrency clusters resulting from using the original data with those resulting from the PCA data.
- Answer the question: Based on visually analyzing the cluster analysis results, what’s the impact of using fewer features to cluster the data by using K-means?

### Coding Conventions and Formatting
- Follow appropriate coding conventions and formatting.
- Ensure proper placement of imports, naming conventions, DRY principles, concise logic, and creative engineering.

### Deployment and Submission
- Submit a link to a GitHub repository that’s cloned to your local machine and that contains your files.
- Use the command line to add your files to the repository.
- Include appropriate commit messages in your files.

## Grading
This project will be evaluated against the requirements and assigned a grade according to the following table:

Grade	Points
A (+/-)	90+
B (+/-)	80–89
C (+/-)	70–79
D (+/-)	60–69
F (+/-)	< 60

## Submission
To submit your Challenge assignment, click Submit, and then provide the URL of your GitHub repository for grading.

## Comments
Ensure that your code is well-commented with concise, relevant notes that other developers can understand.

## References
Data for this dataset was generated by edX Boot Camps LLC, and is intended for educational purposes only.
