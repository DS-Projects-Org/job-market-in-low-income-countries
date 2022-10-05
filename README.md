# Analysis of Job market in low income countries

The focus is to obtain some specific data on skill migration among low income
countries, and to predict the skill migration trends in each country for 2020

- list of countries classified as low income by the world bank
- which skill group category had positive migration in 2019
- which industry and country had the most positive migration in 2019
- list of countries with positive skill migration in 2019
- skill migration in countries with more the 1k per 10k in 2019 vs 2015
- predict skill migration per 10k for 2020
- which country will have the most skill migration in skills that had positive
  migration in 2019 for 2020

## Data

the used dataset is LinkedIn's Digital data, and can be found on
[kaggle](https://www.kaggle.com/datasets/salehahmedrony/linkedin-digital-data)

## Model

For forecasting skill migration, a simple model based on Holt's Exponential
Smoothing is used.
