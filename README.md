# Airplane Price Prediction  
### Multiple Linear Regression | EDA | Power BI Dashboards

## 📌 Overview  
This project predicts **airplane market prices** using multiple linear regression and explores the key technical, operational and economic factors influencing aircraft valuation—all visualised through interactive Power BI dashboards.  
The dataset consists of **12,377 airplane records** originally collected in Turkish, translated into English for analysis.

---

## 🎯 Objectives  
- Build a regression model to estimate airplane prices  
- Identify the most significant price-influencing factors  
- Perform EDA to uncover trends related to capacity, engine type, range, and pricing  
- Create interactive Power BI dashboards to visualise insights  
- Evaluate model performance using metrics: R², RMSE, MSE, MAE, Accuracy  

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
- **Language:** R  
- **ML:** Multiple Linear Regression  
- **Libraries:** tidyverse, caret  
- **Visualization & Dashboards:** Power BI  
- **Tools:** GitHub, R Studio  

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
