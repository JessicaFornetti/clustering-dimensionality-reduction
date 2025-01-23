# clustering-dimensionality-reduction

This project provides a comparison of different clustering methods and dimensionality reduction methods to group similar words (taken from sentences) together based on their labels. 

The project uses 3 different datasets :

- Classic3 dataset : Contains 3 different topics (cisi, cran, med)
- Classic4 dataset : Contains 4 different topics (cacm, cisi, cran, med)
- BBC News dataset : Contains 5 different topics (business, entertainment, politics, sport, tech)

This project was completed as part of the course Machine Learning for Data Science at University Paris Cité, France. Therefore the comments and analysis are written in French.

The main steps of the project are outlined below:

- **Spark Environment Setup** 
- **Data Preparation** : Download and extraction of the data, seperation of the body and head of the message, extraction of organization and category fields
- **Descriptive Analysis Using SQL** : SQL queries to ensure there are only 2 categories, count the different number of organizations, generate descriptive statistics based on the Date feature
- **Text Transformation** : Tokenization of the documents into lists of words followed by conversion of the tokenized text into vector representations using HashingTF
- **Document Clustering Using KMeans**
- **Additional Improvements** : Use of TF-IDF and document vector normalization before KMeans clustering

# Repository Overview
This repository contains 3 Jupyter notebooks, one for each dataset, [bbc_notebook](bbc_notebook.ipynb), [classic3_notebook](classic3_notebook.ipynb), [classic4_notebook](classic4_notebook.ipynb) and a [poster](ProjetDataScience_poster.pdf) recaping the comparaison of the different clustering and dimensionaity reduction methods.
