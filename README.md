**Airplane Price Prediction using Multiple Linear Regression & Power BI Dashboards**

**Project Overview:**

  This project focuses on predicting the market price of airplanes using machine learning techniques. Airplane pricing is influenced by multiple technical, operational, and economic factors such as engine type, number of engines, seating capacity, fuel consumption, maintenance cost, range, and sales region. The project applies Multiple Linear Regression to estimate aircraft prices accurately and uses Exploratory Data Analysis (EDA) and interactive dashboards to visualize key trends and insights in the aviation market.

  The dataset consists of 12,377 airplane records with 11 critical features, originally sourced in Turkish and translated into English for analysis. This project provides valuable insights for aircraft manufacturers, buyers, leasing companies, and aviation analysts to make informed decisions based on data-driven predictions and market intelligence.

**Objectives:**

* Develop a predictive model to estimate airplane prices using historical data.

* Identify key factors influencing the market value of aircraft.

* Perform EDA to uncover trends in capacity, engine type, range, and pricing.

* Build interactive dashboards using Power BI to visually interpret results.

* Evaluate model performance using metrics such as R², RMSE, MSE, MAE, and Accuracy.

**Dataset Description:**

The dataset contains the following features:

Feature	Description:

* Model	- Aircraft name/model
* Production Year	- Year of manufacture (1980–2023)
* Number of Engines -	Total engines (1 for piston, 2+ for turbofan)
* Engine Type -	Turbofan or Piston
* Capacity -	Maximum passenger seating
* Range (km) -	Maximum distance per flight
* Fuel Consumption	- Liters per hour
* Maintenance Cost -	Hourly maintenance expense
* Age	- Production Year
* Sales Region -	Continent or regional sales market
* Price ($) -	Target variable (market price in USD)

**Data Preprocessing & Exploration**

* Handled missing values and standardized column names.
* Encoded categorical variables for analysis.
* Conducted statistical summary and structure analysis using R (summary(), str(), head()).
* Applied data visualization using line charts, bar charts, and pie charts to explore:
  - price trends over the years
  - Fuel consumption by model
  - Passenger capacity distribution
  - Engine type impact on price

**Business Intelligence Dashboards:**

Interactive Power BI dashboards were created to present insights into:

* Average and minimum aircraft prices by model
* Maintenance cost vs. price comparison
* Fuel efficiency trends
* Regional sales performance
* Engine type distribution (91% turbofan vs. 9% piston)
* Yearly market price trends and forecast view

Dashboards help stakeholders quickly interpret critical factors affecting aircraft prices and optimize purchasing or selling strategies.

**Model Evaluation:**

The model was evaluated using regression metrics:

* Metric	Value	Interpretation
* R-squared	(0.915) -	Model explains 91.5% of price variance
* RMSE (67,401,326) -	Moderate prediction error
* MAE	(49,496,987) -	Average price prediction error
* Accuracy (75.25%) -	Good performance with improvement potential

These results demonstrate strong predictive capability, with further enhancements possible using advanced models like Random Forest, XGBoost, or Neural Networks.

**Prediction & Inference:**

* The model predicts aircraft prices based on key features.
* Inference indicates that engine type, capacity, and range are significant drivers of market value.
* Turbofan engines and higher capacity models consistently display higher pricing due to efficiency and operational advantages.

**Conclusion:**

  This project successfully demonstrates the use of data science and machine learning in the aviation sector. By integrating statistical modeling and interactive dashboards, it presents a comprehensive solution for forecasting airplane prices. The model provides valuable insights into the factors affecting aircraft valuation and supports strategic planning, investment analysis, and market forecasting.

**Tools & Technologies:**

* Language: R
* Libraries: tidyverse, caret
* Machine Learning: Multiple Linear Regression
* Visualization: Power BI
* Dashboarding: Interactive, filters enabled by region, model, and engine type

**Future Enhancements:**

* Integrate advanced ML models (Random Forest, Gradient Boosting, Neural Networks)
* Deploy model via web interface (Streamlit/Flask)
* Include external economic factors (fuel price trends, inflation rate)
* Implement real-time prediction with API integration
