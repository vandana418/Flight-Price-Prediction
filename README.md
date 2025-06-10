# ✈️ Flight Price Prediction

This project involves building a machine learning model to predict flight ticket prices based on features like airline, source, destination, departure time, and duration. The goal is to help travelers and travel platforms estimate the cost of a flight.

---

## 🎯 Objective

To predict the price of flight tickets using historical flight data and identify key factors that influence price fluctuations.

---

## 📊 Features Used

- Airline
- Date of Journey
- Source and Destination
- Departure and Arrival Time
- Total Stops
- Duration of Flight
- Additional Information

## 🧠 Workflow

1. **Data Collection**
   - Loaded dataset (e.g., `flight_data.csv`)

2. **Data Preprocessing**
   - Feature engineering: extracting day, month, hour
   - Encoding categorical variables
   - Handling missing or inconsistent data

3. **Exploratory Data Analysis (EDA)**
   - Understanding trends and correlations
   - Price distribution visualization

4. **Model Training**
   - Algorithms: Linear Regression, Decision Tree, Random Forest, XGBoost
   - Performance evaluation using R² score, MAE, RMSE

5. **Model Saving**
   - Best model saved as `flight_price_model.pkl` using `pickle` or `joblib`

## 🧰 Technologies Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- XGBoost
- Jupyter Notebook
