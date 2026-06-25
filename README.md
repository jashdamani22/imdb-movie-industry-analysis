# IMDb Movie Industry Analysis

## Overview

This project explores a dataset of over 2,900 movies to identify factors associated with commercial and critical success. The analysis investigates how budget, audience engagement, ratings, directors and genres influence box office performance.

## Business Problem

Film studios invest substantial resources into movie production with uncertain outcomes. Understanding the drivers of movie success can help stakeholders make better decisions regarding budgeting, talent selection and marketing strategy.

## Dataset

The dataset contains information on 2,961 movies, including:

* Genre
* Director
* Release Year
* Duration
* Gross Revenue
* Budget
* Cast Facebook Likes
* Votes
* Reviews
* IMDb Rating

## Methodology

### Data Cleaning

* Checked for missing values
* Identified duplicate observations
* Removed duplicate movie records

### Exploratory Data Analysis

* Genre distribution analysis
* Return-on-budget analysis by genre
* Director performance analysis
* Rating distribution analysis
* Correlation analysis

### Visualisation

* Rating distributions by genre
* Gross revenue vs cast popularity
* Gross revenue vs production budget

## Key Findings

* Significant differences exist across genres in terms of profitability and ratings.
* Higher budgets are generally associated with higher gross revenue.
* Cast popularity alone is a weak predictor of movie revenue.
* A small number of blockbuster films heavily influence revenue distributions.
* Certain directors consistently generate stronger commercial performance.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

## Repository Structure

```text
data/          Raw dataset
notebooks/     Jupyter notebook analysis
images/        Visualisations
reports/       Project outputs
```

## Future Improvements

* Build predictive models for movie success.
* Develop interactive dashboards using Streamlit.
* Perform time-series analysis of industry trends.
* Include advanced statistical testing and feature engineering.
