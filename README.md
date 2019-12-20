# TrafficSpeed-AD
#### Project6 for EECS 731

The dataset for this project is for traffic speed, which can be found in this link: <br>
https://github.com/numenta/NAB/blob/master/data/realTraffic/speed_6005.csv

The project involves:

* Data Exploration
 > Load the data set into panda data frames and extract its data shape and statistic features <br>
 > Convert dat into time series dataframe, and show the value accross time

* Anomaly Detection
  In this part, we adopt two different models to do this task:
  
  Model 1: Isolation Forest <br>
  Model 2: One-class SVM

 Isolation Forrest detects more outliers than one-class SVM.
 
 More details and discussion could be found in code comments.
