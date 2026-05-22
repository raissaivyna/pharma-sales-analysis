# Pharmaceutical Sales Data Analysis

Analysis of pharmaceutical sales data using Python, Pandas and Matplotlib.

## Dataset

Daily sales data for 8 drug categories (ATC codes) from 2014 to 2019.
Source: [Pharma Sales Data — Kaggle](https://www.kaggle.com/milanzdravkovic/pharma-sales-data)

Place the dataset file at:

    data/salesdaily.csv

## Questions answered

1. What are the total sales quantities for each drug category?
2. Which drugs have the highest total sales volume?
3. Top 3 drugs in January 2015, July 2016 and September 2017?
4. What was the best-selling drug in 2017?
5. Which drug category has the highest average daily sales?
6. Are respiratory drugs (R03) more sold in certain months?

## Key findings

- N02BE (analgesics) dominates sales in every period analyzed
- R03 (respiratory) shows clear seasonality — peaks in winter months
  (October, December, January) and drops in summer (July, August)
- N05C (hypnotics) is the least sold category across all periods

## Technologies

- Python 3
- Pandas — data manipulation
- Matplotlib — data visualization
- Jupyter Notebook

## How to run

Install dependencies:

    pip install pandas matplotlib jupyter

Launch the notebook:

    jupyter notebook

Open `pharma_sales_analysis.ipynb` and run all cells.
