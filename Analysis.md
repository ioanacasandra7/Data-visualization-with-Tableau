# Data-visualization-with-Tableau

# Citi Bike Analytics

[Link to Tableau Public Profile](https://public.tableau.com/profile/ioana3081#!/)

### Overview

David Fried from the Tue/Thu class and I collaborated on this assignment.

We gathered bike data from Summer 2019 and Summer 2020 Citi Bike Trip History Logs, and analyzed the data with Tableau. Several visualizations, two dashboards, and a Story were produced with Tableau Public.

##### Data Munging

Prior to analysis with Tableau, we used Pandas in JupyterLab to create one big CSV from eight CSV files of bike data:

*  201906-citibike-tripdata.csv
*  201907-citibike-tripdata.csv
*  201908-citibike-tripdata.csv
*  201909-citibike-tripdata.csv
*  202006-citibike-tripdata.csv
*  202007-citibike-tripdata.csv
*  202008-citibike-tripdata.csv
*  202009-citibike-tripdata.csv

##### Outliers 
We used filters in Tableau to exclude bad data or outliers from the visualizations (e.g., individuals who claim they are 100+ years old). 

##### The Impact of COVID-19 Story

This story contains several visualizations comparing bike statistics between Summer 2019 (June, July, August, and September) and Summer 2020 (June, July, August, and September). 
The first visualization is composed of two visualizations: first one (Number of Bike Trips) shows a greater number of bike rides in Summer 2019 compared to summer 2020. Interestingly, in the second visualization (Number of Available Bikes), we see the number of available bikes has increased in 2020. This could be due to the city anticipating the need for more bikes as the ones used need to be disinfected before being put back in circulation. Or, maybe it was anticipated that the pandemic would result in more people using bikes to avoid crowded spaces on public transportation. 
Data from October 2020 were included in the original September 2020 CSV file. A filter was used on both visualizations to remove 2020 October data so the analysis between summers was consistent in months.

The second visualization from the story (Most Popular Locations) shows changes in the popularity of bike stations between the two summers. We notice how the popularity of the location changes from 2019(most popular locations are in the heart of the city) to 2020(most popular locations are on the outskirts of the city). This is possibly due to the fact that people seek less crowded places amid the pandemic. The map is interactive in that it displays changes in station popularity each time a summer month is clicked. Zip codes are overlaid on top of the map.

The final visualization of the story (Busiest Times) shows the busiest times for each summer. A clear trend was noticed in summer 2019, showing the busiest time early in the morning (6-8 AM) and late afternoon (5-7 PM), indicating people were commuting on bikes to and from work. However, the same trend was not observed on summer 2020. Perhaps less people were commuting to work on bikes during the weekdays in 2020 because they were working from home as a result of the pandemic. Another thing that it's worth mentioning is that late afternoon (5-7 PM) and weekends are the busiest times in summer 2020, potentially suggesting that more people choose to ride the bike after work and on weekends in 2020 compared to 2019. This makes sense considering that concerts, sports games, pools and many other summer activities were canceled due to the pandemic.

##### Other Visualizations

Visualizations not included in the above story were Age Distribution and Average Trip Duration by Bike Station. 
Age Distribution visualization looks at the age distribution of the bike riders. After formatting the data into age bins, we can easily see which age groups are encountered most frequently throughout the analyzed dataset.
The visualization shows that the 30 to 34 years-old age category showed the highest percentage of rides.
For the Age Distribution visualization, several individuals reported erroneous ages (e.g., 130 years old). We categorized age in bins of five years and excluded anyone over 90 years old. 

The Trip Duration visualization is a map of the average duration of bike rides for each station. The longest trips are the ones starting from locations that are on the outskirts of the city. This could be due to many factors: people riding bikes to get in the city or people simply enjoying longer bike trips outside of the city where it's less crowded and polluted.
