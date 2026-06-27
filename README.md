# Superstore — Data Cleaning & EDA

End-to-end data cleaning and exploratory analysis on the Superstore retail dataset using Python and Pandas.

## Overview

This project covers the full data preparation pipeline before any analytics or modeling:
- Column normalization and type casting
- Date parsing and feature engineering (year, month, quarter, delivery delay)
- Duplicate and null value handling
- Derived metrics: cost, margin, profitability rate
- Segment analysis: top clients, top products, regional sales

## Tech Stack

**Python** · **Pandas** · **Jupyter Notebook**

## Project Structure

```
├── data_cleaning.ipynb   # Full cleaning and EDA pipeline
└── store.csv             # Raw Superstore dataset
```

## Key Steps

1. Column name normalization (lowercase, accent removal)
2. Date conversion to datetime format
3. Feature engineering: delivery time, cost, margin, profitability
4. Aggregations: monthly growth, regional sales, top segments
5. Export of cleaned dataset to `projet.csv`

## Dataset

Superstore sales data — 9,800 rows × 27 columns after cleaning.
