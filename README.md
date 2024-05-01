# Electricity Production Economic Analysis (EPEA) - 1970

## Overview
This repository contains the Electricity Production Economic Analysis (EPEA) project, focused on the econometric analysis of electricity production costs in the year 1970. The goal is to understand the economic scales and cost drivers impacting electricity production during this period.

## Objectives
- To analyze the cost structures associated with electricity production.
- To identify key factors influencing these costs.
- To provide a historical perspective on the economics of electricity production.

## Methodology
The analysis employs various econometric techniques, utilizing the `Electricity1970` dataset which includes data on production costs, output levels, and other economic variables from 158 firms. We utilize linear regression models to investigate the relationships between production outputs and costs.

### Data Analysis
- **Descriptive Statistics**: Overview of the data, including measures of central tendency and dispersion.
- **Regression Analysis**: Estimation of multiple linear regression models to understand the impact of various factors like labor, capital, and fuel prices on the production costs.
- **Visualization**: Scatter plots and box plots to visually assess relationships and detect outliers.

## Results
Key findings from the analysis indicate that certain factors such as output levels and fuel costs have significant impacts on electricity production costs. Details of regression coefficients and statistical significance are provided.

## Tools and Libraries Used
- **R Programming**: Data manipulation, statistical modeling, and visualization.
- **AER Package**: Applied Econometrics with R for model fitting.
- **ggplot2**: For advanced graphical representations.
- **car Package**: Companion to Applied Regression, for diagnostics and enhancements to base R regression modeling.
- **devtools Package**: Tools to make developing R packages easier, used for package development and testing.
- **broom Package**: For converting statistical analysis objects into tidy format, making the analysis workflow more structured and accessible.
- **PoEdata Package**: Provides datasets and functions specifically designed for Principles of Econometrics.
- **leaps Package**: For regression subset selection, which helps in identifying the best set of variables for accurate modeling.
- **Boruta Package**: A feature selection algorithm based on random forests, used to identify the importance of variables.
- **lmtest Package**: Testing linear regression models, used for conducting various statistical tests.
- **sandwich Package**: Advanced statistical methods to derive robust standard errors.
