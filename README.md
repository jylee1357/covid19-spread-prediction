# US COVID-19 Spread Prediction
### 🙋‍♂️ Goals
- Find out important factors when predicting the spread of COVID-19 in the United States
- Predict the speed of covid-19 in the United States

### 𝌞 Data Collection & Preprocessing 
* "4.18 States"
  - List of 50 states
  - Number of new cases/deaths/Tests by week
* "Abridged Counties"
  - Population by states
* "Time Series Covid 19 Confirmed"
  - Number of new cases from Jan 21 2020 to Apr 18 2020 in all 50 states
* "Time Series Covid 19 Death"
  - Number of new deaths from Jan 21 2020 to Apr 18 2020 in all 50 states

### ⌨️ Models
* Model Comparison 
  - Deep learning model's RMSE
    <img width="1040" alt="Screen Shot 2022-06-13 at 10 11 43 PM" src="https://user-images.githubusercontent.com/98932859/173361479-b682afb8-11ab-4e81-9b52-cdabe619b8ac.png">
    <img width="1028" alt="Screen Shot 2022-06-13 at 10 13 31 PM" src="https://user-images.githubusercontent.com/98932859/173361722-89449368-f598-4d7f-abc2-5d705319e0ac.png">  
    
   - Time series model's RMSE
    <img width="997" alt="Screen Shot 2022-06-13 at 10 17 13 PM" src="https://user-images.githubusercontent.com/98932859/173362374-c2c3510f-da8d-4365-8b4d-ebf1375be862.png">
    
### 📍 Takeaway
* In deep learning model, Random Forest Regressor scored the lowest RMSE
* In time series model, LSTM scored the lowest RMSE
