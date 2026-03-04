# Kaggle Retail Sales Analysis

## Overview

This project analyzes Walmart retail sales data to understand sales patterns across different stores, departments, and time periods. The analysis includes exploratory data analysis (EDA), data preprocessing, and time series forecasting using multiple modeling approaches.

## Dataset

The project uses three datasets from Kaggle:

- **Sales Data** (`sales data-set.csv`): Weekly sales figures for different store-department combinations
- **Features Data** (`Features data set.csv`): External features including temperature, fuel price, markdowns, CPI, and unemployment rates
- **Stores Data** (`stores data-set.csv`): Store information including type and size

### Data Overview

- **Total Records**: 421,570 sales records
- **Number of Stores**: 45
- **Departments per Store**: Up to 99
- **Time Period**: 2010-2012 (weekly granularity)

## Project Structure

```
kaggle_retail_sales/
├── retail_sales.ipynb          # Main analysis notebook
├── data_sets/
│   ├── Features data set.csv
│   ├── sales data-set.csv
│   └── stores data-set.csv
├── pyproject.toml
└── README.md
```

## Summary

Best performing model is LightGBM