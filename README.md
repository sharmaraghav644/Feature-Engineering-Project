# Feature Engineering Project - EDA using Pandas, Numpy, Seaborn, and Matplotlib

## Description

In this project, we perform **Exploratory Data Analysis (EDA)** on a dataset containing various features of residential homes in Ames, Iowa, to understand the factors influencing house prices. The dataset consists of **79 explanatory variables** describing various aspects of homes such as the size, location, condition, and other architectural and environmental factors.

The goal of this project is to uncover key features that influence price negotiations during the home-buying process. Through in-depth analysis and visualization, we explore these variables to provide insights into what buyers and sellers consider when determining house prices.

## Table of Contents

1. [Description](#description)
2. [Technology Used](#technology-used)
3. [Dependencies](#dependencies)
4. [Project Insights](#project-insights)

## Technology Used

- **Pandas**: For data manipulation, cleaning, and analysis.
- **Numpy**: For numerical operations on data.
- **Seaborn**: For creating statistical graphics and visualizations.
- **Matplotlib**: For plotting and visualizing the data.
- **Jupyter Notebooks**: An interactive environment for performing the analysis.
- **Scikit-learn**: For exploring machine learning models (if applicable).

## Dependencies

- `pandas`
- `numpy`
- `seaborn`
- `matplotlib`
- `scikit-learn`
- `jupyter`

## Project Insights

### Key Findings from the EDA:

- **Top Influencing Features**: After conducting the correlation analysis, we identified key variables such as `OverallQual`, `GrLivArea`, and `GarageCars` as the strongest predictors of house prices.
- **Handling Missing Data**: We dealt with missing values and imbalances in variables such as `MasVnrType` and `BsmtQual`.
- **Visualizations**: Using heatmaps, boxplots, and scatter plots, we explored how numerical features interact with house prices and detected outliers.
- **Feature Engineering**: We created new features like `Age of House` by calculating the difference between the year of sale and the year of construction, improving the analysis's depth.

