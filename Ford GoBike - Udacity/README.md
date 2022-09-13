# Ford GoBike Data Exploration

## Dataset

Ford GoBike System Dataset includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area in the month of February, 2019.  
This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area in the year 2019. The data set has been stored as a csv file, it has 16 features and 183412 entries. The features are:
- duration_sec - Ridden time in sec
- start_time - Ride start time
- end_time - Ride end time
- start_station_id - Ride start station id
- start_station_name - Ride start station name
- start_station_latitude - Ride start station location in latitude
- start_station_longitude - Ride start station location in longitude
- end_station_id - Ride end station id
- end_station_name - Ride end station name
- end_station_latitude - Ride end station location in latitude
- end_station_longitude - Ride end station location in longitude
- bike_id - Ride bike id
- user_type - User type either Subscriber or Customer
- member_birth_year - Member birth year
- member_gender - Member gender
- bike_share_for_all_trip
  
The dataset can be found [here](https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv).


## Summary of Findings

In the exploration, I found that there was a large number of bike riders are subscribers.
The bike usage during the rush hours is high not only for subscribers but also for customers.
But for a long last rides customers use bikes more often than subscribers.

Outside of the main variables of interest, I verified the number of Male riders is much higher than Other 
Gender types that inturn increase the ratio of usage by a high range.  
I also explored the distribution of age along with ride duration, interestingly I found out that they 
have inverse relationship.


## Key Insights for Presentation

For the presentation, I focus on just visualising the user type usage. 
I start my presentation by showing what is the ratio of user types looks like, 
then I will talk about the ride duration distribution for each user type, 
followed by hourly usage distribution, and finally I will plot the 
graph showing the weekdays along with hourly distribution of each user type.

To visualize the ratio of user types I use a pie chart, a histogram chart to show the distribution 
of ride duration, a bar chart to visualize the hourly distribution of usage for each user type, and finally 
I used heatmap to show the relationship between user type, hourly, and weekday distribution.
