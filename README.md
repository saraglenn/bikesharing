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

## Visualizations 

 Line graph displaying the number of bikes checked out by duration for all users
 
 ![Checkout_Times_for_Users](https://github.com/saraglenn/bikesharing/assets/119461431/463f8517-3e4e-4121-8c7f-bd21d4d4b90c)


 Line graph displaying the number of bikes that are checked out by duration for each gender by the hour
 
 ![Checkout_Times_by_Gender](https://github.com/saraglenn/bikesharing/assets/119461431/2ba3b8e6-9261-43aa-bf41-209ce89eb40f)


Heatmap is created showing the number of bike trips for each hour of each day of the week

![Trips_by_Weekday_PerHour](https://github.com/saraglenn/bikesharing/assets/119461431/555c9794-00a8-4956-bb24-320b57ffa18d)


Heatmap is created showing the number of bike trips by gender for each hour of each day of the week

![Trips_By_Gender](https://github.com/saraglenn/bikesharing/assets/119461431/5045184f-6c3f-41e3-80be-265d3042b456)


A heatmap is created showing the number of bike trips for each type of user and gender for each day of the week

![User_Trips_by_Gender](https://github.com/saraglenn/bikesharing/assets/119461431/747770f9-e874-4909-90c5-2a2f1c0223da)

