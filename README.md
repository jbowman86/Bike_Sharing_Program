# Bikesharing with NYC CitiBike data

## Overview

The aim of this project was to analyze bike-sharing data from CitiBike in New York City in preparation for a presentation to investors looking to begin a similar program in Des Moines, Iowa. These investors were primarily concerned with answering the following questions:

- Who uses bikeshare programs?
- What area of a city sees the most bikeshare usage?
- What time of day are bikes used the most and the least?
- How much are the bikes used and by whom?

The Tableau story for a New York bike-sharing program can be viewed via the following link:

LINK TO TABLEAU STORY

The code for conversion of tripduration and gender variables into understandable forms can be seen by clicking the link below:

CitiBike Code: [Link to Code](https://github.com/jbowman86/Bike_Sharing_Program/blob/b115cd6a194e53e2cb355f05b3027c4f48acf81f/NYC_CitiBike_Challenge.ipynb)

## Results

While citizens of Des Moines, Iowa may be different from the populace of New York City, a cursory understanding of the demographics of CitiBike riders may illuminate the investors on who are the user base for bike-sharing programs.  From the data collected, more than 3/4 of the users are classified as Subscribers (those who make regular use of the bikes and are a predictable source of income for the program).  Bikeshare program users were also predominantly male, at approximately 5/8 to only about 1/4 female. The remaining 1/8 gender was unknown or undeclared.

![](https://github.com/jbowman86/Bike_Sharing_Program/blob/be8fce428c4b8e4022c002ad7abf5cc1a634aba3/Images/NYC_Starting_Location.png)

The above map displays the bike stations from which recorded bike trips started. The size of the circles and darkness of the blue indicate the relative number of trips started at those locations. It is apparent that the majority of the bike trips originate in the commercial districts principally lower Manhattan.  Bike usage is lower in the less densely packed surrounding neighbourhoods. 

![](https://github.com/jbowman86/Bike_Sharing_Program/blob/be8fce428c4b8e4022c002ad7abf5cc1a634aba3/Images/NYC_Ending_Location.png)

The above map displays the bike stations from which recorded bike trips ended. The size of the circles and darkness of the red indicate the relative number of trips started at those locations. Similar to the starting locations, most bike rides ended in commercial districts and bike usage was lower in areas with less densely populated areas.  

![](https://github.com/jbowman86/Bike_Sharing_Program/blob/ec964eb9723ea10f462aabe3b45768061943a633/Images/NYC_Peaki_Riding_Hours.png)

The bar graph displayed above depicts the number of bike rides started during each hour of the day, totalled across the entire month of August. We can see peak usage during evening rush hour (between 5-7 PM).  The time of lowest usage was between 2 AM and 5AM.  It is during this period of time that bike repairs and maintenance should be completed as it will have the lowest impact on user base satisfaction.

![](https://github.com/jbowman86/Bike_Sharing_Program/blob/ec964eb9723ea10f462aabe3b45768061943a633/Images/NYC_Bike_Repairs.png)

The stepped-level heatmap seen above can be used to determine which bikes get heavy usage and may be in need of repairs/maintenance.  This heatmap shows each individual bike in the program, sized, colored, and sorted by its degree of usage during the month.  Red dots indicate nikes that are classified as heavy use and most likely needing repairs or potential replacement.  Green dots display the bikes which are used less often and repairs can probably be delayed.

![](https://github.com/jbowman86/Bike_Sharing_Program/blob/ec964eb9723ea10f462aabe3b45768061943a633/Images/NYC_trip_duration.png)

The above line graph depicts the number of trips by duration.  Its shows that the vast majority of trips taken on CitiBike bikes are under an hour in length. More specifically, most trips are under a half-hour in length, with a steep drop in number of rides over an hour in length.

![](https://github.com/jbowman86/Bike_Sharing_Program/blob/ec964eb9723ea10f462aabe3b45768061943a633/Images/NYC_trip_duration_gender.png)


The line graph above depicts the number of trips by duration broken down by gender.  It was observed that the majority of bike-sharing users are male and take rides less than an hour.

![](https://github.com/jbowman86/Bike_Sharing_Program/blob/ec964eb9723ea10f462aabe3b45768061943a633/Images/NYC_peak_use_hours.png)

A heatmap showing weekly usage patterns is displayed above. Heaviest usage of the bike-sharing program was during weekday commute times.  Weekend usage was spread throughout the middle of the day.  Furthermore, the lowest usage time was in the early morning hours.  The low usage trend was observed for each day of the week. 

![](https://github.com/jbowman86/Bike_Sharing_Program/blob/ec964eb9723ea10f462aabe3b45768061943a633/Images/NYC_Trips_per_Weekday_Gender_per_Hour.png)

A heatmap displaying the usage of the bike-sharing program categorized by weekday and gender.  The heatmap findings were consistent with other analyses completed.  Males were shown to have greater usage of the program compared to females.  For both genders, the heaviest usage of the bike-sharing was during commuter times (between 7 AM to 9AM and between 5PM and 7PM) with weekdays having heavier usage than on weekends.  

![](https://github.com/jbowman86/Bike_Sharing_Program/blob/ec964eb9723ea10f462aabe3b45768061943a633/Images/NYC_trips_user_day_gender.png)

The heatmap depicted above further demonstrated that the majority of users of the bike-sharing program are male and that most users are program subscribers.  For clarification, the darker the shade of blue indicates greater utilization of the the bike-sharing program.

## Summary

In conclusion, bike-sharing programs are utilized more often in busy metropolitan areas.  The user base is made up mostly of male subscribers, providing regular income to the program. More outreach should be done to attract female riders, but male users seem to be a reliable market. Furthermore, main usage was demonstrated to be focused around morning and evening commute times.

Additional analyses that should be completed in order to gain further insight into the bike-sharing user base are:

- Complete analysis on trip starting and ending locations during morning and evening rush hour time-windows.  This can help display the flow of traffic between neighbourhoods at peak hours.
- Complete analysis of the average trip duration, by birth year and gender in order to explore if there was any difference in male, female or un-gendered riders as they age.




