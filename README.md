# **Storm Troopers Capstone**
### Flight cancellation and delay prediction model using US flights and weather events

This repository contains the Capstone Project for Dev10 Cohort 40 Group Storm Troopers. The project team consists of: Stephen Duval, David Perhai, Meghan Roffler, and Talia Willcott. 

In the United States in 2021, there were approximately 6.2 million passenger flights, with approximately 1 million flights delayed and 100k flights cancelled. Flight delays and cancellations are frustrating for both travelers and airlines. Although there are many factors that can affect a timely departure (such as busy travel seasons, airline/airport issues, or flight systems issues), this project chooses to focus on weather events and weather-caused flight delays/cancellations. A deeper understanding of how flight schedules are affected by weather has the potential to help both airline operators minimize losses and passengers maximize ease of travel. This project will examine 2021 passenger flight data and 2021 weather events in order to find existing patterns and create a machine learning model to predict whether or not a flight will be delayed or cancelled. This readme is broken down as follows:


### Markdown Navigation
<!-- TOC -->
- [Concept Map](#Concept-Map)
- [Introduction](#Introduction)
- [Repository Contents](#Repository-Contents)

<!-- /TOC -->

### Concept Map
![this image will not be displayed](https://files.smallpdf.com/files/b2694a0e2e404886b899fb3f1bbc37bf-0001.jpg?name=Flights_2021_ConceptMap.jpg)


### Introduction
This project examines flight data in conjunction with weather events to explore patterns in flight cancellations and delays. The [main dataset](https://www.transtats.bts.gov/Tables.asp?QO_VQ=EFD&QO_anzr=Nv4yv0r%FDb0-gvzr%FDcr4s14zn0pr%FDQn6n&QO_fu146_anzr=b0-gvzr) used is from the Bureau of Transportation Statistics and tracks passenger flights across the United States. Our [second dataset](https://www.kaggle.com/datasets/sobhanmoosavi/us-weather-events) is from Kaggle and includes weather reports taken from 2,071 airport-based weather stations across the United States. We decided to only look at the data from 2021 for both datasets due to the magnitude of data. This project explores how weather affects the efficiency of flights by examining the timeliness and consistency of the flights based on the current state of the weather. As a stretch goal, we hoped to use machine learning to develop an app-like program that could learn from our merged data in order to determine whether a flight would be canceled or not. As a super stretch goal, we also wanted it to predict how long the delay might be if the flight were to not be canceled. Overall, our results show that deviations from the flight schedule are not efficiently predicted by weather at time of flight.


### Repository Contents 
- Readme file
- PowerBI Reports 
- ETL Report
- EDA Report
- Technical Report

