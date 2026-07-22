# PCA_Iris_Analysis_Mechine-Learning
This project applies Principal Component Analysis (PCA) to the Iris dataset using Scikit-learn. The data is standardized, reduced from 4 features to 2 principal components, and visualized with Matplotlib. Species labels are added to observe the distribution of Setosa, Versicolor, and Virginica in the reduced feature space.
# PCA Iris Analysis - Project Summary

## Project Overview

This project demonstrates **Principal Component Analysis (PCA)** using the famous Iris dataset from Scikit-learn. The objective is to reduce the original four features of the dataset into two principal components while preserving most of the information, making the data easier to visualize and analyze.

## Dataset

* Source: Scikit-learn Iris Dataset
* Total Samples: 150
* Features:

  * Sepal Length
  * Sepal Width
  * Petal Length
  * Petal Width
* Classes:

  * Setosa
  * Versicolor
  * Virginica

## Project Workflow

1. Imported the Iris dataset using Scikit-learn.
2. Converted the dataset into a Pandas DataFrame.
3. Standardized the features using `StandardScaler`.
4. Applied PCA with `n_components=2`.
5. Created a new DataFrame containing the two principal components (PC1 and PC2).
6. Visualized the transformed data using a scatter plot.
7. Added species labels to observe how the three flower classes are distributed in the PCA space.

## Results

* PCA successfully reduced the dataset from **4 dimensions to 2 dimensions**.
* The scatter plot shows how the Iris flower species are distributed in the reduced feature space.
* Setosa is clearly separated, while Versicolor and Virginica have some overlap.

## Technologies Used

* Python
* Pandas
* Scikit-learn
* Matplotlib

## Learning Outcomes

* Dataset Import
* Data Preprocessing
* Feature Scaling
* Principal Component Analysis (PCA)
* Data Visualization
* Understanding dimensionality reduction
