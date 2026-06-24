📌 Project Overview
Retail businesses face significant challenges in balancing inventory levels with fluctuating customer demand. Overstocking increases operational costs, while stockouts lead to lost sales and poor customer experience.
This project leverages Machine Learning, Time Series Forecasting, and Retail Analytics to predict future product demand, identify seasonal sales patterns, and generate insights for inventory optimisation. Using over 2 million retail transaction records, the solution helps improve supply chain efficiency and support data-driven inventory planning.

🛒 Retail-Demand-Forecasting-Inventory-Optimisation
> Seasonal trends
> Promotional events (Black Friday)
> Holiday periods (Christmas)
> Product categories
> Warehouse-specific demand patterns
> Supplier lead times

Without accurate forecasting, retailers risk:
- Stockouts during high-demand periods
- Excess inventory carrying costs
- Inefficient warehouse allocation
- Reduced customer satisfaction


💡 Solution
Developed an end-to-end retail analytics and forecasting pipeline that:
✔ Analyses historical sales trends
✔ Identifies key demand drivers
✔ Forecasts future product demand using XGBoost
✔ Supports inventory optimisation decisions
✔ Helps reduce stockout risk during peak seasons


📊 Dataset Information
The dataset contains approximately 2.19 million retail transaction records across multiple warehouses and product categories.

Features
Feature	Description
Date	Transaction Date
Warehouse	Warehouse Location
Product_ID	Unique Product Identifier
Units_Sold	Number of Units Sold
Black_Friday_Flag	Promotional Event Indicator
Christmas_Flag	Holiday Season Indicator
Category	Product Category
Lead_Time_Days	Supplier Lead Time
Time Period

January 2024 – December 2025

🔑Key Findings
Birmingham warehouse generated the highest overall sales volume.
Grocery products contributed the largest share of demand.
Black Friday promotions significantly increased sales volumes.
Christmas periods showed strong seasonal demand uplift.
Demand patterns varied across warehouses and product categories.
Products with longer supplier lead times exhibited higher stockout risk.
A small percentage of products contributed a large proportion of total sales (ABC Analysis).


🤖 Machine Learning Model
Model Used
XGBoost Regressor
Chosen for its:
Strong predictive performance
Ability to capture non-linear relationships
Robust handling of tabular business data
High interpretability through feature importance analysis

📈 Model Evaluation
The model was evaluated using a time-based train-test split to preserve chronological order.

Evaluation Metrics
Mean Absolute Error (MAE)
Root Mean Squared Error (RMSE)
Mean Absolute Percentage Error (MAPE)
Validation Approach
Historical data used for training
Future periods reserved for testing
Time-series forecasting methodology applied

📊 Visualisations
This project includes:

Daily Demand Trends
Monthly Seasonality Analysis
Warehouse Performance Analysis
Product Category Analysis
Black Friday Impact Analysis
Christmas Demand Analysis
ABC Inventory Classification
Actual vs Predicted Demand Forecasts
Feature Importance Analysis

🛠️ Tech Stack
Programming & Analytics
Python
Pandas
NumPy

Visualisation
Matplotlib
Seaborn
Machine Learning
Scikit-Learn
XGBoost
Data Science Techniques
Exploratory Data Analysis (EDA)
Feature Engineering
Time Series Forecasting
Inventory Analytics
Demand Forecasting

📈 Business Impact
This solution enables retailers to:
Improve demand forecasting accuracy
Reduce stockout risk
Optimise inventory allocation
Improve warehouse planning
Support data-driven supply chain decisions
Prepare for seasonal demand spikes

🔑 Key Achievements
Analysed 2.19M+ retail transactions to identify demand trends, seasonal patterns, and operational risks.
Built an XGBoost-based forecasting model using advanced lag and rolling-window features for product-level demand prediction.
Delivered actionable recommendations for inventory optimisation, stock allocation, and stockout prevention, supporting smarter retail supply chain management.
