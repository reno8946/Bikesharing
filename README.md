# Bikesharing

## 1. Overview

Citibike runs a bikesharing service in New York City. They are looking to expand the services in other cities around the country and found an angel investor in Des Moines, IA.

The bikesharing project is to analyze New York City CITI Bike data from **August 2019** and then create a proposal on how it may work in Des Moines, IA.

**Tableau Public 2020.3 is used to import, style and portray data accurately using worksheets, dashboards, and stories.**

## 2. Results

The tableau stories can be found at:

[Link to the Bike Utilization+Duration Story](https://public.tableau.com/profile/reno.stephens#!/vizhome/NYCCITIBikeAvgTripDuration/BikeUtilizationDurationStory)

[Link to the NYC CITI Bike Story](https://public.tableau.com/profile/reno.stephens#!/vizhome/NYCCITIBikeStory/NYCCITIBikeStory)

The tableau dashboard can be found at:

[Link to the User Bike Data Dashboard](https://public.tableau.com/profile/reno.stephens#!/vizhome/UserBikeDataDashboard/UserBikeDataDashboard)

### 2.1. Bike Utilization:
We start the analysis by looking at bike utilization.

From the data, it looks like bike utilization by bikeID in NYC was quite random and didn't follow any consistent pattern. 

![image](https://user-images.githubusercontent.com/70483866/102005793-5d90a200-3ce1-11eb-8c87-264ff2339137.png)

### 2.2. Average Trip Duration:
Next, the analysis looked into at average trip duration.

According to the data, there was a huge spike in average trip duration among people born in the very early 1890s, however a consistent increase in average trip duration started to take place from people born in the 1930s and onwards.

![image](https://user-images.githubusercontent.com/70483866/102005908-34bcdc80-3ce2-11eb-845a-70867ef59bce.png)

### 2.3. Usage Pattern by Hour

Looking at the hourly data for each day of week further confirms that 5-7 PM peak hours is consistent through out the week. It is also observed that Monday through Friday, bikes usage is high during hours of 8-10 AM. 

On Saturdays and Sundays the bikes are used throughout the day. 

It is also interesting to observe that on Thursday, in spite of being a working day, the bike usage during hours of 5 - 7PM is higher.

![](images/trips_by_weekday_for_each_hour.png)

### 2.4. Bike Checkout Times
The following charts show the bike check out times for Overall users and broken down by gender.
![](images/checkout_times_for_user.png)

![](images/checkout_times_by_gender.png)

The first chart show that typically the bikes are checked out for 4-6 hours. 

From the second chart, it can be determined that both male and female users have the same checkout pattern.

### 2.5. Bike usage by Gender by Weekday
The following heat map confirms the fact the men and women have same pattern of bike usage through out the week.
![](images/trips_by_gender_weekday_per_hour.png)


### 2.6. Bike usage by User type by Weekday
The following heatmap depicts the bike usage throughout the week for each user type broken down by gender.

Based on the chart below, one can determine that male subscribers are the largest users of the bikes. For Customer user type, there is not much difference in the usage pattern between men and women.

![](images/user_trips_by_gender_by_weekday.png)

