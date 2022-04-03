# Analysis of NYC Citi Bikes
[link to dashboard](https://public.tableau.com/app/profile/rowena.quinn/viz/NYCCitiBikes_16490063899820/Story1?publish=yes)
## Overview
Investors in Des Moines, Iowa are interested in the potential of a possible bike sharing company located in their own city. They have asked to see an analysis on the popularity of an existing venture that would be similar to the one they would invest in.
### Purpose
Using Tableau, I will create multiple graphs visualizing the performance of a bike sharing company in NYC. Investors will be able to use these to make a prediction on how profitable a bike sharing company would be in their own city.
## Results
Citi Bikes, located in NYC, is an analogous business to the one being proposed to the investors. Using their data from August of 2019, we can begin to see the overall performance of their bikes which could inform us on how our own would behave. 
### Peak Performance Hours
![Peak_Hours.png](https://github.com/Lavernus/Bikesharing/blob/main/Images/Peak_Hours.png)

First, I made a bar graph of the number of bike trips that occured each hour for the entire month of August. This shows which hours were the busiest, which were 7 and 8 AM, and 5 and 6 PM. The hours with the least traffic were in the very early morning, between 1 and 5.
### Gender Breakdown
![Breakdown.png](https://github.com/Lavernus/Bikesharing/blob/main/Images/Breakdown.png)

The second graph is a simple pie chart showing the breakdown of genders riding the bikes. As one can see, the majority of the bike riders are male, with female bike riders accounting for around a quarter of the riders.
### Trip Duration
![Trip_Dur.png](https://github.com/Lavernus/Bikesharing/blob/main/Images/Trip_Dur.png)

The next graph was a line graph plotting the number of bike trips versus what time they ended at. This gives an idea of the average length of time most bike trips last, which was around 10 minutes.

![Gen_Dur.png](https://github.com/Lavernus/Bikesharing/blob/main/Images/Gen_Dur.png)

I then did a breakdown of this graph, separating the graph into three lines plotting each gender's checkout time separately. This gives an idea of the length of time each gender stays on the bike, which is overall similar.
### Trips by Weekday per Hour
Next was a series of heat maps showing the frequency of bike trips over a map of hours of the day for each day of the week.

![Weekday.png](https://github.com/Lavernus/Bikesharing/blob/main/Images/Weekday.png)

The first graph was an overview of all users, with darker colors appearing around rush hour times on week days and between 11 and 5 on weekends. 

![Week_Gen.png](https://github.com/Lavernus/Bikesharing/blob/main/Images/Week_Gen.png)

The next graph displayed three heatmaps showing the frequency of trips for each gender, with all of them following a similar pattern.

![Week_Type.png](https://github.com/Lavernus/Bikesharing/blob/main/Images/Week_Type.png)

The final graph displayed a heatmap not only across genders but across usertypes as well. This one was paired down to only show frequency of usage each weekday for each gender and usertype, which was customer and subscriber. It showed heaviest usage by subscribers, with their usage happening on weekdays. Customers, on the other hand, tended to use them on weekends more.
## Summary
The first area to focus on is peak usage periods. It is obvious that the most usage occurs during rush hours on weekdays, where people possibly use the bikes to commute to work or school. On weekends, however, they tend to be used during the active hours of the afternoon when many people would be using them on their days off for leisure activities. How long the bikes are used is important information as well, since most people only use the bikes for a short period of time. This means that most of the money made from a bike rental needs to be made within the first ten minutes. This could mean a higher price per minute for the first 15 minutes or a single fee at the beginning for a block of 20 minutes with the bike. 

The types of people using the bikes are interesting as well. More men tend to use them, but across the genders we can see that they all use them in the same way, with peak performance occuring on rush hours and afternoons on the weekends. Whether the user is a customer or a subscriber affects their usage as well. It makes sense that people using the bikes regularly for commuting to work or school would get a subscription to cut down on costs. Those using them as one off experiences would tend to use them on the weekends, which is their day off to try things and explore the city. 

### Additional Visuals
Additional visuals that could aid understanding this business model would be valuable. If we had the payment model of the bikes, we could graph how much money each bike made over the month of August using the frequency of their use and how much time they were used. This could be displayed in a bubble chart with each bike ID displaying how much money it made in the size of its bubble. This would be valuable in envisioning exactly how much money an individual bike could make and whether some bikes are costing more than they make.  

Another visual that could be informative would be the checkout times of users across usertypes. Knowing how long subscribers use the bikes compared to single use customers could influence how we price each usertype in order to offset wear costs and maximize profits.
