# Customer-Churn-Retention
End-to-end Machine Learning pipeline to predict customer churn using Random Forest and SMOTE. Includes a business ROI simulation to translate model accuracy into revenue savings.

#  Customer Churn & Retention Engine
**Business Case:** Reducing subscriber attrition for a high-volume Telecommunications provider.

##  Project Overview
This project identifies at-risk customers using **Random Forest Classification** and translates technical accuracy into **Monthly Recurring Revenue (MRR)** savings. 

##  Tech Stack
* **Python (Pandas, Scikit-Learn)**: Data pipeline & Modeling.
* **IMB-Learn (SMOTE)**: Handling class imbalance.
* **Matplotlib/Seaborn**: Insight visualization.
* **Business Logic**: ROI & Retention Campaign Simulation.

##  Key Insights
* **Top Churn Predictors**: Month-to-month contracts and lack of online security services.
* **Model Performance**: Achieved high **Recall (82%)** to ensure maximum capture of at-risk users.
* **Financial Impact**: The proposed retention strategy saves an estimated **$14k+ in Annualized Revenue** for the tested segment.

##  How to Run
1. Clone this repo.
2. Install dependencies: `pip install -r requirements.txt`.
3. Open `notebooks/churn_analysis_and_roi.ipynb` in Google Colab or Jupyter.
