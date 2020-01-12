# Formula 1 Racing Times

## Context
Every racer's objective is to finish their race with the fastest time. But what affects their lap times?
What can they do to improve their race times? There's no data than the looking at premier auto racing
championships.

## Problem
We want to find which variables are a significant components in circuit times. However, after examining the data, 
there is large number of factors that affect lap times. Furthermore, there seems to be high multicollinearity among
the predictors. We must find a machine learning technique that will reduce dimensionality of the dataset and
account for the correlated predictors.

## Analysis 
We use the "Formula 1 Racing Data" dataset from Kaggle which provides information for championships from 1950
to 2017. Out of all the predictors, we narrow it down to lap times, number of laps, number of pit stops, 
time spent at pit stops, constructor points and driver points. To address both issues mentioned above,
we use principle component regression to optimize the findings. We check the assumptions with correlation plots
and assert our results through other visualizations. 
