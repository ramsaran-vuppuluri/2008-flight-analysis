# 2008 Airline & Airport Connectivity and Performance Analysis

## Author: Ram Saran Vuppuluri

### Story URL

Final Story URL - https://public.tableau.com/profile/ram.saran.vuppuluri#!/vizhome/Flight_2008_REL1_1/2008AirlineAirport

### Summary

In this tableau story line will analyze data gathered by RITZ for each commercial flight that has flown in 2008. Raw data utilized to generate this storyline is downloaded  __[from](http://stat-computing.org/dataexpo/2009/the-data.html)__ and was wrangled twice before generating final visualizations.

From the final visualizations we can deduce the following observations:
1. Frequency of flights:
    * Most number of flights are scheduled in the month of July,2008.
    * Least number of flights are scheduled in the month of November, 2008.
    * Most number of flights are scheduled on Wednesday.
    * Least number of flights are scheduled on Saturday
    * Atlanta and Chicago O’Hare took first 2 places in air traffic.
2. Taxi-Out of flights:
    * On average JetBlue airlines flights spent long time during Taxing-Out, suggesting the gates used by JetBlue airlines are farther from the runway i.e. operating from large and busy airports.
    * On average Aloha airlines flights spent least time during Taxing-Out, suggesting the gates used by Alohas are nearer to the runway i.e. operating from small and non-busy airports.
    * Pueblo Memorial Airport and JFK took first 2 places in average Taxing-Out time.
3. Delays:
    * Average amount of time by which each route is delayed due to Arrival delay.
    * Average amount of time by which each route is delayed due to Departure delay.
    * Average amount of time by which each route is delayed due to Carrier delay.
    * Average amount of time by which each route is delayed due to Aircraft delay.
    * Average amount of time by which each route is delayed due to National Airspace System (NAS) delay.
    * Average amount of time by which each route is delayed due to Security delay.
    * Average amount of time by which each route is delayed due to Weather delay.
4. Cancellations:
    * February has the greatest number of flight cancellation in 2008.
    * October has the least number of flight cancellations in 2008.
    * Chicago O’Hare has highest number of total cancellations in 2008.
5. Diversions:
    * December has the greatest number of flight diversions in 2008.
    * September has the least number of flight diversions in 2008.
    * Dallas Forth worth has highest number of total diversions in 2008.
    
__Note: Due to GIT file size limit (100 MB) raw data was not stored in the repository. Please download the raw file [2008.csv](http://stat-computing.org/dataexpo/2009/the-data.html) and run Wrangle_FlightData_2008_1.0 and Wrangle_FlightData_2008_1.1 to generate flights_2008_clean.csv utilized to generate the Tableau story line.__
    
### Design

In this story line following design decisions are made:
1.	Use colors that are compatible for Color-blindness.
2.	When visualizing place (airports) and routes geographical maps are utilized.
3.	When visualizing counts with fewer number of attributes heat maps are utilized.
4.	When visualizing counts with lot of attributes bar charts are utilized.

### Resources

* airports.csv – This file was downloaded from __[RITZ](http://stat-computing.org/dataexpo/2009/the-data.html)__ and is used as it is.
* cancellationCodes.csv – This file was manually created with various cancellation codes mentioned in description of __[RITZ](http://stat-computing.org/dataexpo/2009/the-data.html)__ 
* carriers.csv – This file was downloaded from __[RITZ](http://stat-computing.org/dataexpo/2009/the-data.html)__ and is used as it is.
* days.csv – This file was manually created as enumerator for weekdays (Monday to Sunday).
* flights_2008_clean.csv – 2008.csv downloaded from __[RITZ](http://stat-computing.org/dataexpo/2009/the-data.html)__ was wrangled twice (Wrangle_FlightData_2008_1.0 and Wrangle_FlightData_2008_1.1) to generate flights_2008_clean.csv.

Additional technical resources

* https://community.tableau.com/people/sarah.battersby.0/blog/2018/01/12/origin-destination-maps-or-flow-maps 
* https://www.youtube.com/watch?v=ckQNNhCfUW4&t=638s 
