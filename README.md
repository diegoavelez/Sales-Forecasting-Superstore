# 📊 Sales Forecasting and Customer Behavior Analysis

**Author:** Diego Alejandro Vélez Martínez  
**Role:** Data Scientist
**Tools:** Python, Scikit-learn, XGBoost, Pandas, Seaborn, Matplotlib

---

## 🎯 Project Objective

This project aims to analyze customer behavior and sales performance across product lines,  
and to build a machine learning model capable of forecasting monthly demand.

The goal is to support business decisions in **inventory planning**, **sales strategy**, and **product prioritization**.

---

## 🧠 Problem Overview

Retail companies need to predict future sales by product category to reduce stockouts,  
optimize inventory, and improve marketing ROI.

This project uses historical sales data to:
- Identify key behavior patterns and customer insights
- Train a supervised regression model for demand forecasting
- Translate insights into actionable business recommendations

---

## 🧰 Technologies Used

- Python 3.11+
- Pandas, NumPy
- Seaborn & Matplotlib (EDA Visualizations)
- Scikit-learn (Random Forest, GridSearchCV)
- XGBoost (Final Model)
- Jupyter Notebooks
- Notion / GitHub Pages (Documentation)

---

## 🧪 Machine Learning Approach

| Step | Description |
|------|-------------|
| Feature Engineering | Created variables: `SEASON`, `IS_HOLIDAY_SEASON`, `IS_HIGH_MARGIN` |
| Model 1 | Random Forest Regressor (tuned via GridSearchCV) |
| Model 2 | **XGBoost Regressor** – best performance |
| Target | Monthly sales (`SALES`) per product line |
| Features | Year, Month, ProductLine, Margin, Quantity, Season, Holiday flags |

---

## 📈 Model Performance

| Model     | MAE       | RMSE      | R²     |
|-----------|-----------|-----------|--------|
| Random Forest (tuned) | 22,396.65 | 47,780.45 | 0.6499 |
| **XGBoost**           | **21,647.61** | **38,440.00** | **0.7734** |

---

## 💡 Strategic Business Insights

- **Seasonality**: Sales spike in November across key categories.
- **Product Strategy**: Vintage Cars = high-margin & stable; Classic Cars = volume-driven.
- **Customer Behavior**: No global price sensitivity, but product-specific differences.
- **Geographic Targeting**: USA, Spain, France = high average order size → bulk potential.
- **Client Segmentation**: ~57 clients = 80% of revenue, but no extreme dependency.

---

## 🗂️ Repository Structure

```plaintext
Sales-Forecasting-Superstore/
├── notebook/
│   └── sales_forecasting.ipynb
├── data/
│   └── superstore_sales.csv
│   └── superstore_sales_modeled.csv
├── models/
│   └── xgboost_model.pkl
├── report/
│   └── executive_summary.md
│   └── executive_summary.docx
└── README.md
```
---

## ▶️ How to Run
1. Clone this repository

2. Install dependencies
```bash
pip install -r requirements.txt
```
3. Run the notebook
```bash
jupyter notebook notebook/sales_forecasting.ipynb
```

## 🙌 Acknowledgments

This project was developed as part of my professional transition into AI Engineering,
bringing together real-world business experience and technical AI capability.

If you’re interested in collaborating or hiring for applied AI roles — feel free to connect:

	•	📧 d.alejandrovelez@gmail.com
	•	🌐 [LinkedIn](https://www.linkedin.com/in/diegoavelezm)
	•	🧑‍💻 [GitHub](https://github.com/diegoavelez)
