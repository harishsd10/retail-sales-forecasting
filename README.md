# 🛒 Retail Sales Forecasting & Analytics Intelligence Platform

[![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://render.com/deploy?repo=https://github.com/harishsd10/retail-sales-forecasting)

A comprehensive Retail Sales Forecasting, Machine Learning, and Customer Behavior Analytics platform analyzing transactional data across supermarket branches.

## 🚀 Live Demo & Deployment
- **Deploy to Render:** Click the button above for 1-click cloud deployment.
- **Interactive Dashboard:** Complete HTML5 + Tailwind + Chart.js dynamic analytics platform with real-time demographic filters and live satisfaction prediction simulator.

## 📊 Core Features & Supervised Machine Learning
1. **Sales & Category Trends:** Revenue breakdown across Food & Beverages, Sports & Travel, Electronic Accessories, Fashion, Home & Lifestyle, and Health & Beauty.
2. **Customer Demographics & Behavior:** Segmentation by Gender, Membership (Member vs. Normal), Average Order Value (AOV), and payment method utilization (Cash, E-wallet, Credit card).
3. **Supervised ML Classification Models:**
   - **Decision Tree Classifier** vs. **Logistic Regression** predicting customer rating categories (High: >= 7.0 vs. Low: < 7.0).
   - Evaluated using Accuracy, Precision, Recall, F1-Score, and ROC-AUC benchmarking.
4. **Actionable Managerial Recommendations:** Strategic data-backed business insights for operational parity, digital payment migration, and VIP member retention.

## 📦 Project Structure
- `main.py` — Complete master Python pipeline (Data loading, Preprocessing, EDA, Models, Metrics)
- `supermarket_sales_ml.py` — Standalone ML pipeline and plot generator
- `Supermarket_Sales_Analysis_and_ML.ipynb` — Google Colab & Jupyter-ready notebook
- `supermarket_sales.csv` — Full 1,000-transaction dataset
- `processed_supermarket_data.csv` — Feature-engineered dataset
- `index.html` — Interactive web analytics dashboard
- `executive_summary_report.md` — Strategic business recommendations report
- `app.py`, `Procfile`, `render.yaml` — Render deployment configuration
- `images/` — High-resolution visualization charts
