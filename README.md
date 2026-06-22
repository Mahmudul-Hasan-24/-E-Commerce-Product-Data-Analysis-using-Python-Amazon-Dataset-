# Amazon-Product-Data-Analysis-Python

> Exploratory data analysis of Amazon e-commerce product data using Python — uncovering pricing patterns, discount effectiveness, and customer engagement insights to support seller strategy.

---

## Project Overview

This project analyzes a real Amazon product dataset from Kaggle to answer key business questions around pricing, discounts, ratings, and customer behavior. The goal is to help sellers make smarter decisions about discount strategy, category investment, and product positioning.

**Tools & Technologies:** Python · Pandas · Matplotlib · Seaborn · Jupyter Notebook

---

## Research Questions

1. Which product categories generate the highest average discounted price?
2. Are deeper discounts associated with higher ratings or more reviews?
3. Which categories and products receive the highest customer ratings?
4. Which categories are the most competitive (by product count and total reviews)?
5. Which products have the largest price gap between actual and discounted price?

---

## Key Findings

- Categories with high average discounted prices do **not** necessarily have the highest ratings — pricing alone does not drive customer satisfaction
- Deeper discounts show **weak correlation** with higher ratings, suggesting quality matters more than discount size
- The most competitive categories have both high product counts and high total review volumes — making differentiation harder for new sellers
- Products with the largest price gaps (perceived biggest deals) are concentrated in electronics and home appliance categories
- Targeted discounting in high-rating, low-competition categories offers the best growth opportunity for sellers

---

## Dataset

- **Source:** Kaggle — Amazon product listings dataset
- **Fields:** Product ID, Product Name, Category, Actual Price, Discounted Price, Discount %, Rating, Rating Count, Review details
- **Derived features:** Price Gap (Actual − Discounted Price), Normalized Rating Count

---

## Analysis Steps

1. **Data Cleaning** — Removed currency symbols (₹), commas, and percentage signs; converted all price and rating fields to numeric; handled missing and invalid values
2. **Feature Engineering** — Created Price Gap column; normalized rating counts for cross-product comparison
3. **Exploratory Data Analysis (EDA)** — Descriptive statistics, distribution analysis, and category-level comparisons
4. **Visualization** — Bar charts, scatter plots, and logarithmic-scale plots using Matplotlib and Seaborn
5. **Business Recommendations** — Actionable insights for pricing strategy, category investment, and customer engagement

---

## Repository Structure

```
├── Amazon_data_analysis_Project.ipynb    # Main analysis notebook
└── amazon.csv                            # Dataset (from Kaggle)
```

---

## How to Run

```bash
# Clone the repository
git clone https://github.com/Mahmudul-Hasan-24/Amazon-Product-Data-Analysis-Python.git

# Install required packages
pip install pandas matplotlib seaborn jupyter

# Launch the notebook
jupyter notebook Amazon_data_analysis_Project.ipynb
```

---

## Skills Demonstrated

- Data cleaning and preprocessing with Pandas
- Exploratory data analysis (EDA)
- Business-focused data visualization (Matplotlib, Seaborn)
- Correlation analysis and statistical interpretation
- Translating data insights into actionable business recommendations

---

## Author

**Mahmudul Hasan**
M.Sc. Computational Social Systems (Business Analytics)
Technical University of Graz & University of Graz
[LinkedIn](https://www.linkedin.com/in/mahmudul-hasan-764307249/) · [GitHub](https://github.com/Mahmudul-Hasan-24)
