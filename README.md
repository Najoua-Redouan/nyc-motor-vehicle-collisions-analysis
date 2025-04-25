 NYC Motor Vehicle Collisions Analysis

This project presents an exploratory data analysis (EDA) of motor vehicle collisions in New York City using data from NYC Open Data. The analysis investigates collision frequency, contributing factors, and trends across boroughs, time, and geography.
## Dataset
- *Source:* [NYC Open Data - Motor Vehicle Collisions](https://data.cityofnewyork.us/resource/hgxi-nx95.csv?$limit=200000)
- *Records:* 200,000 rows (limit)
- *Columns:* 29 attributes including date, time, borough, location, injuries, fatalities, and contributing factors
## Objectives
- Identify the most common contributing factors to collisions
- Visualize collision frequency by borough, zip code, and time (day of week, year)
- Analyze the number of injuries and fatalities per borough
- Compare boroughs and time periods to highlight areas with higher risks
## Tools Used
- *Python:* pandas, numpy, matplotlib, seaborn
- *Platform:* Google Colab
- *Data Cleaning & Visualization:* Bar plots, pie charts, line charts
## Key Insights
- *Friday* has the highest number of collisions; *Sunday* has the lowest.
- *Brooklyn* has the most reported collisions and injuries, followed by *Queens*.
- Most common contributing factor: *Driver Inattention/Distraction*
- Zip code *11207* reported the highest number of collisions.
- Fatalities are relatively rare but injuries are significantly concentrated in a few boroughs.
- Collisions peaked in *2022*, likely due to post-COVID mobility rebound.
## Visualizations
- *Bar Plot:* Collisions by day of the week
- *Count Plot:* Top contributing factors
- *Grouped Bar:* Injuries vs fatalities by borough
- *Line Plot:* Collisions trend by borough over years
- *Pie Chart:* Contributing factors impact on injury and death averages
## Author
*Najoua Redouan*  
Aspiring Data Analyst | LaGuardia Community College  
Passionate about using data for public safety and urban planning.
