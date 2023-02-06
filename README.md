# Bikesharing with Citi Bike

## Overview of the analysis:

The purposes of this analysis is to research how the bike sharing service Citi Bike operates in New York City. Our data from the NYC Citi Bike business model includes trip duration, start times, stop times, start station IDs, start station latitude/longitude, end station latitude/longitude, bike IDs, user types, user birth years and user gender. Using this analysis we can create a proposal for a similar business in Des Moines, Iowa.

The first step will be changing the trip duration from an integer to a datetime value measured to the second. This can easily be accomplished using a pandas library in python utilizing the 'pd.read_csv', 'pd.datetime' and 'to_csv' functions. Next, we'll use the modified table to compare checkout times, gender comparisons, peak hours, subscriber base and most popular start and end destinations.  

## Results: 

The best way to understand the nature of the Citi Bike business, is to review the trends of customer usage. For instance, the length of time customers checkout the bikes they select.

![This is an image](https://github.com/aaron-ardell/bikesharing/blob/main/Checkout_User.png)

Then, when we add gender to the consideration for checkout times.

![This is an image](https://github.com/aaron-ardell/bikesharing/blob/main/Checkout_Gender_Line.png)

Another useful topic would be the most popular days and timeframes for the New York City Citi Bike customers to start and stop their trips. This will help further assess consumer behavior and rate of use. 

![This is an image](https://github.com/aaron-ardell/bikesharing/blob/main/Trips_WD_Hour_Heat.png)

Taking a slightly different perspective, focusing on the month of August with it's mild weather and tracking the average number of trips per hour of the day.

![This is an image](https://github.com/aaron-ardell/bikesharing/blob/main/August_Peak_Hours_Bar.png)

And when we add gender into the equation...

![This is an image](https://github.com/aaron-ardell/bikesharing/blob/main/Trips_Gender_WD_Hour_Heat.png)

An additional topic worth considering is the impact of subscriber users and how much of the NYC Citi Bike business is reliant upon them.

![This is an image](https://github.com/aaron-ardell/bikesharing/blob/main/Subscriber_Base_Pie.png)

![This is an image](https://github.com/aaron-ardell/bikesharing/blob/main/User_Trips_Gender_Heat.png)

A final perspective, the most popular starting and ending points for trips in the NYC Citi Bike program.

![This is an image](https://github.com/aaron-ardell/bikesharing/blob/main/NYC_Citi_Dashboard_Start_End.png)

Review the interactive web-based charts [HERE](https://public.tableau.com/app/profile/aaron.ardell/viz/bikesharing_16756204412070/Story1?publish=yes).

## Summary:

Upon review of the analysis, there are conclusions that we can make based on the data presented.
- While there were signifigantly more males than females and unknown participating in the NYC Citi Bike program, the length of trips and highest volume of bike usage between the genders correlated. 
- Most bike checkouts were within an hour, and the most popular times to take a bike trip were between 7a - 9a and 4p - 7p.
- The most popular starting points for trips correlate with the most popular ending points for trips.

For further analysis, looking into the age of NYC's Citi Bike users will help narrow down target audience for this type of program.

![This is an image](https://github.com/aaron-ardell/bikesharing/blob/main/Users_Birth_Year.png)

Another important lesson to learn from the NYC data is the location of their most popular starting points and their proximity to parks, boulevards and tourism areas.

![This is an image](https://github.com/aaron-ardell/bikesharing/blob/main/Most_Popular_Stations.png)

