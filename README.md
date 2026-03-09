# E-Commerce Transaction Analysis

Exploratory data analysis and transformation of a large-scale e-commerce client dataset using Pandas. Surfaces key metrics across product categories, customer segments, and purchasing behavior to inform merchandising and pricing strategy.

---

## Key Findings

- Analyzed **client_dataset.csv** covering client ID, job, category, subcategory, units purchased, shipping price, line price, and profit
- Identified top-performing **product categories and subcategories** by revenue and unit volume
- Calculated **profit margins** across segments and surfaced highest-value customer profiles
- Validated data transformations to confirm accuracy of derived metrics

---

## Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

- **Core library:** Pandas for data loading, transformation, aggregation, and validation
- **Analysis:** Group-by aggregations, value counts, summary statistics, derived metric calculation

---

## Project Structure

```
├── module_4_challenge.ipynb    # Main analysis notebook
├── client_dataset.csv          # Source transaction data
└── README.md
```

---

## Methodology

1. Loaded and explored client transaction dataset — shape, dtypes, summary stats
2. Transformed raw fields to calculate line revenue, shipping cost, and profit
3. Identified top 5 clients by units ordered and confirmed order totals
4. Validated calculations against known benchmarks before surfacing insights
5. Summarized key metrics for each top client including spend and profit contribution
