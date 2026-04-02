# Dimensionality Reduction using PCA and SVD

This project demonstrates important dimensionality reduction techniques and applications using Python.
The implementation includes analysis using **Principal Component Analysis (PCA)** and **Singular Value Decomposition (SVD)** for data analysis, image compression, and text processing.

These techniques are widely used in **machine learning, data compression, and natural language processing**.

---

# Project Overview

This project contains three main experiments:

1. PCA on the Wine Quality dataset
2. Image compression using SVD
3. Latent Semantic Analysis (LSA) using SVD for text classification

The goal is to understand how dimensionality reduction techniques work in practical applications.

---

# Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* Pillow (PIL)

---

# Repository Structure

softcomp_dr.ipynb – Main implementation notebook
winequality-red.csv – Dataset used for PCA analysis
SOFTCOMPUTING.jpg – Image used for SVD compression
svd_output.png – Output image after SVD reconstruction
README.md – Project documentation

---

# Task 1: Principal Component Analysis (PCA)

Principal Component Analysis is a technique used to reduce the number of features in a dataset while preserving most of the important information.

Dataset used:
Wine Quality Dataset

Steps performed in the notebook:

• Load and preprocess dataset
• Standardize the dataset
• Compute covariance matrix
• Perform eigenvalue and eigenvector decomposition
• Project data onto principal components
• Analyze explained variance
• Determine number of components required to preserve 90% variance

A **Scree Plot** is generated to visualize the variance explained by each principal component.

---

# Task 2: Image Compression using SVD

Image compression is performed using Singular Value Decomposition.

Steps:

• Convert the image into grayscale matrix
• Compute SVD of the image matrix
• Reconstruct image using fewer singular values
• Compare quality of compressed images

By reducing the number of singular values, the image can be stored using less memory while maintaining visual quality.

Example Output:

![SVD Compression Result](svd_output.png)

---

# Task 3: Latent Semantic Analysis (LSA)

Latent Semantic Analysis is implemented using truncated SVD to reduce the dimensionality of TF-IDF features in text data.

Dataset used:
20 Newsgroups Dataset

Pipeline used in the notebook:

1. Text preprocessing
2. TF-IDF feature extraction
3. Dimensionality reduction using truncated SVD
4. Logistic regression classification

Two models are compared:

• Baseline TF-IDF features
• Reduced features using LSA

Evaluation metrics:

• Accuracy
• Training time
• Feature dimensionality

Results are visualized using bar charts.

---

# Key Concepts Demonstrated

• Dimensionality Reduction
• Data Visualization
• Image Compression
• Natural Language Processing
• Feature Engineering

Core algorithms used:

Principal Component Analysis (PCA)
Singular Value Decomposition (SVD)

---

# How to Run the Project

Install required libraries:

pip install numpy pandas matplotlib seaborn scikit-learn pillow

Run the notebook:

jupyter notebook softcomp_dr.ipynb

---

# Author

Prashant Dubey


GitHub Profile:
https://github.com/Prashantdubeyfran9coo
