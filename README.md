# RetailPulse 360 — Sales, Profit & Customer Intelligence System

A Python-based business analytics project that turns raw retail transaction data into actionable business intelligence — built as part of the **MainCrafts SkillSprint: Data Science & Data Analytics Using Python** (48-hour challenge).

## 📌 Project Overview

A growing retail company has thousands of transactions but no clear view of what is actually driving its performance. This project analyzes a Superstore-style transactional dataset to answer:

- Which products/categories generate the most revenue and profit?
- Which regions and customer segments perform best?
- Are high-discount orders actually profitable?
- How does sales performance change over time?
- What business actions should management take?

**Workflow:** `Understand → Clean → Analyze → Visualize → Discover → Explain → Recommend`

## 📊 Dataset

- **Source:** Superstore / Global Superstore transaction dataset
- **Size:** 10,194 records × 21 columns
- **Period:** 2023 – 2026
- **Fields:** Order/Ship dates, Customer, Segment, Region, Category, Sub-Category, Product, Sales, Quantity, Discount, Profit, Ship Mode

## 🛠️ Tools & Libraries

- Python (Google Colab)
- Pandas, NumPy — data cleaning & aggregation
- Matplotlib, Seaborn — visualization
- Scikit-learn — profit-prediction regression model

## 🔍 Key Findings

- **Total Sales:** $2,326,534.35 | **Total Profit:** $292,296.81 | **Profit Margin:** 12.56%
- **Technology** is the strongest category in both sales and profit.
- The **West region** is the top performer on every measure; **Central** has the weakest profit margin (7.92%).
- Strong negative correlation (**-0.86**) between discount rate and profit margin — discounts of 30%+ are frequently unprofitable.
- Sales are highly seasonal, peaking every year in **November–December**.
- Counter-intuitively, **Standard Class** (slowest) shipping is far more profitable than **Same Day** (fastest).
- A baseline linear regression model predicts profit with **R² ≈ 0.49**.

Full methodology, all visualizations, and business recommendations are in the notebook and the accompanying report.

## 📁 Repository Structure

```
RETAILPULSE-360/
│
├── README.md
├── RetailPulse360_OumarMahamatKadergueli.ipynb
├── dataset/
│   └── sample_-_superstore.xls
├── visuals/
│   └── (exported charts and dashboard screenshots)
├── report/
│   └── RetailPulse360_OumarMahamatKadergueli_Report.pdf
└── requirements.txt
```

## 🚀 How to Run

1. Clone this repository.
2. Open `RetailPulse360_OumarMahamatKadergueli.ipynb` in Google Colab or Jupyter.
3. Install dependencies: `pip install -r requirements.txt`
4. Run all cells in order — the notebook loads, cleans, analyzes and visualizes the dataset end to end.

## 👤 Author

**Oumar Mahamat Kadergueli**
MainCrafts SkillSprint — Data Science & Data Analytics Using Python

## 🙏 Acknowledgment

Built as part of the **MainCrafts Technology SkillSprint** program.
