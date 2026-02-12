# Airplane Price Prediction  
### Multiple Linear Regression | EDA | Power BI Dashboards

## 📌 Project Goal & Business Value

- The primary objective of this project is to provide a data-driven valuation framework for the aviation industry. By leveraging historical market data, this predictive model assists sellers, buyers, and fleet managers in estimating aircraft prices with high precision.

- Standardizing Valuation: Eliminates subjective pricing bias by using objective features like Aircraft Age, Engine Configuration, and Seating Capacity.

- Risk Mitigation: Helps buyers avoid overpaying and sellers avoid undervalued listings by identifying the "Fair Market Value" through Multiple Linear Regression.

- Market Transparency: Provides stakeholders with a clear understanding of which technical specifications (e.g., Number of Engines vs. Fuel Type) drive the most significant price fluctuations.

## Overview  
and explores the key technical, operational and economic factors influencing aircraft valuation—all visualised through interactive Power BI dashboards.  
The dataset consists of **12,377 airplane records** originally collected in Turkish, translated into English for analysis.

---

## 📁 Dataset Features  
Key features used in the modelling:  
- Model – Aircraft name/model  
- Production Year (1980 – 2023)  
- Number of Engines  
- Engine Type (Turbofan / Piston)  
- Capacity (max passenger seating)  
- Range (km)  
- Fuel Consumption (L/hr)  
- Maintenance Cost (hourly expense)  
- Sales Region (continent or regional market)  
- Price ($) – Target variable  

---

## 🔧 Data Preprocessing & EDA  

- Handled missing values and standardised column names
  
- Categorical encoding of variables (Engine Type, Sales Region)
  
- Explored data via statistical summaries (`summary()`, `str()`, `head()` in R)
  
- Visualised:  
  - Price trends over production years  
  - Fuel consumption by model  
  - Passenger capacity distribution  
  - Engine type impact on price  

---

## 📊 Power BI Dashboard Highlights  
- Price comparison by aircraft model (average, minimum)  
- Maintenance cost vs price relationship  
- Fuel efficiency trends across models  
- Engine type distribution (91% Turbofan vs 9% Piston)  
- Regional sales insights  
- Yearly market price trends and forecast view  

---

## 🤖 Model Performance  
| Metric | Value | Interpretation |
|--------|--------|----------------|
| R²     | 0.915  | 91.5% of price variance explained |
| RMSE   | 67,401,326 | Moderate average error in USD |
| MAE    | 49,496,987 | Average absolute error |
| Accuracy| 75.25% | Good predictive performance, room for improvement |

---

## 🔍 Key Insights  
- Engine type (Turbofan vs Piston), capacity and range are major drivers of price  
- Aircraft with turbofan engines and higher capacity consistently show higher market value  
- Maintenance cost is strongly correlated with older aircraft age  
- Sales region influences pricing trends based on market demand and region specific factors  

---

## 🛠 Tech Stack  
- **Language:** R programming
- **ML:**  Feature engineering, Multiple Linear Regression, Model evaluation
- **Libraries:** tidyverse, caret  
- **Visualization & Dashboards:** Power BI  
- **Tools:** R Studio, Power BI

---

## 🚀 Future Enhancements  
- Implement advanced models: Random Forest, XGBoost, Neural Networks  
- Deploy the model via Streamlit or Flask web application  
- Integrate external economic variables: fuel price trends, inflation rate  
- Build real-time prediction API with live data feed  

---

## ✅ Conclusion  
This project combines machine learning and interactive dashboards to analyse and forecast airplane prices. The insights and visualisations provide strategic value for aircraft manufacturers, buyers, leasing firms and aviation analysts.

⭐ *If you found this repository useful, feel free to give it a star!*  
