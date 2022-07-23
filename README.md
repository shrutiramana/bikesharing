# bikesharing

## Overview of the Project

### Purpose 
To find bikesharing trends in NewYork City during August, for this purpose we will create worksheets, Dashboards and Stories using Tableau Public.Data is obtained for August 2019 from Citibike , a bike sharing company in NYC.

## Resources 
Data -  "201908-citibike-tripdata.csv.zip" from "https://s3.amazonaws.com/tripdata/index.html"
Software - Tableau Public 2021.2
Jupyter notebooks, Pandas.

[Link to Story](https://public.tableau.com/app/profile/shruti.ramana/viz/BikeSharingProject-NYCCitibank/Story1)

![image](https://user-images.githubusercontent.com/98556229/180587051-9c07e1b4-4ef4-40da-8824-c0dedcadc191.png)

"Starting and Ending locations for bikes"

The Image shows the starting and Ending location of the bike trips. As the story depicts , it is more popular in the urban areas of the city. The picture also shows the tooltip depicting the exact location name and the number of rides at the location.


"Checkout times for bikes based on all users and genders"
![image](https://user-images.githubusercontent.com/98556229/180587120-ffb406fd-30ec-4d49-b755-9549c5623de7.png)

The above chart shows the checkout time for all users and based on genders. The gender chart shows that there are fewer women compared to men who are using the bikes.


"Trips by weekday per hour"
![image](https://user-images.githubusercontent.com/98556229/180587216-e5e33a4d-314b-42aa-9ca4-2dbb136f5678.png) 

This shows a heat map of trips during weekday per hour , which shows the peak hours are morning around 7AM-9AM and evening 5PM -7PM.


"Trips by Gender (WeekDay per hour)".
![image](https://user-images.githubusercontent.com/98556229/180587329-654c9fd0-9980-4dc7-ad93-9b497ebd9582.png)


This is similar to above analysis but also includes the gender division , whihc shows how each gender took bike trips during the weekdays. The graph includes values for each cell.


"User trips by Gender by Weekday"

![image](https://user-images.githubusercontent.com/98556229/180587343-ed3c3190-2ca7-4662-b571-57ffa216b610.png)

This shows trips based on the Usertype - like if they are customers or regulars(subscribers) also divided based on the gender, the chart also shows the total gender division of how many are male , female and unkown. And also number of each user type.



"Peak Time , Maintainence Time and Repair Time"

![image](https://user-images.githubusercontent.com/98556229/180587392-58c94c2d-1eba-4401-8f14-b29349de0719.png)


This shows a dashboard with data including the peak hours of bike trips and least trip hours which can be used for maintainence repairs of bikes. It also shows a treemap with counts of bike ids with thier respective trip numbers.  


### Summary

1. The story data shows activity of the bike sharing service in New York for August 2019.
2. Majority of the rides were in the very busy Manhattan Island.
3. Majority usage is by male.
4. 7AM-9AM and evening 5PM -7PM are the peak hours , so could be infered that it could be a good way commute for people during office hours.

Additional analysis could be:

1. Comparing data for different months to determine trends across the year.
2. Including weather data , as it can affect the bike ride trends
   
