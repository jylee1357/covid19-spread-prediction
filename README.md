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

### ⌨️ Data Analysis & Models
* EDA
  - Comparing population by states
    <img width="948" alt="Screen Shot 2022-06-18 at 4 03 41 PM" src="https://user-images.githubusercontent.com/98932859/174426892-01932828-8dd6-4c51-bbc9-5c2b02b8c347.png">
   - Number of people tested vs confimed cases
    <img width="883" alt="Screen Shot 2022-06-18 at 4 05 24 PM" src="https://user-images.githubusercontent.com/98932859/174426934-5733d401-38a2-42ee-8d3f-57028a57f49f.png">

    
### 📍 Takeaway
* In deep learning model, Random Forest Regressor scored the lowest RMSE
* In time series model, LSTM scored the lowest RMSE
