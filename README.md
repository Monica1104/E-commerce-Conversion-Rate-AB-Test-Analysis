# E-commerce-Conversion-Rate-AB-Test-Analysis

## Overview
This project is to analyze A/B Testing data for an e-commerce website. 
- Evaluation metric: conversion rate
- Unit of diversion: user id

## Libraries 
```import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import random
import statsmodels.api as sm
from statsmodels.stats.proportion import proportions_ztest
```

## Data
Datasets are downloaded from website. They are provided here.
> ab_data.csv 

> countries.csv

## Methodology
- Similate binomial distributions to construct distributions for p difference
- Run logistic regression to analyze coefficients of page variale

## Results
Shown in the end of notebook. 
