# Kickstarting with Excel

## Overview of Project
This project is part of the first weekly challenge for the Data Science Bootcamp. It let us practice and display the skills learned during the first module of the Bootcamp.

### Purpose
The purpose of the analysis was to provide Louise with further insights on Kickstarter campaigns for *plays* with relation to launch dates and funding goals.

## Analysis and Challenges
Analysis was carried out in Excel from source data provided.  Input and outputs are located in file [Kickstarter_Challenge](Kickstarter_Challenge.xlsx).

### Analysis of Outcomes Based on Launch Date
As shown in visualisation [Outcomes vs Launch Month](resources/Theater_Outcomes_vs_Launch.png), more projects are successful when launched in the months of May, Jun and July than in any other month. Although the number of failed projects remains fairly stable.

This effect is strongly noted on the years 2014-2016, with a variation of +/-1 month on either side.

Projects launched in December have the lowest success rate.

### Analysis of Outcomes Based on Goals
As shown in visualisation [Outcomes vs Goals](resources/Outcomes_vs_Goals.png), *Plays* campaigns with a goal under $15,000 are more likely to be successfully funded.

Although there are successful *plays* projects at each high goal level (except for the 45000 to 49999 range), the low number of projects on the high range (35000 and higher) makes this metric not a good indicator of the likelihood of success of a project. Further analysis of the 35000 to 44999 goal range would help resolve any doubt.

### Challenges and Difficulties Encountered
No technical difficulties were found with the data manipulation. However, some possible technical challenges that could be faced include converting the date stamps into usable dates.

The dataset is few data points on the high goal ranges for the Plays subcategories, which produces a result that may not be representative.  Further analysis is required to explain this outcome. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
  1. It is recommended to hold the launch of the Kickstart campaign until the months of May or June.
  2. It is recommended that the campaign launch is not started in December as campaigns started on December have the lowest rate of success.

- What can you conclude about the Outcomes based on Goals?
  1. It is recommended to keep the goal of the campaign under 15,000 to increase the likelyhood of being successful.

- What are some limitations of this dataset?
  - Latest full year data is from 2016, so we have assumed that trends have kept for the past 5 yrs.
  - There are few data points on the high range goals for our target subcategory (Plays).

- What are some other possible tables and/or graphs that we could create?
  - It would be interested to visualise the success rate for the different goal ranges for the *plays* campaigns based on their launch date. A heatmap would probably be a good place to see any correlation.
  - Plotting the effect of the *staff_pick* and *spotlight* boolean variables on the plots already provided may point us to investing on the campaign preparation to increase the likelyhood of being staff picked or included on the spotlight.
