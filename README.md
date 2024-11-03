# Citi Bike


## Project Description

In this assignment, I have created visualizations, dashboards and a story using Tableau for the [New York Citi Bike Program](https://en.wikipedia.org/wiki/Citi_Bike). CitiBike is the largest bike-sharing program in the United States.

Since 2013, the Citi Bike program has implemented a robust infrastructure for collecting data on the program's utilization. Each month, bike data is collected, organized, and made public on their [webpage](https://www.citibikenyc.com/system-data).

This Tableau dashboard is created with the purpose to establish a sophisticated reporting process. The set of visualizations are aimed to provide data reports to the city officials.


## Data Used:

I have used the Jersey City data only for the full year 2023. I used Jupyter Notebook to concatonate the 12 data files for the year 2023 for Jersey City and stored the combined & cleaned dataframe as a CSV file.


## Key Insights

Following are some key insights from the analysis performed for the year 2023 for Jersey City:
   
- Classic bikes are the most popular ride types used equally higher among casual riders as well as member riders. 86.36 % of the total rides was Classic Bike for the year 2023. Their usage fluctuates over the year but that coincides with the change in number of trips taken across different months of the year. Electric bikes are also gaining popularity but their usage is lesser than the classic bikes.

- Average trip Duration is 10.60 mins. The average trip durations are higher during the Summer months. This correlates with the higher number of trips taken during those months. Busiest station Grove St PATH has average trip duration of 8.5 mins. 

- Riders seem to enjoy longer rides during weekends and this trend is consistent across all months of the year. On Sundays average trip duration is 13.99 mins.

- The average trip durations are higher in early morning hours (8 am ) and evening hours (5-6 pm) during the weekdays. This can imply that many riders use the Citi Bikes to commute to and from their work. 

- During the weekends, the average trip durations remain higher through out the day which might imply that riders use the bikes for pleasure rides over the weekends.

- Avarage trip distance is 0.7226 miles. Summer 2023 has the longest trip distance travelled, a total of 230,668 miles have been ridden.  

- Casual riders take longer trip likely due to the lower per-trip cost for members. 


## Questions to Answer:

* How many trips have been recorded in total during the chosen period?<br>
**985,519** 

* What are the peak hours when bikes are used during the summer months?<br>
**5-6 pm.**

* What are the peak hours when bikes are used during the winter months?<br>
**5-6 pm.**

* Today, what are the top 10 stations in the city for starting a journey? Based on data, why do you hypothesize these are the top locations?<br>

        **1. Grove St PATH**<br>
        **2. Hoboken Terminal - River St & Hudson Pl**<br>
        **3. South Waterfront Walkway - Sinatra Dr & 1 St**<br>
        **4. Hoboken Terminal - Hudson St & Hudson Pl**<br>
        **5. City Hall - Washington St & 1 St**<br>
        **6. Newport PATH**<br>
        **7. Hamilton Park**<br>
        **8. Newport Pkwy**<br>
        **9. Bergen Ave & Sip Ave**<br>
        **10. 11 St & Washington St** <br>

* How does the average trip duration change by the type of user? <br>
**Casual - 16.47 mins**
**Member - 8.55  mins**

* What is the average distance in miles for a bike trip?<br>
**0.7226 Miles**


## Visualizations:

I have created multiple visualizations to answer different questions stated above. They are mainly three different types - 

### 1. Ride: 
Total number of rides, ride types and their count by Months, ride types used by members vs. casual riders,  number of rides taken by members vs. casual riders, riders across different months of the year

### 2. Trip Duration
Compute the average trip duration for 2023 in Jersey City, average trip duration with the number of rides, average trip durations across different months of the year, average trip duration taken over different days of the week, average trip duration taken by members vs. casual riders, average trip duration by season, heatmap to show the average trip duration for different hours of the day.

### 3. Trip Distaance
Compute the average trip distance for 2023 in Jersey City, total trip distance by season. 


##  Dashboards:
I have created two dashboards:

### Dashboard - Rides

The dashboard for rides compares Ride types and their traffic across different months. The dashboard also attempts to compare the different ride types used among members vs. casual riders.

Following are key findings from this dashboard:

Ride Type:

* Classic bikes are the most popular rides throughout the year (65.32% members/ 21.04% casual riders of all rides).
* Electric bikes are also frequently used (8.78% members/ 4.65% casual riders of all rides).

Ride Traffic:

* Winter months of December, January, February and March have lesser than average traffic for all ride types and among both member and casual riders.
* Summer and early Fall months of May, June, July, August and September have higher than average traffic for all ride types and among both member and casual riders.

### Dashboard - Average Trip Duration

The dashboard for average trip duration compares the length of the trips across different months of the year, weekdays and across different hours of the day.

Following are key findings from this dashboard:

Average Trip Duration - Monthly Trend:

* The overall average trip duration for the year 2023 is 10.60 minutes.
* Summer months tend to have higher trip durations.

Average Trip Duration - Weekday Trend:

* Weekends are clearly the most popular days where riders tend to take trips for higher duration.

Average Trip Duration - Hourly Trend:

* During weekdays, riders tend to have longer trips during early morning hours (8 am) and evening hours (5-6 pm) which coincides with most commute to work hours.
* The average trip duration during the weekends is longer through out the day.


## Create a Map

In this step, I created a dynamic map which shows how each Start and End Station popularity changes over time (by adding a filter for Month). The map has Zip Code Boundaries and Zip Code Number data overlaid on the map. I have also added a layer for 2018 Median Household Income to the map. There are two maps created - one to show the Start Stations data and the second for the End Stations data.

I have also created two bar charts to show the top 10 Stations used to Start and End the rides. 

I have then created a dashbaord displaying the two maps showing the Start and End Stations with filters added to analyze the most popular stations for each month.

**Following are key findings from this dashboard:**

The top 10 stations for starting and ending and trip are almost (9 out of top 10) the same locations in Jersey City. The top 3 stations are: 
1. Grove St PATH ( 16.88% of total ride for starting a trip)
2. Hoboken Terminal - River St & Hudson Pl ( 15.68% of total ride for starting a trip)
3. South Waterfront Walkway - Sinatra Dr & 1 St ( 11.22% of total ride for starting a trip)


## Create a Story

Finally, I have created a story on Tableau which is a presentation of all the visulizations created in the previous steps. The header of the story outlines a brief analysis derived out of the visualizations.