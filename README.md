# -Customer-Lifetime-Value-Prediction
a full pipeline for predicting Customer Lifetime Value (CLV) using real-world e-commerce data (Online Retail Dataset)
🔹 Data Cleaning & Preprocessing — handled missing values, removed cancelled orders, capped outliers using IQR, and engineered a clean dataset ready for modeling.
🔹 Feature Engineering — built RFM features (Recency, Frequency, Monetary), extracted temporal signals (hour, day, season), created session-based behavioral features, and computed CLV per customer.
🔹 Exploratory Data Analysis — analyzed top countries by revenue, monthly sales trends, Pareto (80/20) analysis of customer spend, and top products by quantity & revenue.
🔹 Regression Models — trained and compared Gradient Boosting, Random Forest, and ElasticNet regressors to predict CLV (evaluated with RMSE, MAE, R²).
🔹 Classification Task — converted CLV into a binary High-Value Customer label (top 25%), then trained an XGBoost classifier with Stratified K-Fold Cross-Validation, ROC-AUC evaluation, and a Calibration Curve analysis.
Tech Stack: Python · Pandas · Scikit-learn · XGBoost · Seaborn · Matplotlib
