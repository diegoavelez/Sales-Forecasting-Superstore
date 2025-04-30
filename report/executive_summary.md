
# Executive Summary: Demand Forecasting & Customer Behavior

**Author:** Diego Alejandro Vélez Martínez - AI Engineer  
**Email:** d.alejandrovelez@gmail.com  
**GitHub:** https://github.com/diegoavelez

---

## 1. Project Objective

This project was designed to predict monthly sales volumes by product category using historical transaction data and machine learning models. The goal was to support decision-making in areas like demand forecasting, inventory planning, and product strategy.

---

## 2. Business Questions Answered

- Which product categories drive the most revenue and margin?
- How seasonal is the demand, and when should we stock more?
- Are customers sensitive to price changes?
- Can we predict next month's sales using historical patterns?

---

## 3. Data Analysis Highlights

- Seasonality: Sales spike strongly in November
- Product Lines: Classic Cars: high sales, low margin. Vintage Cars: balanced
- Regions: USA, Spain, and France place largest orders
- Price Sensitivity: No clear global trend, but varies by product line
- Client Base: ~57 clients = 80% of revenue (distributed pattern)

---

## 4. Machine Learning Results

**Final model performance comparison:**

- Random Forest (Tuned) - MAE: 22,396.65 | RMSE: 47,780.45 | R²: 0.6499  
- XGBoost - MAE: 21,647.61 | RMSE: 38,440.00 | R²: 0.7734 ✅

---

## 5. Strategic Recommendations

- **Marketing:** Focus campaigns in November (Q4), especially for Classic and Vintage Cars.
- **Pricing:** Maintain premium pricing on low-sensitivity products.
- **Logistics:** Prepare inventory and logistics ahead of Q4 seasonal spikes.
- **CRM:** Target top 50-60 clients with tailored strategies and upselling offers.
- **Forecasting:** Deploy XGBoost model into sales simulation or inventory planning tools.

---

## 6. Tools & Technologies Used

Python, Pandas, Matplotlib, Seaborn, Scikit-learn, XGBoost, Jupyter Notebooks, Markdown, GitHub, Notion
