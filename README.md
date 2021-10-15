# Surfs_up Analysis


## Overview of the analysis
The purpose of this analysis is to helps investor W. Avy determine whether opening a surf and ice cream shop business in Oahu, Hawaii, would be successful. The focus of the analysis is on Oahu weather data to determine the temperature trend during June and December for the surf and ice cream shop business to be sustainable year-round.

The analysis was performed using the Oahu weather data from 2010 to 2017 that was stored in an SQLite database, hawaii.sqlite. The SQLite database file and the code for the data analysis, SurfsUp_Challenge.ipynb, can be found at http://github.com/dshetty100/surfs_up. 

Using Python, Pandas functions and methods, and SQLAlchemy to query SQLite database, the date column of the Measurements table in the hawaii.sqlite database was filtered to retrieve all the temperatures for June and December. A summary of statistics was then generated to conclude the data.

## Results
The results from the summary statistics for June and December are shown below.

![Figure1](/Images/Temp_June.PNG)    ![Figure2](/Images/Temp_Dec.PNG)

- It is observed that about 1700 weather stations recorded the June temperature, and 1517 weather stations recorded the December temperature, between the years, 2010-01-01 and 2017-08-23. 
- The average temperature that was recorded for June was 74.9 degrees and that for December was 71 degrees.
- The maximum and minimum temperatures recorded for June were 85 and 64 degrees, respectively, and that for December were 83 and 56 degrees, respectively. 

## Summary
- From the analysis of the above data it can be seen that the temperature during June and December remains pretty steady, where the average temperature stays between 71 - 75 degrees. Such a steady temperature would be perfect for the surf and ice cream shop business to be sustainable year-round.
- It would also be useful to include information on precipitation for June and December. This can also be an important factor in deciding the long-term success of the business.
- Finally, it would be useful to create a weather app using Flask with five different routes such as, Welcome, Precipitation, Stations, Monthly Temperature, and Statistics,
and share them with others via a webpage. This would provide a powerful tool for data visualization. 







