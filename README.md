# Citi Bike Analysis
## Overview and Purpose of Analysis
The purpose of this analysis is to determine feasability for opening a Citi Bike operation in Des Moines Iowa.  
To accomplish the analysis data from the New York operations were analyzed for the month of August.  August should be close to a peak month and can provide insight regarding usage volumes and customer preferences.
Specifically the analysis will look at:
-  Number of rides 
-  Volume of rides by gender
-  Volume of rides by Customer Type
-  Duration of rides in total and by gender
-  Usage by hour of day and day of week in total and by gender
-  Hours of most utiliztion 
-  Volume of where trips are started and completed

## Results of Analysis
The summary results of the August data can be seen in the figure below.

<img src="Summary_statistics.png" alt="Summary Statistics" >

The total number of rides for August was 2.3M.  Most of the rides, 65% or 1.5M, were taken by Men.  Over 85% of the rides were taken by "Subscriber" customer type.  Most of the "Unknown" gender were of customer type "Customer".  The intial conclusions from these visuals are that Men represent the vast majority of the riders in August and they are regular subscribers to the Citi Bike service.

<img src="trip_durations.png">
 
 The next part of the analysis was to exmaine duration of trips overall and by gender.  The visuals above, show both sets of data.  The trip duration overall shows that most of the trips are less than forty minutes in length.  The most frequent durations are all less than twenty minutes and centered about ten minutes in length.
  The trip durations by gender are similar in behavior to the totals for men and women.  On average men have some longer trips than women.  The "Unknown" gender which are mostly "Customer" type users, have more uniform trip times between approximately  five and thirty minutes.
  
<img src="Bike_utilization.png">  

There were two blocks of high usage hours, rush hours, in August.  The first was in the morning from 7-10am, and the second was in the afternoon from 4-8pm.  These two blocks of usage time accounted for 50% of the rides in August.  Another observation from this visual is that between 2-6am is a window to perform maintenance and reposition bikes as needed.  Repositioning may be needed if the inventory is shifted due to trip start and ending locations shown in a later visual.

<img src="Starttime_by_Dayhour.png">

The above visual presents the start time of trips by day of week and hour of the day.  This graphic reinforces the prior visual showing the high usage or rush hours during the day.  The rush hours only occur during the working week of Monday to Friday.  Weekend days, Saturday and Sunday, the usage is spread more evenly through the day starting in late morning until late afternoon.  We can also see that Wednesday usage is lighter than other week days whereas Thursday afternoon rush hour is the heaviest usage.

<img src="Gender_stoptime_dayhour.png">    

The visual above represents usage by day of week and hour of the day for Men, Women and "Unknown" genders.  We can see again that Men are the drivers in usage and their usage patterns are representative of the larger usage distribution.  The usage by Women is consistent with the overall pattern also but with less volume.  The "Unkown" gender usage which is comprised of customer type "Customer" is more uniform throughout the week and then increases on Saturday.

<img src="dayuse_gender_day.png">

The image of Customer Type daily usage by gender is represented above.  This graphic just reinforces the prior analysis.  Subscriber men are the drivers of usage through out the week. While female users follow a similar pattern with lower volume.  

<img src="startstop_loctions.png">
          
The two visuals above show the concentration of trip origins and terminations.  Most of the bike usage is located Manhattan.            

## Summary

It is clear from the data that "Subscribers" account for most of the volume in August and most riders are "Male".  The average trip duration is around ten minutes and very few are longer than forty minutes.  The trip duration time is heavily skewed to shorter trips.  There are two rush hour periods from Monday to Friday between 7-10am and 4-8pm.  Usage on the weekend is lighter and more uniform than during the week. Supporting analysis shows that the usage data is driven by "Male" riders.  When reviewing the starting and stopping locations in Tableau, there are a relatively few number of locations that have significant volume. 

Additional analysis to support a launch plan for Des Moines would be:
- Exmaine the same data for a low volume month such as January or February
- Review bike inventory in detail to see if there are bikes that don't get used
- Deeper look at location usage data to determine if there are potential shortages in areas thus losing revenue from rides




All of the visuals as part of a Tableau Story can be seen at the following links:

[This a link to Summary Story](https://public.tableau.com/app/profile/bill.remy/viz/Mod14Challenge_16557427414530/CitiBikeOverview?publish=yes)


[This is a link to the Usage Story](https://public.tableau.com/app/profile/bill.remy/viz/Mod14Challenge_16557427414530/CitiBikeUsage?publish=yes)
