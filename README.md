# Agricultural Machine Learning Projects

This repository contains hands-on machine learning projects developed in Python using simulated agricultural data. The projects demonstrate my progression in applying supervised and unsupervised machine learning techniques, evaluating model performance, visualizing results, and improving code structure.

## Project 1: Crop Yield Prediction — Linear Regression

This project uses Linear Regression to predict crop yield from two simulated agricultural features representing soil pH and moisture.

### Machine Learning Approach
- Generated a synthetic dataset with 100 farm observations
- Used two input features to predict crop yield
- Built a Linear Regression model with scikit-learn
- Created predictions and compared predicted yield with actual yield
- Visualized the relationship between agricultural features and crop yield

### Model Evaluation

A cleaner version of the model uses an 80/20 train-test split:

- 80 observations for model training
- 20 observations for testing
- Test R²: approximately 0.9836
- Mean Absolute Error: approximately 4.83 yield units

The test dataset allows the model to be evaluated on observations it did not use during training.

## Project 2: Farm Plot Segmentation — K-means Clustering

This project demonstrates unsupervised machine learning using K-means clustering.

The model analyzes 300 simulated farm plots and groups similar observations into four clusters based on two agricultural features.

### Machine Learning Approach
- Generated 300 simulated farm observations
- Applied K-means clustering using scikit-learn
- Identified four farm-plot clusters
- Calculated cluster centroids
- Visualized clusters and their centers using Matplotlib
- Used a Silhouette Score to evaluate cluster separation
- Demonstrated assigning a new farm observation to an existing cluster

## Original vs. Cleaner Implementations

The repository includes both my original implementations and cleaner versions of the projects.

The original notebooks document the learning and experimentation process. The cleaner notebooks demonstrate how the same machine-learning objectives can be implemented using a more organized and efficient workflow.

## Technologies

- Python
- Jupyter Notebook
- NumPy
- scikit-learn
- Matplotlib
- Linear Regression
- K-means Clustering
- Train/Test Split
- R² and Mean Absolute Error
- Silhouette Score

## Machine Learning Concepts Demonstrated

**Supervised Learning:** Linear Regression is used to learn the relationship between input features and a known target variable and predict a numerical outcome.

**Unsupervised Learning:** K-means clustering is used to discover groups within data without providing the model with predefined target labels.

## Repository Files

- `Farm_Yield_Linear_Regression.ipynb` — original Linear Regression project
- `RLinearregession_cleaner approach.ipynb` — cleaner Linear Regression workflow
- `Farm_Plot_KMeans_Clustering.ipynb` — original K-means clustering project
- `Farm_Plot_KMeans_Clean.ipynb` — cleaner K-means clustering workflow

## Data Note

The agricultural datasets in these notebooks are synthetically generated for machine-learning education and experimentation. Feature names such as soil pH and moisture are used to demonstrate agricultural applications and should not be interpreted as validated real-world agricultural measurements.

## Purpose

These projects are part of my continued development in AI, machine learning, technical program management, systems engineering, and practical AI applications.
