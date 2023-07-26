# Predicting Flight Arrival Delays 🛬

The U.S. Department of Transportation's (DOT) Bureau of Transportation Statistics tracks the on-time performance of domestic flights operated by large air carriers. Summary information on the number of on-time, delayed, canceled, and diverted flights is published in DOT's monthly Air Travel Consumer Report and in this dataset of 2015 flight delays and cancellations.

### Objective 🎯
Prediction whether a given flight would be delayed or not. 

### Description Of Dataset 📊 
The given dataset is divided for 3 files:
  1. airlines.csv - contains all information about airlines names and codes
  2. airports.csv - contains all information about airport names, codes and location (city, state, longitude, lattitude)
  3. flights.csv - contains 5.819.079 records with informations about given flights, like airlines, airports, dates, delays and other important flight informations

### Methodology ⚙️
To predict delays, I performed a train-test split of 80:20. I've analysed the various factors responsible for flight arrival delays and applied machine learning models such as Random Forest, XGBoost, Logistic Regression, Decision Tree, NaiveBayes to predict whether a given flight would be delayed or not. Appropriate graphs and metrics were generated for the analysis and performance of the different models were compared.
