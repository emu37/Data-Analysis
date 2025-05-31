# 🌸 Iris Dataset Exploratory Data Analysis (EDA)
This repository contains a complete Exploratory Data Analysis (EDA) project on the classic Iris dataset, implemented using Python libraries such as Pandas, Seaborn, Matplotlib, and NumPy. The goal is to explore the dataset visually and statistically, identify patterns, and handle outliers to prepare it for further analysis or machine learning.

#Dataset
The dataset used is the popular Iris flower dataset, which consists of 150 samples from three different species of Iris flowers (Setosa, Versicolor, and Virginica), with four features:

Sepal Length (cm)

Sepal Width (cm)

Petal Length (cm)

Petal Width (cm)

## Libraries Used
pandas

numpy

seaborn

matplotlib

#Project Features
✅ Data Loading and Overview
1.Load dataset using pandas
2.Display top rows, data types, missing values, and descriptive statistics

✅ Data Cleaning
1.Remove duplicate records based on species
2.Check for null values
3.Drop outliers using Interquartile Range (IQR) method
✅ Visualizations
1.Count Plot of flower species
2.Scatter plots showing sepal and petal measurements by species
3.Pair Plot to see all pairwise relationships between features
4.Histograms and Facet Grids to visualize distribution of individual features
5.Heatmap showing correlation between numerical features
6.Boxplots for each feature grouped by species
✅ Outlier Detection and Removal
1.Use IQR method to detect and remove outliers in SepalWidthCm
2.Compare shapes before and after cleaning
3.Replot boxplot to confirm outlier removal
## Sample Plots
1.Countplot of species distribution
2.Scatter plots of Sepal vs Petal dimensions
3.Heatmap showing feature correlations
4.Boxplots showing variation and outliers in features
###Purpose
1.This EDA provides a foundational understanding of the Iris dataset, suitable for beginners in Data Science and Machine Learning. It helps build skills in:
2.Data cleaning and preparation
3.Data visualization
4.Feature understanding
5.Statistical analysis

