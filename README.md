# Iowa Liquor Sales Analysis

An end-to-end analysis of Iowa's wholesale liquor sales data: cleaning, SQL validation, exploratory analysis, regression, classification, and clustering.

## Question
What drives liquor pricing and sales patterns across Iowa, and can product attributes predict price and category?

## Key results
- **Regression (OLS):** Product attributes explain ~40% of variation in bottle price (RMSE ≈ $11)
- **Classification (Decision Tree):** Predicts product category with 84% test accuracy
- **Clustering (K-Means):** Five product segments with distinct price tiers and dominant categories
- **Trends:** Sales peak in December, and transaction size rose sharply from 2019–2021

## Data
Iowa Liquor Sales data published by the State of Iowa, covering wholesale spirits orders placed by licensed retailers. I analyzed a random 1% sample (`random_state=54`). The dataset is not included in this repo due to its size.

## Tools
Python (pandas, scikit-learn, statsmodels, matplotlib, seaborn), SQL (SQLite)
