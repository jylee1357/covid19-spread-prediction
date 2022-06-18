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
  - **Comparing population by states**
    <img width="948" alt="Screen Shot 2022-06-18 at 4 03 41 PM" src="https://user-images.githubusercontent.com/98932859/174426892-01932828-8dd6-4c51-bbc9-5c2b02b8c347.png">
   - **Number of people tested vs confimed cases**
    <img width="883" alt="Screen Shot 2022-06-18 at 4 05 24 PM" src="https://user-images.githubusercontent.com/98932859/174426934-5733d401-38a2-42ee-8d3f-57028a57f49f.png">
    
   - **Population (US) vs Spreading Speed of Covid19**   
    <img width="809" alt="Screen Shot 2022-06-18 at 4 07 02 PM" src="https://user-images.githubusercontent.com/98932859/174426982-270e59ca-4f35-4dfe-aaee-2eb2c214cdcd.png">
    
   - **Data Transformation using MinMaxScaler**  
    <img width="753" alt="Screen Shot 2022-06-18 at 4 08 28 PM" src="https://user-images.githubusercontent.com/98932859/174427034-decae4f1-41af-4ae5-aab9-2a54f5070d96.png">
    
### ⌨️ Models
* Linear Model Score: 0.128
* Non Linear ($x^2$) model score: 0.638
* Non Linear ($x^3$) model score: 0.977
<img width="714" alt="Screen Shot 2022-06-18 at 4 14 23 PM" src="https://user-images.githubusercontent.com/98932859/174427233-eba95947-55e6-4430-ad75-634a76a07428.png">

    
### 📍 Takeaway
* In deep learning model, Random Forest Regressor scored the lowest RMSE
* In time series model, LSTM scored the lowest RMSE
