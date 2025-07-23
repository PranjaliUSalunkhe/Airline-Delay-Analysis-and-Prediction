# ✈️ Airline Delay Analysis & Prediction

This project analyzes over 4 million flight records from the U.S. Department of Transportation's Airline On-Time Performance dataset to uncover delay patterns and build predictive models for flight delays. The goal is to assist airlines and airports in minimizing travel disruptions and improving operational efficiency.

---

## 📌 Objectives

- Identify key causes and trends of flight delays, cancellations, and diversions
- Predict delay duration using machine learning models
- Visualize delay patterns by airline, airport, time of year, and cause

---

## 📂 Dataset

- **Source:** [U.S. DOT Airline On-Time Performance](https://www.transtats.bts.gov/DL_SelectFields.aspx?gnoyr_VQ=FGJ&QO_fu146_anzr=b0-gvzr)
- **Size:** 4,095,932 records | 110 columns
- **Time Period:** Jan 2024 – Jul 2024
- **Features:** Flight date, departure/arrival times, delays, cancellations, diversions, airlines, airports, weather, etc.

---

## 🧪 Tools & Technologies

- **Languages:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost  
- **ML Models:** Linear Regression, Random Forest, XGBoost  
- **Metrics:** R², MAE, MSE  
- **IDE:** Jupyter Notebook

---

## 🔍 Exploratory Data Analysis (EDA)

- Delay trends by airline, airport, month, and time of day
- Breakdown of delay causes (Carrier, Weather, NAS, Security, Late Aircraft)
- Cancellation and diversion patterns
- Top delay-prone airports and routes

---

## 🤖 Machine Learning

- **Feature Engineering:** Day of week, month, flight distance, scheduled departure hour, etc.  
- **Models Trained:**  
  - Linear Regression  
  - Random Forest Regressor  
  - XGBoost Regressor  
- **Best Result:**  
  - **XGBoost** achieved **R² > 80%** in predicting delay durations

---

## 📊 Visualizations

- Delay distribution across airlines (bar plots)  
- Delay causes over time (line charts)  
- Seasonal variation in delays (heatmaps)  
- Delay by airport (ranked visuals)  
- Flight status breakdown (pie charts)

---

## 💡 Key Insights

- 70% of delays originated from 5 major airports  
- Weather and late aircraft were top contributing delay factors  
- Flights after 6 PM had the highest average delay durations

---

## 🚀 Future Improvements

- Integrate with real-time flight API for live predictions  
- Build a Power BI dashboard for dynamic reporting  
- Extend to international flight data analysis

---

## 📎 Resources

- [Dataset Download](https://www.transtats.bts.gov/DL_SelectFields.aspx?gnoyr_VQ=FGJ&QO_fu146_anzr=b0-gvzr)
- [Project Medium Article](https://medium.com/@rvora3/analyzing-and-predicting-airline-delays-a-comprehensive-data-science-approach-c08d5de14a10)

---

## 👤 Author

**Pranjali Salunkhe**  
- [LinkedIn](https://www.linkedin.com/in/pranjali-salunkhe-0201b725a/)  
- [GitHub](https://github.com/PranjaliUSalunkhe)

---

