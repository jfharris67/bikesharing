# Bikesharing

## Overview
Project to convince investors that a bike-sharing program would succeed in Des Moines.
One of the stakeholders would like to see an analysis based on data from Citi Bikesharing in New York City.

- Show the length of time that bikes are checked out for all riders and genders
- Show the number of bike trips for all riders and genders for each hour of each day of the week
- Show the number of bike trips for each type of user and gender for each day of the week.

## Results

### Checkout Times for Users
<img width="1901" alt="Checkout_by-user" src="https://user-images.githubusercontent.com/114355199/226145286-b79e68cf-c7c5-4fbc-9946-8075d0b27980.png">
The image above shows that users' most popular checkout time is 5 minutes. 146,752 riders. Most rides are completed within 30 minutes.


### Checkout Times by Gender
<img width="1882" alt="Checkout_by_gender" src="https://user-images.githubusercontent.com/114355199/226145417-9d2c887b-e71a-4ea2-84e8-22c67752fd04.png">
The image above shows checkout times by gender. Males' most common checkout time is 5 minutes, while female's is 6 minutes.


### Trips by Weekday for Each Hour
<img width="549" alt="Trips_by_weekday" src="https://user-images.githubusercontent.com/114355199/226145515-9611fe83-3ccf-4f3f-b2af-7b1bf6fd2d5c.png">
This image shows the most popular usage times are at 8:00 AM and between 5:00 PM and 6:00PM, Monday to Friday. Thursday is the most popular day. It is very common for users to use the service for commuting to and from work.


### Trips by Gender (Weekday per Hour)
<img width="1368" alt="Trips_by_Gender_weekday" src="https://user-images.githubusercontent.com/114355199/226145747-0f64151f-0d5e-4ddc-afd3-cd814fe15870.png">
The image above shows similar results. When split out by gender, male usage tends to be significantly higher than female.  


### User Trips by Gender by Weekday
<img width="646" alt="Trips_by_Gender_by_weekday" src="https://user-images.githubusercontent.com/114355199/226145843-bbf19d3e-c205-42d5-a973-39519ddd9e7e.png">
The image below shows subscribers are the most popular service users, especially on weekdays. This study tells us that the service is very popular for residential users. The usertype customer is most likely tourists using the bikes to check out points of interest throughout the city.

### Top Starting Locations
<img width="1258" alt="Top_starting_locations" src="https://user-images.githubusercontent.com/114355199/226146197-d9d2dbe5-5f32-425e-8170-9bbfa7274ded.png">
This image shows the top starting locations. Obviously, the central business district is showing the highest usage. Higher starting locations are shown as a darker and larger blue circle.

### Top Ending Locations
<img width="1315" alt="top_ending_locations" src="https://user-images.githubusercontent.com/114355199/226146273-c0682b03-65bd-4964-9df8-6f7749aba837.png">
Like top starting locations, the central business district shows similar ending locations. Higher ending locations are shown as a darker and larger orange circle.

## Summary

### Target Demographics
- The service is more famous for the male population. This could indicate a target audience for marketing and advertising.  
- People like using the service for their commute to work. Do people in Des Moines typically live close to work? Manhattan is densely populated by residential and businesses. We need to consider this. While using the service for commuting to work may be prevalent in New York, the same may not be accurate for Des Moines.  
- Tourists use the service more on weekends. However, there is a slight difference on weekdays.

### Additional Recommended Analysis
- It would be advantageous to see what age groups use the service. We have the birth year in the data. We could subtract the birth year from 2019 to get age estimates of the users. This study would help establish age targets for advertising campaigns etc.
- It would also be valuable to see how many rides are occurring per bike per day, looking at the number of rides per bikeid. This would help establish, in part, an ROI for the cost of the bike itself. We also need to figure out the cost of maintenance for the bikes, for example cost per trip duration.
