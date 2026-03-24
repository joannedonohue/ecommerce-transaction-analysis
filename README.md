# E-Commerce Transaction Analysis

Exploratory data analysis and customer segmentation on a large-scale e-commerce transaction dataset — built with pandas to surface revenue drivers, profit margins, and high-value customer profiles.

---

## Overview

This project performs end-to-end exploratory analysis on an e-commerce client dataset, transforming raw transaction records into actionable business insights. The analysis identifies top-performing product categories, calculates profit margins across customer segments, and validates revenue and cost transformations against known benchmarks — demonstrating production-ready data wrangling practices.

---

## Dataset

| Field | Description |
|---|---|
| client_id | Unique customer identifier |
| job | Client occupation |
| category | Product category |
| subcategory | Product subcategory |
| units_purchased | Order quantity |
| shipping_price | Shipping cost |
| line_price | Total line revenue |
| profit | Net profit per transaction |

---

## Analysis Objectives

1. Identify top-performing product categories and subcategories by revenue and unit volume
2. Calculate profit margins across customer segments
3. Identify highest-value customer profiles by spend and profit contribution
4. Validate all data transformations against benchmarks for accuracy

---

## Methodology

1. Load dataset and perform exploratory profiling (shape, dtypes, summary statistics)
2. Engineer derived fields: line revenue, shipping cost contribution, and profit per transaction
3. Identify top 5 clients by units ordered
4. Apply `groupby` aggregations across category, subcategory, and customer dimensions
5. Validate all calculated fields against known benchmarks
6. Summarize key metrics for top clients (total spend, profit contribution, order frequency)

---

## Tech Stack

| Component | Tool |
|---|---|
| Data analysis | pandas |
| Aggregation | groupby, value_counts, agg |
| Validation | Custom benchmark checks |
| Notebook environment | Jupyter |
| Language | Python |

---

## Repository Structure

```
ecommerce-transaction-analysis/
├── ecommerce_transaction_analysis.ipynb   # Full analysis notebook
├── client_dataset.csv                     # Source transaction data
└── README.md
```

---

## Outcomes

- Identified top product categories and subcategories driving the highest revenue and unit volume
- Calculated profit margins across customer segments, surfacing the highest-value client profiles by spend and contribution
- Built a validated data transformation pipeline with benchmark checks ensuring accuracy of all derived metrics
- Demonstrated production-grade pandas workflows for EDA on large transaction datasets: multi-level groupby, value counts, and summary aggregation

---

## Getting Started

```bash
pip install pandas jupyter
jupyter notebook ecommerce_transaction_analysis.ipynb
```
