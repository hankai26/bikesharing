# Citi Bike-sharing Analysis
[link to dashboard](https://public.tableau.com/app/profile/hankai.zhu)

# Overview
This project is to prepare a proposal of a bike-sharing  program in Des Moines for investors. The Citi bike-sharing analysis is used to support the proposal using tableau visualizations. The data of Citi Bikes in August 2019 is used in this analysis.

Here we conducted these studies as followings.
- Convert the datatype for specific columns to datetime to prepare the data for visualization analysis, using Python and Pandas functions.
- Show the length of time that bikes are checked out for all riders and genders.
- Show the number of bike trips for all riders and genders for each hour of each day of the week.
- Show the number of bike trips for each type of user and gender for each day of the week.
- Indicate the August peak hour for rides.
- Indicate the top starting locations and ending locations for rides.

# Results
In this analysis we have several findings for investors to review.
1. The August Peak Hour chart indicates that most ride rentals occur around 5 - 7 pm.
![Peak Hour](https://github.com/hankai26/bikesharing/blob/main/Images/August%20Peak%20Hours.png)

2. Manhattan looks likes a popular location to start and end a bike rental. It's probably due to lots of tourists.
![start_loc](https://github.com/hankai26/bikesharing/blob/main/Images/Start%20Locations.png)

![end_loc](https://github.com/hankai26/bikesharing/blob/main/Images/End%20Locations.png)

3. Most checkout time would be within half hour. Most people rent bikes just for 10 mins. 
![Checkout_times](https://github.com/hankai26/bikesharing/blob/main/Images/Checkout%20Times%20by%20Hour.png)

Based on the gender for ride user, males sound like rent bikes more offen than females. However, the checkout duration looks same among males and females.
![Checkout_times_gender](https://github.com/hankai26/bikesharing/blob/main/Images/Checkout%20Times%20for%20Gender.png)


4. Most bikes were checked out around 5 - 7 pm. This is the busy period for the bike-sharing business.
![Trips_weekday_hour](https://github.com/hankai26/bikesharing/blob/main/Images/Trips%20by%20Weekday%20per%20hour.png)

Males always rent bikes more than females. But both males and females share a similar time pattern for bike checking out.
![Trips_gender](https://github.com/hankai26/bikesharing/blob/main/Images/Trips%20by%20Gender.png)

5. The trip user overview image shows a clear difference between different types of users. Annual subscribers and males are more like to rent bikes. 
![user_trips](https://github.com/hankai26/bikesharing/blob/main/Images/User%20Trips.png)