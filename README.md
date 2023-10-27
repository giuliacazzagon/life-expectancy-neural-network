# Implementing Neural Networks to predict life expectancy

The World Health Organization (WHO)’s Global Health Observatory (GHO) data repository tracks life expectancy for countries worldwide by following health status and many other related factors.

Although there have been a lot of studies undertaken in the past on factors affecting life expectancy considering demographic variables, income composition, and mortality rates, it was found that the effects of immunization and human development index were not taken into account.

This [Kaggle dataset](https://www.kaggle.com/datasets/kumarajarshi/life-expectancy-who) covers a variety of indicators for all countries from 2000 to 2015 including:
- immunization factors
- mortality factors
- economic factors
- social factors
- other health-related factors

Ideally, this data will eventually inform countries concerning which factors to change in order to improve the life expectancy of their populations. If we can predict life expectancy well given all the factors, this is a good sign that there are some important patterns in the data. Since life expectancy is expressed in years, I will use regression in my predictive model.

**Objective:** in this project I will design, train and evaluate a neural network model performing the task of regression to predict the life expectancy of countries using this dataset.
