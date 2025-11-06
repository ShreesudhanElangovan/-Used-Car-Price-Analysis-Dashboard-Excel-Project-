🚗 Used Car Price Analysis Dashboard (Excel, 2010–2020)
📘 Overview

An interactive Excel dashboard analyzing used car prices from 2010–2020.
It explores how brand, fuel type, transmission, age, and mileage influence car prices and fuel efficiency.
The dashboard provides dynamic insights through KPIs, slicers, and charts — enabling users to explore patterns in pricing, depreciation, and performance.

🧩 Features

Data Cleaning – Removed missing values, standardized numeric columns, and categorized brands, transmissions, and fuel types.

Exploratory Data Analysis (EDA) – Studied how key factors like engine size, age, and mileage impact car prices.

Correlation & Regression Insights – Identified which variables most influence car value.

Interactive Dashboard – Built in Excel with:

Dynamic slicers (Brand, Fuel Type, Transmission)

KPI cards (Total Cars, Avg Price, Avg Mileage, Avg Age, Avg MPG)

Trend and comparison pivot charts

Highlighted Key Insights section

📊 Dashboard Insights

Used car prices increased steadily from 2010–2020, reflecting consistent market appreciation.

Premium brands (Mercedes, Audi, BMW) have the highest prices, while Ford and Skoda cater to budget segments.

Electric vehicles show the highest MPG, outperforming hybrid and petrol cars.

Automatic transmissions generally command higher prices than manual ones.

Price distribution shows mid-range and budget cars dominate, with luxury vehicles forming a smaller but high-value share.

Dataset Overview:

Metric	Value
Total Cars	57,512
Average Price	£19,205
Average Mileage	22,851 miles
Average Age	8 years
Average Fuel Efficiency	56 MPG
🧠 Key Visuals

📈 Average Price by Brand

📉 Average Price by Year (2010–2020 Trend)

⛽ Fuel Type vs Average MPG

⚙️ Transmission vs Average Price

🔵 Engine Size vs Price (Scatter with Trendline)

🟢 Actual vs Predicted Price (Regression Performance)

⚙️ Tools & Techniques
Category	Tools / Methods
Data Cleaning	Microsoft Excel
Analysis	Correlation, Linear Regression
Visualization	Excel Pivot Charts, Slicers, KPIs
Reporting	Interactive Dashboard (Export as PDF/Image)
📈 Analytical Summary
🔹 Correlation Summary

Correlation analysis revealed several key relationships:

Price ↗ Engine Size: Strong positive correlation — larger engines tend to increase car price.

Price ↘ Age / Mileage: Negative correlation — older, high-mileage cars lose value faster.

MPG ↘ Engine Size: Larger engines are less fuel-efficient.

Tax ↗ Engine Size: Bigger engines attract higher taxes.

🧩 Interpretation:
Performance-related factors (engine size, tax) drive prices upward, while depreciation factors (age, mileage) pull them down — consistent with real-world trends.

🔹 Regression Summary

A multiple linear regression model was built using engine size, age, mileage, MPG, and tax to predict price.

R² ≈ 0.74 — model explains ~74% of price variation.

Engine size has the strongest positive effect on price.

Age and mileage contribute negatively.

Residuals show random distribution, confirming consistent, unbiased predictions.

🧮 Interpretation:
The regression model supports dashboard insights — newer cars with larger engines command higher resale prices, while older or heavily driven cars depreciate predictably.

📉 Residual Analysis

Residuals are centered around zero, showing minimal error spread.
A slight positive bias appears for luxury brands — the model underestimates high-end prices due to missing brand-specific effects.
No visible pattern confirms model stability and validity.

📊 Interpretation:
Regression performance is strong and reliable; accuracy could be further improved by including categorical predictors such as brand or transmission type.

💡 Key Findings

Prices rose steadily from 2010–2020, led by fuel-efficient and electric models.

Larger engine cars remain the most expensive segment.

Depreciation: Prices drop 10–15% per year after purchase.

Premium brands (BMW, Audi, Mercedes) retain resale value better than average.

Electric vehicles deliver the highest fuel efficiency (MPG) and lowest tax costs.

🧭 Recommendations
🔹 For Buyers

Focus on 2–4-year-old vehicles for best value retention.

Choose smaller engines to reduce fuel and tax costs.

Consider hybrid/electric models for long-term efficiency.

🔹 For Sellers / Dealers

Emphasize low mileage and engine performance in listings.

Highlight fuel efficiency and eco-friendly features to attract modern buyers.

🔹 For Future Work

Incorporate time-series forecasting for market price prediction.

Add brand-wise regression or machine learning models for improved precision.

Include categorical dummy variables (brand, fuel type, transmission) for richer model performance.

🧠 Executive Summary

A multiple linear regression model was developed to predict used car prices based on mileage, age, engine size, MPG, and tax.
The model achieved R² = 0.736, explaining ~74% of price variation, with RMSE = £8,191 and MAE = £6,596, demonstrating high predictive accuracy.
Residuals show random distribution, confirming reliability.
Future improvements include adding categorical predictors such as brand and fuel type.

🧑‍💻 Created by Shreesudhan Elangovan

© 2025 | Excel Data Analytics Project
