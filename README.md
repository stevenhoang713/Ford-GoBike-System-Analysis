# 🚴🏼 Ford GoBike System Data Exploration
![GoBike](https://github.com/stevenhoang713/Ford-GoBike-System-Analysis/assets/145725846/dc04b66c-04cb-497b-b0f2-a30f78ea1cd7)


## Dataset Overview 
The dataset contains 183,412 bike rides, each described by 16 features. The majority of variables in the dataset are numeric, while some variables such as start_time and end_time have incorrect data types and should be converted to datetime. Additionally, some variables such as start_station_id, start_station_name, end_station_id, end_station_name, member_birth_year, and member_gender have missing values. After cleaning up the dataset, the dataset contained 174,952 bike rides and 17 features for investigation.

## Summary of Findings
The data exploration revealed interesting patterns and insights about the bike-sharing service:
- Thursdays and Tuesdays are the busiest days for bike trips, while weekends have the least number of trips.

- The peak hours for bike trips are during the morning hours of 8 and 9, and the evening hours of 17 and 18.

- The age group between 20 to 60 years takes the highest duration trips.

- Male users dominate the bike service usage compared to females and other gender users.

- Subscribers take more trips than customers.

- Customer users take longer trips than subscribers, regardless of the day of the week.

- The average duration of bike trips is between 8 and 15 minutes, but on weekends, the trips are longer than on weekdays.

## Key Insights
The duration of the trip is a crucial aspect and is influenced by the following variables:
- Age: People in the age group of 20 to 60 tend to take the longest trips compared to other age groups.

- User type: Customers took longer trips compared to subscribers across all days of the week and hours of the day.

- Day of the week: Longer trips are taken on weekends compared to weekdays.
