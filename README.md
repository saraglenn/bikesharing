# Bike Trip Analysis 

## Overview 

Tableau Public was used to create visualizations to show:

•	the length of time bikes are are checked out, then filtered by gender

•	the number of trips for riders and a breakdown of genders for each hour of each day of the week

•	the number of trips for each user a breakdown of genders for each day of the week

The Citi Bike System Data was downloaded from https://citibikenyc.com/system-data

Pandas was used to change the datatype of the tripduration oclum from an integer to a datetimes datatype, then exported as a csv. Tableau was then used to create the visualizations. 

## Conversion and DataFrame Creation

The data was manipulated in Jupyter Notebook to create a converted bikesharing dataframe. 

![bikesharing_df](https://github.com/saraglenn/bikesharing/assets/119461431/2d539a7a-1b8b-4b44-b142-ddcb5cc8f9a9)

## Visualizations via Tableau

Line graph displaying the number of bikes checked out by duration for all users. 
The duration of most trips is typically under one hour.
 
 ![Checkout_Times_for_Users](https://github.com/saraglenn/bikesharing/assets/119461431/463f8517-3e4e-4121-8c7f-bd21d4d4b90c)


Line graph displaying the number of bikes that are checked out by duration for each gender by the hour. Both male and female users exhibit similar trip duration patterns, with the majority of trips lasting less than one hour
 
 ![Checkout_Times_by_Gender](https://github.com/saraglenn/bikesharing/assets/119461431/2ba3b8e6-9261-43aa-bf41-209ce89eb40f)


Heatmap is created showing the number of bike trips for each hour of each day of the week. Peak usage is observed during weekdays, specifically during the morning rush hour between 8:00am - 9:00am and the evening rush hour between 5:00pm and 6:00pm. On weekends, usage patterns differ, with higher activity on Saturdays and Sundays between 11:00am and 4:00pm. The heat map indicates that overall usage is more consistent throughout the day on weekends, whereas weekdays show concentrated usage during typical work commuting hours.

![Trips_by_Weekday_PerHour](https://github.com/saraglenn/bikesharing/assets/119461431/555c9794-00a8-4956-bb24-320b57ffa18d)


Heatmap is created showing the number of bike trips by gender for each hour of each day of the week. The usage patterns and days of activity among different genders align with those observed in the overall rider population. While male riders outnumber female riders in general, resulting in higher overall usage, the distribution of usage across days and times remains consistent across genders.

![Trips_By_Gender](https://github.com/saraglenn/bikesharing/assets/119461431/5045184f-6c3f-41e3-80be-265d3042b456)


A heatmap is created showing the number of bike trips for each type of user and gender for each day of the week. Comparing customer usage to subscribers, it is evident that customers exhibit higher activity on weekends, suggesting that they are more likely tourists. On the other hand, subscribers display heavier usage throughout the week. When considering the weekday and hours visualizations, this pattern could be attributed to subscribers utilizing bikes for their work commutes.


![User_Trips_by_Gender](https://github.com/saraglenn/bikesharing/assets/119461431/747770f9-e874-4909-90c5-2a2f1c0223da)

