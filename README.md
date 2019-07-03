# dataanalytics
data analytics course
This project was part of my Data Analyst - Nanodegree course at Udacity.The data set was taken from the below source(
https://docs.google.com/document/d/e/2PACX-1vQmkX4iOT6Rcrin42vslquX2_wQCjIa_hbwD0xmxrERPSOJYDtpNc_3wwK_p9_KpOsfA6QVyEHdxxq7/pub?embedded=True). 
I chose Ford GoBike System Data for my analysis.


In this exercise, I have used Python's data science and data visualization libraries to explore the dataset’s variables and understand 
the data’s structure, oddities, patterns and relationships.


The structure of my data set is:-

My Data set contains trip data of users in San Francisco Bay Area with fields as :-
Trip Duration (seconds),
Start Time and Date,
End Time and Date,
Start Station ID,
Start Station Name,
Start Station Latitude,
Start Station Longitude,
End Station ID,
End Station Name,
End Station Latitude,
End Station Longitude,
Bike ID,
User Type (Subscriber or Customer – “Subscriber” = Member or “Customer” = Casual),
Member Year of Birth,
Member Gender 


I am interested in figuring out the factors which influence the trip duration

The features in the dataset that have helped my investigation into your feature(s) of interest?
1.Trip Duration
2.User Type 
3.Start Date and End Date


Data Wrangling


I took some data wrangling steps before getting started with the exploration:-
1.Convert the duration in seconds to hours
2.Delete bike share for all trip column
3.Delete values where the station id is null
4.Convert the end and start station id to int
5.Segregate the start_time into indvidual fields like start_date and start_time
6.Segregate the end_time into indvidual fields like end_date and end_time
7.Extract day and month from start date, end date 

