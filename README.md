📊 Retail Sales Forecasting for Rossmann Stores

Enhancing revenue strategy using Exploratory Analysis, Statistical Testing, and Machine Learning

🚀 Project Overview

This project focuses on building a robust machine learning system to forecast daily store-level sales for a large retail chain (similar to Rossmann). With over 1 million rows and 24 features, the dataset enables deep exploration of sales patterns, seasonal trends, customer behavior, promotions, competition, and store characteristics.

The goal of the project is to design a complete end-to-end analytical pipeline, starting from business problems → data understanding → exploratory analysis → statistical testing → ML modeling → model explainability → business insights.

❓ Problem Statement

Retailers face complex challenges:

How do promotions, holidays, competition, and store type influence daily sales?

Which time-based seasonal patterns (month, week, year, holidays) matter the most?

Is there a statistically significant difference in sales across store types and promotions?

Can we build a predictive model that accurately forecasts daily store sales at scale?

What are the top features driving sales predictions, and how can stores act on them?

This project answers these questions using a combination of analytics, statistics, and machine learning.

📂 Dataset Description

The dataset contains 1,017,209 rows and 24 variables representing daily store operations.

Key features include:

Store identifiers & operational status

Promotions (Promo, Promo2, Promo intervals)

Holidays (StateHoliday, SchoolHoliday)

Time-based fields: Year, Month, WeekOfYear, Quarter, DayOfWeek

Customer counts & competition data

Store attributes: StoreType, Assortment

The dataset mixes numerical, categorical, temporal, and missing-value-rich variables, requiring careful preprocessing.

🔧 Project Workflow
1️⃣ Data Understanding & Preprocessing

Date parsing and temporal feature extraction

Missing value treatment for competition & promotions

Categorical encoding

Feature scaling where required

2️⃣ Exploratory Data Analysis (EDA)

Charts were used to analyze:

Sales trends over time

Weekly and seasonal patterns

Promo vs non-promo sales

Customer–sales relationship

StoreType-wise performance

Competition impact

🧪 Statistical Testing

To validate insights:

t-test / Mann–Whitney U → Promo vs non-promo sales

ANOVA → StoreType impact

ADF test → Stationarity of sales

Jarque–Bera → Normality

Durbin–Watson → Autocorrelation

VIF → Multicollinearity

These tests ensured statistical credibility before modeling.

🤖 Machine Learning Modeling

Models trained and compared:

Linear Regression (baseline)

Random Forest Regressor

XGBoost Regressor (final model)

Hyperparameter tuning used GridSearchCV and RandomizedSearchCV.

✅ Final Model Performance (XGBoost)

RMSE: ~658

MAE: ~23

R²: 0.955

🧠 Model Explainability (XAI)

Used SHAP (SHapley Additive Explanations) to interpret predictions.

Top drivers of sales:

Promo

Customers

StoreType

CompetitionDistance

Month & DayOfWeek

This ensures transparent, business-ready decision-making.

🏪 Business Impact

This project helps retailers:

Forecast daily sales accurately

Optimize inventory & staffing

Improve promotion timing and ROI

Gain store-level strategic insights

Reduce operational risk and improve profitability

🔗 Project Links & Resources
🌐 Live Project Website

👉 Retail Sales Forecasting Project
https://shubham-walnut-kernels.github.io/Retail_Sales_Regression/

📘 Machine Learning Notebook

👉 View Project Notebook (HTML)
https://shubham-walnut-kernels.github.io/Retail_Sales_Regression/retail_sales_regression%20(1).html

📊 Interactive Dashboard (Visualization)

👉 View Dashboard
https://app.thebricks.com/file/06f11552-8a69-45f6-8980-7bba8890d7bc

🔗 GitHub Repository

👉 View Source Code
https://github.com/shubham-walnut-kernels/Retail_Sales_Regression

⭐ If you found this project useful, feel free to star the repository or connect with me!
