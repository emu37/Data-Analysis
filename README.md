# 🌸 Iris Dataset Exploratory Data Analysis (EDA)
This repository contains a complete Exploratory Data Analysis (EDA) project on the classic Iris dataset, implemented using Python libraries such as Pandas, Seaborn, Matplotlib, and NumPy. The goal is to explore the dataset visually and statistically, identify patterns, and handle outliers to prepare it for further analysis or machine learning.

📁 Dataset
The dataset used is the popular Iris flower dataset, which consists of 150 samples from three different species of Iris flowers (Setosa, Versicolor, and Virginica), with four features:

Sepal Length (cm)

Sepal Width (cm)

Petal Length (cm)

Petal Width (cm)

🛠 Libraries Used
pandas

numpy

seaborn

matplotlib

📊 Project Features
✅ Data Loading and Overview
Load dataset using pandas

Display top rows, data types, missing values, and descriptive statistics

✅ Data Cleaning
Remove duplicate records based on species

Check for null values

Drop outliers using Interquartile Range (IQR) method

✅ Visualizations
Count Plot of flower species

Scatter plots showing sepal and petal measurements by species

Pair Plot to see all pairwise relationships between features

Histograms and Facet Grids to visualize distribution of individual features

Heatmap showing correlation between numerical features

Boxplots for each feature grouped by species

✅ Outlier Detection and Removal
Use IQR method to detect and remove outliers in SepalWidthCm

Compare shapes before and after cleaning

Replot boxplot to confirm outlier removal

📷 Sample Plots
Countplot of species distribution

Scatter plots of Sepal vs Petal dimensions

Heatmap showing feature correlations

Boxplots showing variation and outliers in features

🧠 Purpose
This EDA provides a foundational understanding of the Iris dataset, suitable for beginners in Data Science and Machine Learning. It helps build skills in:

Data cleaning and preparation

Data visualization

Feature understanding

Statistical analysis

📎 How to Run
Clone this repo:

bash
Copy
Edit
git clone https://github.com/yourusername/iris-data-analysis.git
cd iris-data-analysis
Install the required packages:

nginx
Copy
Edit
pip install pandas seaborn matplotlib numpy
Run the notebook or Python script in your favorite environment (e.g., Jupyter Notebook, VS Code).
