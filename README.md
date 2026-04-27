# 🛒 Amazon-product-analysis-python

## 📌 Project Overview
This project performs **exploratory data analysis (EDA)** on an Amazon e-commerce product dataset.  
The goal is to:
- Explore **product categories, pricing, ratings, and reviews**
- Uncover **patterns that affect sales and customer behavior**
- Provide **insights that can support pricing, marketing, and inventory decisions**

---

## 🗂 Repository Structure
```
├── data/
│   └── amazon_products.csv     # Dataset (or link to Kaggle/source)
├── notebooks/
│   └── EDA.ipynb              # Main analysis notebook
├── images/
│   └── category_distribution.png
└── requirements.txt           # Python dependencies
```

---

## 🔍 Analysis Steps

1. **Data Cleaning & Preparation**
   - Handle missing values
   - Remove duplicates
   - Convert numerical columns (e.g., price, rating) to proper format

2. **Exploratory Data Analysis**
   - Distribution of product ratings
   - Price range distribution across categories
   - Relationship between discount %, price, and reviews

3. **Visualization**
   - Histograms, bar plots, and box plots to reveal patterns
   - Category-wise rating distribution
   - Correlation heatmap for numerical variables

4. **Insights & Recommendations**
   - Identify top-performing categories
   - Suggest price optimization opportunities
   - Recommend focus areas for marketing campaigns

---

## 📊 Key Insights

| Insight | Observation |
|--------|-------------|
| ⭐ Rating Distribution | Most products have ratings between 3.5 and 4.5 |
| 💲 Pricing | Discounted products receive **20–30% more reviews** |
| 🏷 Category Insights | Electronics and Fashion dominate product count |
| 🔗 Correlation | Positive relationship between review count and rating (popular products rated higher) |

---

## 🖼 Example Visualization
![Category Distribution](images/category_distribution.png)

---

## 🛠 How to Run Locally

### 1. Clone the repository
```bash
git clone https://github.com/Mahmudul-Hasan-24/E-Commerce-Product-Data-Analysis-using-Python-Amazon-Dataset.git
cd E-Commerce-Product-Data-Analysis-using-Python-Amazon-Dataset
```

### 2. Create and activate a virtual environment
```bash
python -m venv venv
source venv/bin/activate       # On Windows: venv\Scripts\activate
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

### 4. Launch the notebook
```bash
jupyter notebook notebooks/EDA.ipynb
```

---

## 📦 Dependencies
- pandas – Data manipulation
- numpy – Numerical analysis
- matplotlib, seaborn – Visualizations
- jupyter – Notebook interface

---

## 🚀 Future Improvements
- Build a **predictive model** to estimate ratings based on product features  
- Add **sentiment analysis** on review text (if available)  
- Deploy a **dashboard** (Streamlit / Power BI) to share findings interactively  

---

## 📜 License
This project is licensed under the MIT License – see [LICENSE](LICENSE) for details.

---

## 👤 Author
**Mahmudul Hasan**  
Master’s of Computational Social System (Business Analytics) at Technical University of Graz and University of Graz  

