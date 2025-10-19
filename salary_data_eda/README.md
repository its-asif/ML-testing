# Salary Data Exploratory Data Analysis (EDA)

This project contains a comprehensive exploratory data analysis (EDA) workflow on a salary dataset. It focuses on understanding data distributions, detecting outliers, and visualizing key insights through histograms, boxplots, and statistical measures.

## Project Overview

The goal of this notebook is to:
- Explore and clean salary data
- Understand the distribution of numeric features
- Detect and handle outliers
- Visualize relationships and trends
- Prepare the dataset for further analysis or modeling

## Features

- Automated plotting functions for histograms and boxplots  
- Outlier detection using statistical methods (e.g., Mahalanobis distance)  
- Data visualization using Seaborn and Matplotlib  
- Clean and reusable code structure

## Tech Stack

- **Programming Language:** Python  
- **Libraries Used:**
  - `pandas` for data manipulation
  - `numpy` for numerical computations
  - `matplotlib` & `seaborn` for data visualization
  - `scipy` for statistical analysis
  - `re` for regular expressions


## Key Functions

### `plot_histogram()`
- Plots a detailed histogram with KDE curve
- Customizable titles, labels, and colors

### `plot_boxplot()`
- Plots single and grouped box plots
- Supports log transformation for better visualization

### `mahalanobis()` based Outlier Detection
- Uses Mahalanobis distance to detect multivariate outliers
- Includes Chi-square thresholding


