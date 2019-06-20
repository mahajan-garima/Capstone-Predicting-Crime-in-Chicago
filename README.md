# Capstone-Predicting-Crime-in-Chicago

EXECUTIVE SUMMARY
--------------------------
In this project I analyzed the Chicago Crime dataset (between the years 2012–2019), which is one of the richest open source data in this area, to get a better understanding about the security status of this city.
Data Source: https://data.cityofchicago.org

**Goal**
The aim of this project is to classify a criminal incident by type, depending on its occurrence at a given time of the day,  season and location details.

This project is to help the law enforcement agencies to effectively allocate resources based on the type of crime and keep the neighbour hood safe.


**Data Cleaning**

1. Removed the null values
2. There are 22 Police districts in Chicago. Removed the invalid police district "31" from the data.

**Feature Engineering**

1. Extracted month,day,time,day of week year from the datetime column
2. Broadly classified crime classification into 11 broader crime categories.
3. Converted month into season {Autumn,Summer,Winter,Spring}
4. Converted time into parts_of_day {early morning,late morning,afternoon,evening,night}







