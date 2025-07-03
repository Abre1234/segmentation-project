# Customer Segmentation Project

This repository contains my Customer Segmentation project, developed by Abraraw Ayal, a Data Science student at Bahir Dar University. The project applies K-means clustering to segment customers for a marketing campaign using a 500-row dataset, demonstrating my skills in machine learning and data analysis.

## Project Overview
Customer segmentation is a key technique in marketing to group customers based on behavior and demographics. This project uses unsupervised learning to identify distinct customer clusters, enabling targeted marketing strategies. The dataset includes 500 records with features like age, income, spending score, and purchase frequency.

## Dataset
- **Source**: Simulated retail dataset (available in `data/customer_data.csv`).
- **Rows**: 500.
- **Columns**: 5 (Age, Income, Spending Score, Purchase Frequency, Region).
- **Description**: The dataset was cleaned to remove missing values and normalized for clustering analysis.

## Methodology
1. **Data Preprocessing**:
   - Loaded the 500-row dataset using Pandas.
   - Handled missing data with median imputation.
   - Standardized features using StandardScaler for consistent clustering.
2. **Clustering**:
   - Applied K-means clustering with 3 clusters, determined via the Elbow Method.
   - Visualized clusters using Matplotlib and Seaborn.
3. **Analysis**:
   - Interpreted clusters based on feature distributions (e.g., high-income, high-spending group).
   - Provided insights for marketing targeting.

## Tools and Technologies
- **Programming Language**: Python 3.9
- **Libraries**: 
  - Pandas (data manipulation)
  - NumPy (numerical operations)
  - Scikit-learn (K-means, preprocessing)
  - Matplotlib/Seaborn (data visualization)
- **Environment**: Jupyter Notebook
- **Version Control**: Git

## How to Run
1. Clone the repository:

  (file):[https://github.com/Abre1234/segmentation-project/blob/main/customer%20segmentation-checkpoint.ipynb]
