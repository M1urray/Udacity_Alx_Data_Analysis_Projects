# (Dataset Exploration Title)
## by (your name here)


## Dataset

## Dataset Overview

> This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area.
The data set has been stored as a pandas dataframe, It has 16 columns and 183412 rows. The features cover 3 main areas: 
1. trip duration
2. station information
3. member information
### Dataset Dictionary:
1. duration_sec: Trip Duration (seconds)
2. start_time>: Start Time and Date
3. end_time: End Time and Date
4. start_station_id: Start Station ID
5. start_station_name: Start Station Name
6. start_station_latitude: Start Station Latitude
7. start_station_longitude: Start Station Longitude
8. end_station_id: End Station ID
9. end_station_name: End Station Name
10. end_station_latitude: End Station Latitude
11. end_station_longitude: End Station Longitude
12. bike_id: Bike ID
13. user_type: User Type (Subscriber or Customer – “Subscriber” = Member or “Customer” = Casual)
14. member_birth_year: Member Year of Birth
15. member_gender: Member Gender
16. bike_share_for_all_trip: Boolean to track members who are enrolled in the "Bike Share for All" program for low-income residents
## Investigation Overview

> The Goal of this presentation is to explore the main features of bike-sharing in the greater San Francisco Bay area. The main goal here is to specify the main determinants of trip duration by looking at the relationship between trip duration and other explanatory variables in the dataset. We try to answer the following questions:
1. What does the distribution of trip duration look like?
2. Which days have the highest demand on trips?
3. Which hours during the day have the highest demand on trips?
4. How trip duration differs by user age, hour, day, and user type?


## Summary of Findings

1. More than 90% of the users age below 50 years old and about 78% of users are in the age range from 20 years to 40 years old, so this system is very popular for youth which have a fitness to ride bikes
2. More than 90% of the trips are below 20 minutes.
3. The male users number is more than 3 times of the female users.
5. Most of the users are subscribed in this system (the number of subscribers are more than 9 times greater then those of customers)
6. The number of rides decreases greatly during the weekends (saterday and sunday) compared to the number of rides during the rest of days in the week.
7. The average trip duration during weekends (saturday and sunday) is longer than that during the rest of week the male users have the least trip duration in general , the average trip duration for all genders increased at hte weekend (saterday and sunday) which can be explained that the trips during the weekends are for entertainment where no need to hurry.
8. The subscribers users have the least trip duration in general , the average trip duration for both subscribers and customers increased at the weekend (saterday and sunday) especially the customers which can be explained that the trips during the weekends are for entertainment where no need to hurry


## Key Insights for Presentation

Used different visualizations to convey the distribution of age against duration and type of user against gender.