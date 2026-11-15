# Online Retail Analysis: Sales, Customers and Returns

Python analysis of 541,909 transactions from a UK online gift retailer
(Dec 2010 – Dec 2011).

## Questions answered
- When, where and what sells the most?
- Which customers bring the revenue, and who is drifting away?
- Do new customers come back?
- Which products are cancelled most?

## Tools
Python, pandas, NumPy, Matplotlib, Seaborn

## Data cleaning
541,909 rows → 522,504 rows (19,405 removed): missing descriptions,
duplicates, cancelled invoices, zero/negative quantity or price,
non-product codes (postage, manual entries).

## Key findings
- Revenue peaks in **November 2011 (1.45M)**, the pre-Christmas season.
- The UK brings **85.1%** of revenue.
- The top 20% of customers bring **74.6%** of revenue.
- **Champions** are 25.8% of customers but **66.1%** of revenue.
- Only about 15–24% of new customers return in their second month.
- Two huge cancelled orders overstate the revenue of two top products.

## Techniques used
Data cleaning · feature engineering · Pareto analysis · RFM segmentation ·
cohort retention analysis

## Files
- `Retail_analysis.ipynb`: full analysis with charts and findings
- `images/`: chart images

## Data source
[UCI Online Retail dataset](https://archive.ics.uci.edu/dataset/352/online+retail)

Author: Komal Sargar
