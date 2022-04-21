# RAINFALL PREDICTION USING CLASSIFICATION MODELS

My capstone project is created for St. Clair Collegecourse - M018, Data Analytics for  Business

## Overview of the project

Australia's rainfall is highly known for its extreame temperature. The rainfall pattern is around the extensive core of the continents of the Australia. as australia is the second driest continent on the earth. There are still major gaps in our understanding of the reasons of observed rainfall patterns, both in the mean and extremes, as well as climate models' capacity to effectively simulate rainfall in the Australian region and future rainfall forecasts. 

### Abstract

My dataset is about rain in Australia, this dataset contains about 10 years of daily weather observations from many locations across Australia. This dataset contains 145460 records and 23 attributes. ‘Rain Tomorrow’ is target variable to predict, that provide information about “will it rain tomorrow, Yes or No?”. Our dataset contains 1 Date/Time attribute that contains particular date of each observation with year and month, 6 categorical attributes such as Location that elaborates different location in Australia, WindGustDir that represents direction of wind gust, WindDir includes direction of wind, RainToday which provides logical information about present day rain prediction, RainTomorrow shows the distribution regarding whether it will be raining tomorrow or not and contains 16 numerical attributes that are WindGustSpeed that shows the speed of wind gust in km/h, Pressure includes atmospheric pressure in hpa (hectro pascal pressure units), MaxiTemp includes information about maximum temperature point, MiniTemp contains information regarding minimum temperature and Humidity shows the humidity level. Then we perform initial analysis on our dataset.  We will build different classification models to check their accuracy. We will also use Logistic regression, Random Forest, K-Neighbors and Naïve Bayes classifications models and choose an optimal model with highest accuracy score. The main motive behind choosing this dataset is to forecast about tomorrow regarding there will be rain or not, predicting accuracy of our result and also perform cross validation to find out which model is optimal for my dataset by comparing accuracies.

#### KEYWORDS:  

Data visualization, Logistic regression model, K-Nearest Neighbors, Random Forest, Naïve Bayes Classification models.

#### RESEARCH QUESTIONS:

1.	Check yearly distribution of rainfall to find the years with highest and lowest rain fall.
Ans:- I analysed the yearly distribution of rainfall. We can observe that the wettest years were 2010, 2011, and 2016, with about 33000mm of rain. The wettest years were 2007, 2008, and 2017, with rainfall ranging from 25000 to 30000 mm in 2009, 2012, 2013, 2014, and 2015.

2.	Find out the degree of temperature that contains highest counts?
 The highest concentration of points of temperature is between 17 to 20 degrees Celsius.
 
4.	Check the distribution of target attribute to evaluate will there be rain tomorrow or not?

ANs:- The distribution of the goal variable 'Will it rain tomorrow?' is represented by the pie chart above, which has two slices: 'Yes' (Will Rain) and 'No' (Will Not Rain) (No Rain). The graph shows that the chances of raining tomorrow are quite low, since yes only accounts for 21.6 percent of the total, while no accounts for 78.4 percent. As a result, it is apparent that pouring tomorrow will have more implications.
5.	Build different classification models and select an optimal model by comparing accuracies of all models.

##### Data Dictionary 

Our dataset is Rainfall in Australia which includes the information about rain fall, temperature, wind speed regarding different locations in Australia. This dataset contains 145460 records and 23 attributes. This dataset is generated from Kaggle. Dataset contains information between the year 2007 to 2017 and which year having the maximum and minimum rainfall, speed of the wind, temperature about different locations. Our dataset contains enough missing values and for performing operation we removed those null values by dropping attributes and records. It has attributes with different datatypes, and we converted them into required pattern. 


