# NHANES Adult Health Outcomes Analysis

## Overview

This project analyzes health outcomes in the adult U.S. population using data from the National Health and Nutrition Examination Survey (NHANES). The goal of the analysis is to explore how demographic and lifestyle factors relate to important health indicators such as diabetes, blood pressure, and glycemic control.

The project focuses on identifying patterns in the data and testing statistical relationships between variables such as age, BMI, and blood pressure. The analysis also includes predictive modeling to understand which factors are most strongly associated with diabetes and HbA1c levels.

## Dataset

The dataset used in this project is derived from NHANES, a large national survey that collects health and nutrition data through interviews, medical examinations, and laboratory tests.

For this analysis:

* Adult participants aged 18 and older were selected
* The dataset includes more than 8,000 observations and multiple health-related variables
* Key variables include age, BMI, blood pressure, glucose, HbA1c, physical activity, and socioeconomic indicators

## Data Processing

Before performing the analysis, several preprocessing steps were applied:

* Filtering the dataset to include only adult participants
* Removing duplicate records
* Handling missing values and unrealistic outliers
* Creating categorical variables such as BMI category, blood pressure category, and age groups

These steps helped ensure the dataset was suitable for statistical analysis.

## Exploratory Data Analysis

Exploratory analysis was conducted to understand the structure and distribution of the data. This included:

* Histograms and distribution plots for continuous variables
* Frequency tables for categorical variables
* Correlation analysis between key health indicators
* Visualizations showing relationships between age, BMI, and blood pressure

These visualizations helped identify trends and potential relationships that were explored further using statistical tests.

## Statistical Testing

Several hypothesis tests were performed to examine relationships between variables:

* **Shapiro-Wilk tests** to evaluate normality of continuous variables
* **Chi-square tests** to examine associations between categorical variables
* **Two-sample t-tests** to compare group means
* **ANOVA tests** to compare multiple group averages
* **Proportion tests** to evaluate hypertension prevalence

These tests helped determine whether observed patterns in the data were statistically significant.

## Predictive Modeling

Two regression models were developed to explore predictive relationships:

**Logistic Regression**

* Used to predict diabetes status
* Key predictors included age, BMI, and systolic blood pressure

**Linear Regression**

* Used to predict HbA1c levels
* Examined how demographic and lifestyle variables influence glycemic control

Model diagnostics were also performed to evaluate assumptions and model quality.

## Key Insights

The analysis revealed several important relationships:

* Age, BMI, and systolic blood pressure are strong predictors of diab
