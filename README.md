
# Wine Quality EDA


### Project Overview

This project is my first attempt at performing Exploratory Data Analysis (EDA) on a real-world dataset.
I worked with the Wine Quality Dataset from the UCI Machine Learning Repository.

The goal of this project was to:

* Understand the structure of the dataset

* Explore feature distributions

* Identify correlations with wine quality

* Visualize patterns and potential outliers

### Repository Structure

```
Wine-EDA/
│── data/ # Raw dataset (winequality-red.csv, winequality-white.csv)
│── Outputs/ # Saved plots 
│── wine_quality_eda.ipynb # Main notebook
│── README.md # Project documentation
```

### Tools Used

* Python

* Pandas (data manipulation)

* Matplotlib and Seaborn (visualization)

* Jupyter Notebook (analysis environment)

### Key Insights

* Most wines are rated between 5 and 6, showing slight imbalance.

* Alcohol content has a positive impact on wine quality.

* Volatile acidity negatively affects quality.

* Features like residual sugar and citric acid show skewed distributions with outliers.

### Outputs

The following plots and files are saved in the outputs folder:

* Distribution of Wine Quality Ratings

* Correlation Heatmap

* Alcohol vs Quality Boxplot

* Volatile Acidity vs Quality Boxplot

### Next Steps

* Apply preprocessing and feature scaling

* Train machine learning models to predict wine quality

* Handle class imbalance (since most wines are average quality)

### About

This is my beginner project in data analysis.
The aim was to learn how to structure an EDA, generate insights and to keep the analysis organized and easy to understand.
