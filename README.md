# Surfs_up Analysis


## Overview of the analysis
The purpose of this analysis is to helps investor W. Avy determine whether opening a surf and ice cream shop business in Oahu, Hawaii, would be successful. The focus of the analysis is on Oahu weather data to determine the temperature trend during the months of June and December for the surf and ice cream shop business to be sustainable year-round.

The analysis was performed using the Ohahu weather data from 2010 to 2017 that was stored in a SQLite database, hawaii.sqlite. The SQLite databas file and the code for the data analysis, SurfsUp_Challenge.ipynb, can be found at http://github.com/dshetty100/surfs_up. 

Using Python, Pandas functions and methods, and SQLAlchemy to query SQLite database, the date column of the Measurements table in the hawaii.sqlite database was filtered to retrieve all the temperatures for the months of June and December. A summary statistics was then generated to draw conclusions from the data.

## Results
The results of the anlysis can be found in the files, retiring_titles.csv and mentorship_eligibilty.csv, under Data 
folder in  http://github.com/dshetty100/surfs_up 

- It is observed that there are total 90,398 employess with various titles who will be retiring,
- The company will need to fill in seven different titles (Senior Engineer, Senior Staff, Engineer, Staff, Technique Leader, Assistant Engineer, and Manager)
- There are 29,414 senior engineers, 28,254 senior staffs, 14,222 engineers, 12243 staffs, 4,502 technique leaders, 1,761 assistant engineers, and 2 
  managers due for retirement.
- There are 1,464 employees who are eligible for mentorship program.


## Summary
- The table for the number of retiring employees by title from retiring_titles.csv file is shown below. There are seven different roles that needs to be filled in. These are Senior Engineer, Senior Staff, Engineer, Staff, Technique Leader, Assistant Engineer, and Manager

![Figure1](/Images/Temp_June.PNG)

- The table below shows employees that are eligible for the mentorship program. There are 1,464 employees who are eligible for mentorship program. With large number of 
employees due for retirement, there may not be enough retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees.

![Figure2](/Images/Temp_Dec.PNG)
