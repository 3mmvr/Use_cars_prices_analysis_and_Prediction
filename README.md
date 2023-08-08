# Data Science Project: Predicting Car Prices

## Introduction

In this data science project, we focus on predicting car prices based on a dataset of various automotive attributes. We follow a systematic process of data preprocessing, exploration, feature engineering, and model development to achieve accurate predictions.

## Purpose

The purpose of this project is to showcase the end-to-end data science workflow, including data cleaning, visualization, feature transformation, and model evaluation. By addressing missing values, converting categorical variables, and applying machine learning techniques, we create a predictive model for car prices.

## Project Structure

The project is structured as follows:

1. **Importing Libraries and Data**: We begin by importing essential Python libraries and reading the dataset from a CSV file.

2. **Data Cleaning and Exploration**:
   - We remove the "Unnamed: 0" column, which appears to be redundant.
   - Analyzing the dataset's statistical summary to understand missing values and distributions.
   - Replacing missing values denoted by "?" with appropriate NaN values.
   - Dealing with missing attributes: Normalizing numeric columns with their mean values and addressing categorical "num-of-doors" values.

3. **Data Transformation**:
   - Data normalization: Converting "city-mpg" and "highway-mpg" to "city-L/100km" and "highway-L/100km".
   - One-Hot Encoding: Converting categorical variables into numerical format.
   - Binning: Categorizing "horsepower" values into low, medium, and high ranges.

4. **Correlation Analysis**:
   - Creating a correlation matrix heatmap to understand relationships between variables and the target ("price").

5. **Model Development**:
   - Preparing data for modeling by splitting it into training and testing sets.
   - Utilizing Linear Regression to build a predictive model.
   - Visualizing regression graphs for selected independent variables.

6. **Results and Conclusion**:
   - Evaluating the model's performance using R2 score.
   - Summarizing the model's accuracy for each independent variable.

## Usage

To replicate or explore this project, follow these steps:

1. Install the necessary libraries specified in the "Import the needed libraries and Packages" section.
2. Download the dataset (DataSet.csv) and place it in the project directory.
3. Execute the provided Python code sections sequentially to preprocess, transform, and model the data.
4. Observe the regression graphs and R2 scores to assess the model's accuracy.

## Conclusion

This project demonstrates the complete lifecycle of a data science project, from data preprocessing and transformation to model development and evaluation. By accurately predicting car prices, we illustrate the potential application of machine learning techniques in the automotive industry.
