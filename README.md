# Bikesharing

## Overview
### Purpose
After the trip of a lifetime to New York City with my best friend Kate we realized that the trip was only so perfect because we used CitiBikes to get everywhere we needed, allowing us to truly see the city and interact with locals. If the bike share business works so well in NYC, why can’t it be just as successful in our hometown of Des Moines, Iowa? This thought led us to create an analysis to determine if it is in fact feasible. While we found a potential investor to provide funding we still need to figure out the mechanics behind making the bike share business work.

Luckily CitiBike is kind enough to provide the public with downloadable files of trip histories. For our analysis we will be sifting through a CSV file containing all data from August 2019 because there is typically more traffic during the summer months. Tableau will be our tool of choice to help tell the story of this data set. We will create our visualizations by populating the columns, rows, filters, and marks boxes in Tableau with different data points from the CSV file. Afterwards, we will determine if the bike share business is sustainable and if it would be successful in Des Moines. 

## Results
### Visualizations
#### ***Checkout Time for Users***
Based on the visualization we can see that trip duration rarely, if ever, exceeded an hour. The majority of trips appear to be between a 5–10-minute mark meaning individuals are utilizing the bike service most likely just to run a quick errand or they just don’t feel like walking the distance. 

![time.png](https://github.com/CristinaCod/bikesharing/blob/main/Visualizations/Bike%20Trip%20Analysis.png)
#### ***Checkout Time by Gender***
Building off the above visualization we can also break down trip duration based on gender. Males, outlined in orange, appear to take the most trips while still falling into that average 5-10-minute time frame. Below them women, outlined in blue, take far fewer trips but again stay in the average time frame as well. And lastly, we have unknown gender, outlined in red, with the fewest trips but they appear to average and plateau between 10-30-minute trips. 

![gender_time.png](https://github.com/CristinaCod/bikesharing/blob/main/Visualizations/Bike%20Trip%20Analysis-2.png)
#### ***Trips by Weekday per Hour***
We can also examine the most popular hours the bike share is used during the week. From the visualization we can see the 7am-9am time frame appears very popular with the most activity around 8am and again we see a peak in usage between 5 and 6pm. Monday, Tuesday, and Thursday also appear to be the busiest days during these time frames. The most logical explanation for this is that individuals are utilizing the bike share for their commutes to and from work opposed to walking or taking a bus, subway, cab, or any other mode of public transportation. 

![weekday_hour.png](https://github.com/CristinaCod/bikesharing/blob/main/Visualizations/Bike%20Trip%20Analysis-3.png)
#### ***Trips by Gender (Weekday per Hour)***
Just like with trip duration we can also examine most popular checkout hours based on gender as well. We can see from the visualization, while slightly cut off, that the 8am, 5pm, and 6pm times are still most popular but again men appear to be utilizing the service more than women. 

![gender_hour.png](https://github.com/CristinaCod/bikesharing/blob/main/Visualizations/Bike%20Trip%20Analysis-4.png)
#### ***User Trips by Gender by Weekday***
Building on the last two visualizations we can also determine popularity based on user type meaning are these individuals subscribers to the service or are they just one-time customers. The good news for us is that the current visualization shows the majority of these users are in fact subscribers (and male) meaning we have a constant user base. 

![gender_weekday.png](https://github.com/CristinaCod/bikesharing/blob/main/Visualizations/Bike%20Trip%20Analysis-5.png)
#### ***Gender Breakdown***
Based on the visualization we can see that Males, colored in orange, are the majority users with just over 1.5 million. Women, in blue, on the other hand rank in with about a million less than their counterparts at 588,431. The rest of the pie chart represents unknown gender with the color red at just about a quarter million.

![gender.png](https://github.com/CristinaCod/bikesharing/blob/main/Visualizations/Bike%20Trip%20Analysis-6.png)
#### ***Top Starting and Ending Locations***
Based on the two visualizations it appears that the top starting and end locations are very close if not the exact same spots. This shows that the original marketing team did a great job at determining areas with a lot of foot traffic that would lead to the most popular spots to place bike share locations. 

![stop_start.png](https://github.com/CristinaCod/bikesharing/blob/main/Visualizations/Bike%20Trip%20Analysis-7.png)

A Tableau story of all the visualizations can be found at:
[Bike Trip Analysis](https://public.tableau.com/app/profile/cristina.codispoti/viz/BikeTripAnalysis_16474718483720/BikeTripAnalysis)

## Summary
### Findings
Based on all the above visualizations and analysis of them it becomes apparent that the bike share is successful and profitable in New York City and therefore with the right tactics and implementation it could also be successful in Des Moines if properly targeted to that audience. We know for a fact males are the most active users and it is typically for their mornin commute. As long as those parameters match that in Iowa there is no reason this bike share can't also be successful there as well. 
### Suggestions
To aid in solidifying the proposal to potential stakeholders I would recommend creating a visualization with a breakdown of the age of users based on the ‘birth year’ data point given in the csv file. We could create 10-year ranges to figure out who the main audience is that is utilizing this service and then find ways to target advertisements toward them specifically to hopefully grow our numbers and entice new clients. 

Another potential visualization we could create to bolster the pitch would be to calculate the average distance between bike stations to determine if they are too far apart and if we need to implement more or if we have to many and can reduce the number to save money or if it’s just the right amount. 
