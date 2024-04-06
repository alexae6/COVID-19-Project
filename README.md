# COVID-19-Project
Final Project for Machine Learning Course
Vanderbilt University 2023

Using publically available COVID-19 cell data, we aimed to identify cell populations that could predict/indicate a COVID-19 infection. Two different types of dimensionality reduction were used- PCA and tSNE- and k-means clustering on clusters of sizes 2 through 60 were completed on both reduced spaces. The stability of the clustering was measured based on the rate of change between two clustering patterns. For both dimensionality reduction techniques, 50 clusters was the optimal amount. Using SVM to classify cells as either being from a healthy or infected person, it was found that PCA predicts COVID-19 patients with 98% accuracy and tSNE with 86% accuracy.

To view plots and code outputs for either technique: 
