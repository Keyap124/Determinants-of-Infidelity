# Determinants of Infidelity

## Overview

**Determinants of Infidelity** is an econometrics project designed to analyze the factors that influence the likelihood of infidelity within marriages. The project uses the Affairs dataset to examine how marital satisfaction, age, years married, children, religiosity, and education relate to whether an individual reports having an affair.

The main research question behind this project is: **What factors influence the likelihood of having an affair, with a focus on marital satisfaction?**

Using R, the dataset was cleaned and prepared for analysis by renaming variables, converting the affair outcome into a binary variable, and organizing the data for regression modeling and visualization. Since the dependent variable is binary, a logit model was used to estimate how different factors influence the probability of infidelity.

The project also includes visualizations created with `ggplot2` to make the results easier to interpret. These charts show the relationship between infidelity rates and marital satisfaction, years married, religiosity, and average marginal effects from the logit model.

The analysis revealed that marital satisfaction is one of the strongest predictors of infidelity. Higher marital satisfaction ratings were associated with a lower probability of having an affair. Religiosity also showed a negative relationship with infidelity, while years married showed a positive relationship in the model.

## File Name | Purpose

| File Name | Purpose |
|---|---|
| `Final Report.pdf` | Final written econometrics report explaining the research question, dataset, methodology, results, discussion, and conclusion |
| `Visuals for Determinants of Infidelity.pdf` | PDF version of the R Markdown/HTML output containing the code and generated visualizations |
| `Visuals for Determinants of Infidelity.html` | HTML version of the R Markdown output with the code and charts |
| `affairs (2).xls` | Original Affairs dataset used for the econometric analysis |
| `affairs_description (4).txt` | Description file explaining the dataset variables |


## Features

* Econometric analysis using the Affairs dataset
* Binary dependent variable creation for infidelity outcome
* Logit regression model
* Average marginal effects interpretation
* Data cleaning and variable renaming in R
* Visualization of infidelity rates by key variables
* Marital satisfaction analysis
* Religiosity and years married comparison
* Model interpretation using coefficient signs and marginal effects
* Discussion of limitations such as omitted variable bias and cross-sectional data

## Technologies Used

* R
* R Markdown
* readxl
* dplyr
* ggplot2
* Econometric Modeling
* Logit Regression
* Data Visualization
* Microsoft Excel

## Dataset Information

The project uses the **Affairs dataset**, which contains 601 observations related to individual relationship behavior, marital satisfaction, and demographic characteristics.

The dataset includes variables such as:

* Affair status
* Number of affairs
* Age
* Years married
* Presence of children
* Religiosity
* Education
* Occupation
* Marital satisfaction rating

The main dependent variable is `affair`, which was converted into a binary variable:

* `0` = no affair
* `1` = had an affair

The main independent variable of interest is `ratemarr`, which represents marital satisfaction on a scale from 1 to 5.

## Methodology

A logit model was used because the dependent variable is binary. The model estimates the probability that an individual had an affair based on marital satisfaction and several control variables.

The model includes:

* Age
* Years married
* Kids
* Religiosity
* Education
* Marital satisfaction categories

Marital satisfaction was treated as a categorical variable instead of a continuous variable. This allowed the model to compare different satisfaction levels more flexibly rather than assuming each rating level has the same linear effect.

The project also calculates and visualizes average marginal effects to better explain how each variable changes the predicted likelihood of infidelity.

## Visualizations

The project includes several charts to support the analysis

## Key Findings

The analysis found that marital satisfaction is a major predictor of infidelity. Individuals with higher marital satisfaction ratings were less likely to report having an affair.

The results also showed that religiosity had a negative relationship with infidelity, meaning individuals with higher religiosity levels were less likely to report an affair. Years married had a positive relationship with infidelity, suggesting that longer marriages were associated with a higher probability of infidelity in this model.

The average marginal effects showed that higher marital satisfaction categories had the strongest negative effects on the probability of having an affair, especially the highest satisfaction rating.

## Goal

The goal of this project is to better understand what factors are associated with infidelity and how marital satisfaction plays a role in relationship stability. By combining econometric modeling, data cleaning, and visualization, this project highlights how individual and relationship characteristics can be analyzed using applied econometric methods.
