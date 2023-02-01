# **Storm Troopers Capstone**
### Flight cancellation and delay prediction model using US flights and weather events

This repository contains the Capstone Project for Dev10 Cohort 40 Group Storm Troopers. The project team consists of: Stephen Duval, David Perhai, Meghan Roffler, and Talia Willcott. 

In the United States in 2021, there were approximately 6.2 million passenger flights, with approximately 1 million flights delayed and 100k flights cancelled. Flight delays and cancellations are frustrating for both travelers and airlines. Although there are many factors that can affect a timely departure (such as busy travel seasons, airline/airport issues, or flight systems issues), this project chooses to focus on weather events and weather-caused flight delays/cancellations. A deeper understanding of how flight schedules are affected by weather has the potential to help both airline operators minimize losses and passengers maximize ease of travel. This project will examine 2021 passenger flight data and 2021 weather events in order to find existing patterns and create a machine learning model to predict whether or not a flight will be delayed or cancelled. This readme is broken down as follows:

### Markdown Navigation
<!-- TOC -->
- [Concept Map](#Concept-Map)
- [Introduction](#Introduction)
- [Data Details](#Data)
- [Project Questions](#Project_Questions)
- [Repository Contents](#Repository-Contents)
- [PowerBI Dashboard](#PowerBI_Dashboard)

<!-- /TOC -->

### Concept Map
![this image will not be displayed](https://files.smallpdf.com/files/b2694a0e2e404886b899fb3f1bbc37bf-0001.jpg?name=Flights_2021_ConceptMap.jpg)

### Introduction
This project examines flight data in conjunction with weather events to explore patterns in flight cancellations and delays. The main dataset used is from the Bureau of Transportation Statistics and tracks passenger flights across the United States. Our second dataset is from Kaggle and includes weather reports taken from 2,071 airport-based weather stations across the United States. We decided to only look at the data from 2021 for both datasets due to the magnitude of data. This project explores how weather affects the efficiency of flights by examining the timeliness and consistency of the flights based on the current state of the weather. As a stretch goal, we hoped to use machine learning to develop an app-like program that could learn from our merged data in order to determine whether a flight would be canceled or not. As a super stretch goal, we also wanted it to predict how long the delay might be if the flight were to not be canceled. Overall, our results show that deviations from the flight schedule are not efficiently predicted by weather at time of flight.

### Data
1. [Bureau of Transportation Statistics](https://www.transtats.bts.gov/Tables.asp?QO_VQ=EFD&QO_anzr=Nv4yv0r%FDb0-gvzr%FDcr4s14zn0pr%FDQn6n&QO_fu146_anzr=b0-gvzr) (2021 Flight Data)
	- Visit the above page and choose the desired fields for monthly flight data. Then download as monthly csv files
	- The raw data was 52 columns and over 6 million rows
2. [Weather Data from Kaggle](https://www.kaggle.com/datasets/sobhanmoosavi/us-weather-events)
	- Download the above dataset, which includes an airport code
	- SIZE OF DATASET??
3. Current flight data from [FlightRadar24](https://www.flightradar24.com/42.85,-93.35/6)
	- Acquired through an API key
	- Needed to create an account with RapidAPI, them query
	- Query1 parameters: List of flights by airlines for given day
	- Query2 parameter: In-depth flight information using the list of flight ids obtained in Query1


### Project Questions
1. Are there regional patterns for length of departure delays?
2. Do different states suffer greater delays for the same type of weather events?
3. What weather type causes the most delays? Per state? 
4. Which airlines have the fewest and most delays?
5. Do certain airports have more delays on average? Is it correlated with weather or a different delay factor?
6. How much seasonality will we see in the data? How much do holidays affect delays and cancellations?
7. Which factors will have the greatest predictive power in delay lengths?


### Repository Contents 
- PowerBI Reports 
- ETL Report
- EDA Report
- Technical Report
- Data Dictionary


### PowerBI Dashboards
Although our PowerBI Reports can be found as .pbix files in our repository, our dashboards can only be accessed by URL. Below you will find our:
- [Condensed Dashboard](https://app.powerbi.com/groups/1babf15b-e7e7-40a7-93bc-1583b618e8b5/dashboards/921be722-5b40-400c-a03f-ec34c618686d)
- [Full Dashboard](https://app.powerbi.com/groups/1babf15b-e7e7-40a7-93bc-1583b618e8b5/dashboards/2737bc96-c3a4-4e7e-b523-be083aeaca01)



	
