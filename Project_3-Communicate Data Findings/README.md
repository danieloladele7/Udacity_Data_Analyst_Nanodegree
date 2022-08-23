# (Ford Gobike Data Exploration)
## by (Daniel A. Oladele)


## Dataset

This project is divided into two major parts. In the first part, I conducted an exploratory data analysis on a dataset Ford GoBike System Data. I used Python data science and data visualization libraries to explore the dataset’s variables and understand the data’s structure, oddities, patterns and relationships. The analysis in this part progressed from simple univariate relationships to multivariate relationships.

In the second part, I present my main findings from my exploration and convey them to others through an explanatory analysis. To this end, I will create a slide deck that leverages polished, explanatory visualizations to communicate my results.

This document explores a dataset containing the trip data of the ford gobike approximately 183,412 with 16 features (duration_sec, start_time, end_time, start_station_id, start_station_name, start_station_latitude, start_station_longitude, end_station_id, end_station_name, end_station_latitude ,end_station_longitude, bike_id, user_type, member_birth_year, member_gender, bike_share_for_all_trip).

**After cleaning we have the following data structure and features:**
- Structure (174758 x 16)
- Features:
    - Trip Duration (seconds and in minutes)
    - Start/end weekday
    - Start/end hour
    - Start/end Station ID
    - Start/end Station Name
    - Trip distance in miles
    - Bike ID
    - User Type
    - Member's age 
    - bike_share_for_all_trip and
    - Member's Gender

## Summary of Findings

1. Tuesdays and Thursday seem to be the most popular days for using the bike sharing system, however Wednesday, Mondays and Fridays are very close to the Tues/Weds numbers. The usage drops significantly on Saturdays and Sundays suggesting the Ford bike share system is primarily used during working days.
2. Bikes usage hours shows the most numbers between the hours of 8-9am and 5-6pm, which reflects the typical work day in the US.
3. The percentiles and plot shows that most rides falls between 3 and 12 minutes, therefore most riders tahe bikes for short distance. This is also visible in the Distance plots.
4. Generally, Over 80% of members involved in the trip were subscribers.
5. Overall, the average ages of users were about 35, with subscribers ages a slightly higher upper quartile (75%).
6. Overall, the average trip duration for customers was much higher than that of subscribers, and customers spent longer time on trips.
7. Ages of between 22 and 65 were fairly consistent with a distance of 3-4 miles.
8. Interestingly, females on average spent more time on trips and covered more distance.
9. no customer shared bikes on trips,
10. Average ages of users not sharing bikes through out all trips was more than those sharing.
11. There was a correlation between duration of trips and distance covered.
12. All bike sharing users were subscribers.


## Key Insights for Presentation

1. Distribution of Trip Durations: Was between 3 - 12 mins with customer having the highest average of about 11 mins and subscribers less than 10 mins.
2. Distribution of days and hours: Most active days were weekdays and Most active hours were an hour before or after a typical working day.
3. Distribution of User Age: Age the distribution was most concentrated between 22 to 45 years old.
4. Interestingly, females on average spent more time on trips and covered more distance.
5. No customer shared bikes on trips.
6. There was a correlation between duration of trips and distance covered.