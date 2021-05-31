# Time Series Airport Traffic Prediction:    Charles de Gaulle Airport

## Purpose:
This project was used to show how to use time series in order to predict future events based on previous patterns and events.

![Charles de Gaulle Airport](https://github.com/Zexes9/Time-Series/blob/main/Graphics/ParijsCharlesdeGaulleAirport-400x292.jpg)

### See our presentation for a more [detailed view](https://drive.google.com/file/d/1TSoFw47IsO7kJO4E4cZmHXazuloj-Jlw/view?usp=sharing). 

## Data Set:
This dataset contains the traffic for Charles de Gaulle Airport in France from January 2000 December 2019.


## Method:
The methodology used was to EDA of the dataset, clean it, then to employ a Box-Jenkins time series analysis.


## Result
Based on our In-Sample test from 2017 to 2019:
![image](https://user-images.githubusercontent.com/76630966/119959959-c4aac600-bfa4-11eb-9a69-a9e83d2a5197.png)

We found that our model ARIMA (0,1,3)(0,1,1)[12], with no dummy variables, was our best model with an AIC of -860.1.
The rest of our residuals was white noise and the proportion of points in the confidence bound is 88.24%.

Our prediction of 2020 to 2023 predicted a continued increase in traffic for the Charles de Gaulle Airport, if COVID-19 had not happened.

![image](https://user-images.githubusercontent.com/76630966/119961355-3e8f7f00-bfa6-11eb-82e7-b9e01493ecd6.png)

## Conclusion

We conclude that the Airport traffic will continue to increase over time, after the COVID 19 pandemic has been taken care of.  
