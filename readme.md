# California Flights Dataset
## by Faisal AlDhuwayhi


## Dataset
The dataset includes information about flights of California state, of the year of 2019. Flights that are going into California or going outside of it. Including variables like destinations, arrival and departure delays, day of the week and day of the month, elapsed time and distance, and more other features.

I have performed some data wrangling steps to have more tidy structured data and make the data easier to interpret and understand:
- I have changed the type of the quarter of the year, day of the month and day of the week to categorical.
- I have split the origin and destination of the flight from the form (city, state) in one variable, to put them in two different variables.
- I have converted the format of the time from (hhmm) format, with bad recording to the entries, to the normal format (HH:MM:SS).

You can find the general dataset with more details from [here](https://www.transtats.bts.gov/DL_SelectFields.asp?Table_ID=).


## Summary of Findings
The last three days of the month have less traffic of flights throughout the year. While the other days show quite consistent. 

The weekend days have the least number of flights over the workdays.

The second and the third quarters of the year have the highest ratio of flights. With slight differences from other quarters.

June and December have more delays in their flights than the others.

The highest number of flights coming to California over the whole week from outside of it, is for the Los Angles city.

Mondays of the third quarter are the most traffic day over all the days of all the other quarters with a noticeable difference. And the opposite thing applied for Saturdays as the least traffic day for all quarters of the year.

There is a high correlation between the scheduled and the actual times, which is expected. But a more noticeable thing that there is no correlation between the day of the month of the flight and the other features.

February and December have the worst average departure time delay in general. Also, Fridays of February and Sundays of December have the highest average departure time delays compare to the whole days of all months.

For the first quarter, Mammoth lakes city appears to be the highest (worst) average arrival time delay for destination city of local flights. and the same thing applied to Bakersfield for the second and third quarters. And also San Luis Obispo for the fourth quarter.


## Key Insights for Presentation

San Jose city have the best average arrival time delay for destination city of local flights. 

It appears that Santa Maria city and Mammoth lakes have the least number flights coming to it over the whole week.

Tuesdays usually have the least average departure time delay between the other days over the months. Also, seems to be that October has the best average departure time delay generally.