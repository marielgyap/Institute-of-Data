# Mini Projects at the Institute of Data
Welcome to my repository featuring mini projects that I worked on during my time at the Institute of Data. This repository includes projects focusing on various aspects of data science and machine learning. Below is a brief overview of each project.

The findings for each project were presented to the class and trainers, and slides for each can be found in the presentation folder.

## Project 1 - Comprehensive Data Analysis: Crime Data, K-Means, and DBSCAN
This project is divided into three parts, each focusing on different techniques and datasets:
### Gridsearch and Multinomial Models with SF Crime Data
**Description** Explore and analyse crime data from San Francisco by applying grid search techniques to tune hyperparameters and using multinomial models for classification.
- Data set: 'sf_crime_train.csv'
- Notebook: 'Part1_Gridsearch_SF-Crime.ipynb'
### K-Means: Isotopic Composition of Plutonium Batches
**Description** Cluster plutonium batches based on their isotopic composition using the K-Means algorithm. The dataset is sourced from a public repository to demonstrate clustering techniques.
- Data set: 'pluton.csv'
- Notebook: 'Part2_kmeans_Plutonium.ipynb'
### DBSCAN: Circles
**Description** DBSCAN clustering on synthetic data generated to form clusters.
- Data generation code:
```python
from sklearn.datasets import make_circles
circles_X, circles_y = make_circles(n_samples=1000, random_state=123, noise=0.1, factor=0.2)
```
- Notebook: 'Part2_kmeans_Plutonium.ipynb'
