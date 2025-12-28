PCA From Scratch (Python)

This repository contains a manual implementation of Principal Component Analysis (PCA) using Python and NumPy, without relying on machine learning libraries such as scikit-learn.

The goal of this project is to build a strong conceptual understanding of PCA by implementing each step from first principles:

Mean centering (data standardization)

Covariance matrix computation

Eigenvalue and eigenvector calculation

Sorting principal components by explained variance

Dimensionality reduction and data projection

Visualizing original vs reduced data

This project is intended for beginners and students of Machine Learning and Data Science who want to understand the mathematics and intuition behind PCA, rather than treating it as a black-box algorithm.

Technologies Used

Python

NumPy

Matplotlib

Learning Outcomes

Clear understanding of variance and covariance

Intuition behind eigenvalues and eigenvectors

Hands-on experience with dimensionality reduction

Visual interpretation of PCA results

If you want, I can also:

Write a README.md introduction

Add usage instructions

Create a project structure

Write a commit message

Just tell me.

read me

Below is a complete, clean README.md you can directly copy and paste into your GitHub repository.
It is written in simple, professional language and suitable for beginners, reviewers, and recruiters.

PCA From Scratch (Python)

This repository demonstrates a manual implementation of Principal Component Analysis (PCA) using Python and NumPy, without relying on machine learning libraries such as scikit-learn.

The purpose of this project is to understand how PCA works internally, both mathematically and intuitively, rather than using it as a black-box algorithm.

📌 What is PCA?

Principal Component Analysis (PCA) is a dimensionality reduction technique used to:

Reduce the number of features in a dataset

Preserve as much variance (information) as possible

Remove redundancy and noise

PCA achieves this by rotating the feature space and projecting the data onto the direction of maximum variance.

🔍 What This Project Covers

This implementation walks through PCA step by step:

Creating a sample 2D dataset

Mean centering the data

Computing the covariance matrix

Calculating eigenvalues and eigenvectors

Sorting principal components by explained variance

Selecting the top principal component

Projecting data from 2D to 1D

Visualizing original vs reduced data

All steps are implemented manually using NumPy.

🧠 Key Learning Outcomes

Clear understanding of variance and covariance

Intuition behind eigenvalues and eigenvectors

How PCA rotates axes instead of moving data

Why the principal component becomes the new axis

How dimensionality reduction works mathematically

🛠️ Technologies Used

Python

NumPy

Matplotlib

📊 Output Visualization

Original 2D data scatter plot

PCA-reduced 1D projection plot

Visual interpretation of principal axes and projections
