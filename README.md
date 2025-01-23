# clustering-dimensionality-reduction

This project provides a comparison of different clustering methods and dimensionality reduction methods to group similar words (taken from sentences) together based on their labels. 

The project uses 3 different datasets :

- Classic3 dataset : Contains 3 different topics (cisi, cran, med)
- Classic4 dataset : Contains 4 different topics (cacm, cisi, cran, med)
- BBC News dataset : Contains 5 different topics (business, entertainment, politics, sport, tech)

The goal of this project is to compare clustering algorithms (KMeans++, KMedoids, Spherical KMeans, Hierarchical Clustering) and dimensionality reduction methods (Original Dimension, PCA, t-SNE, UMAP) to assess their effectiveness in grouping words with similar labels, measured using the following metrics NMI (Normalized Mutual Information) and ARI (Adjusted Rand Index). 

This project was completed as part of the course Machine Learning for Data Science at University Paris Cité, France. Therefore the comments and analysis are written in French.

# Repository Overview
This repository contains 3 Jupyter notebooks, one for each dataset, [bbc_notebook](bbc_notebook.ipynb), [classic3_notebook](classic3_notebook.ipynb), [classic4_notebook](classic4_notebook.ipynb) and a [poster](ProjetDataScience_poster.pdf) recaping the comparaison of the different clustering and dimensionaity reduction methods.
