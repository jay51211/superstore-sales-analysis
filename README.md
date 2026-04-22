# 🛒 Superstore Sales Analysis

> Exploratory data analysis of a global superstore dataset to uncover what drives sales, what kills profit, and where the business should focus next.

---

## 🧩 Problem Statement

A global retail superstore wants to understand the performance of its sales across regions, product categories, and customer segments. The goal is to identify patterns in revenue, profitability, and discount behaviour — and translate those into clear, data-backed business recommendations.

---

## 📊 Dataset

- **Source:** Global Superstore Sales dataset
- **Records:** ~10,000 orders
- **Features:** Order date, Region, Country, Category, Sub-category, Sales, Profit, Discount, Shipping Mode, Customer Segment
- **Period Covered:** Multi-year transaction data

---

## 🔍 Key Findings

### Discounts vs Profitability
- **Moderate discounts (10–20%)** show the best balance of sales volume and profit margin
- **Discounts above 30%** consistently result in negative profit — the business is losing money on these orders
- High-discount orders account for a disproportionate share of total losses

### Seasonal Trends
- Sales peak in **Q4 (October–December)**, driven by holiday demand
- A consistent mid-year dip occurs in **Q2**, suggesting an opportunity for targeted promotions
- Year-over-year sales show steady growth, but profit growth has not kept pace

### Shipping Mode Analysis
- **Standard Class** is the most used shipping mode but generates uneven profit margins
- **Same Day shipping** has the lowest volume but the highest profit-per-order ratio
- **First Class** underperforms relative to its cost — a potential area for cost review

### Regional Performance
- The **West region** leads in both sales and profit
- The **Central region** has high sales but significantly lower profit margins — discount abuse is likely a factor
- **South** region is the smallest in volume but shows healthy profit margins

---

## 💡 Business Recommendations

1. **Cap discounts at 20%** — any discount beyond this threshold results in net losses. Implement discount approval thresholds for the sales team
2. **Run Q2 promotional campaigns** to address the consistent mid-year sales dip and balance out revenue across the year
3. **Audit Central region pricing and discount policies** — high sales with low profit signals uncontrolled discounting
4. **Promote Same Day and First Class shipping to high-value customers** — the profit margins justify the pitch
5. **Focus upselling in the Technology category** — it drives the highest profit margins across all regions

---

## 🛠️ Tech Stack

| Area | Tools |
|------|-------|
| Data Analysis | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Environment | Jupyter Notebook |

---

## 🏗️ Project Structure

```
superstore-sales-analysis/
│
├── superstore_sales_analysis.ipynb   # Full EDA notebook
├── superstore.csv                    # Dataset
├── images/                           # Exported charts
└── README.md
```

---

## 📈 Visualizations Included

- Average Sales by Discount Level
- Discount Impact on Profit Margin
- Monthly & Quarterly Sales Trends
- Profit by Shipping Mode
- Sales and Profit by Region
- Top 10 Sub-categories by Profit

---

## ⚙️ Run Locally

```bash
# Clone the repo
git clone https://github.com/jay51211/superstore-sales-analysis.git
cd superstore-sales-analysis

# Install dependencies
pip install pandas numpy matplotlib seaborn jupyter

# Launch notebook
jupyter notebook superstore_sales_analysis.ipynb
```

---

## 👤 Author

**Jay Kumbhar**
📧 jaykumbhar518@gmail.com
💼 [LinkedIn](https://linkedin.com/in/jaykumbhar5121) | 💻 [GitHub](https://github.com/jay51211)
