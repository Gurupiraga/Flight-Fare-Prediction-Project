# Flight-Fare-Prediction-Project
Problem Statement
Flight ticket prices can be something hard to guess, today we might see a price, check out the price of the same flight tomorrow, it will be a different story. We might have often heard travelers saying that flight ticket prices are so unpredictable. That’s why we will try to use machine learning to solve this problem. This can help airlines by predicting what prices they can maintain.

Domain Analysis:
1) Airlines:
An organization that provides regular public air transportation on one or more routes. The service allows travelers to search multiple carriers' flight schedules. This column includes various types of airlines, such as Indigo, Jet Airways, and Air India, among others.

2) Date_of_Journey:
This column is going to notify us of the date the passenger's travel will begin.

3) Source:
This column contains the name of the location from which the passenger's journey will begin.

4) Destination:
This column includes the name of the location to which the passengers wish to travel.

5) Route:
In this column, we can learn about the path that travelers have chosen to take from their origin to their destination.

6) Dep_Time:
When the plane departs from the airport.

7) Arrival_Time:
The arrival time is the time when the traveler will arrive at his or her destination.

8) Duration:
The duration of a flight is the amount of time it takes to go from the starting point to the destination.

9) Total_Stops:
This feature will tell us how many times flights will stop between the origin and destination during the entire voyage.

10) Additional_Info:
We shall learn about eating, the types of food, and other facilities in this column.

11) Price:
The cost of the flight for the entire voyage, including all charges before boarding.

Data Analysis Report

Introduction

This data analysis report is based on a dataset containing information about airline journeys. The dataset includes various features such as the date of the journey, source, destination, route, departure time, arrival time, duration, total stops, and additional information. The dataset consists of 10,683 records.

Data Summary

Here is a summary of the key statistics and characteristics of the dataset:

Total Records: 10,683
Features:
Date_of_Journey
Source
Destination
Route
Dep_Time (Departure Time)
Arrival_Time
Duration
Total_Stops
Additional_Info
Unique Values
Date_of_Journey: 12 unique dates
Source: 44 unique sources
Destination: 5 unique destinations
Route: 6 unique routes
Dep_Time: 128 unique departure times
Arrival_Time: 222 unique arrival times
Duration: 1,343 unique durations
Total_Stops: 5 unique values
Additional_Info: 10 unique additional information
Most Common Values
Airline: The most common airline is "Jet Airways" with 3,849 occurrences.
Date_of_Journey: The most common journey date is "18/05/2019" with 504 occurrences.
Source: The most common source is "Delhi" with 4,537 occurrences.
Destination: The most common destination is "Cochin" with 4,537 occurrences.
Route: The most common route is "DEL → BOM → COK" with 2,376 occurrences.
Dep_Time: The most common departure time is "18:55" with 233 occurrences.
Arrival_Time: The most common arrival time is "19:00" with 423 occurrences.
Duration: The most common duration is "2h 50m" with 5,625 occurrences.
Total_Stops: The most common number of stops is "1 stop" with 8,345 occurrences.
Additional_Info: The most common additional information is "No info" with 8,345 occurrences.

Insights

Jet Airways: Jet Airways is the most frequently occurring airline in the dataset, indicating it is a popular choice among travelers.

Date Distribution: The dataset is skewed towards the date "18/05/2019," which may be due to the dataset collection process.

Source and Destination: The most common source and destination are "Delhi" and "Cochin," respectively. This suggests that Delhi to Cochin route may be a popular one.

Route: The most common route is "DEL → BOM → COK," indicating that this particular route is commonly taken by passengers.

Departure and Arrival Times: The dataset includes a wide range of departure and arrival times, which suggests flights are available throughout the day.

Duration: The most common duration is "2h 50m," indicating that this duration is typical for many flights in the dataset.

Total Stops: Most flights have "1 stop," which suggests that direct flights are the most common, followed by one-stop flights.

Additional Information: The "No info" category is prevalent in the dataset, suggesting that there is missing or unspecified information for a significant number of records.

Conclusion

This data analysis report provides an overview of the given airline journey dataset. It highlights the most common values for various features and provides insights into the dataset's characteristics. Further analysis, such as data cleaning and feature engineering, may be necessary for more in-depth analysis and modeling. Additionally, it's important to address missing or unspecified information in the dataset for more accurate analysis and predictions.
