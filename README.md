# Module1_Kickstarter

## Overview of Project

### The purpose of this exercise was essentially to expand upon the analysis a large dataset of kickstarter campaigns per the request of Louise, who's play "Fever" approached its fundraising goal in a brief period of time. These two additional analyses explore campaign outcomes in relation to launch date and goals, respectively. Via the use of tables and visualizations, the objective was to determine potential trends and correlations which may improve the liklihood of a successful launch for Louise's project.

## Analysis and Challenges

### Beginning with the analysis of theater outcomes by launch date, I added a column to the main Kickstarter dataset to display the year a given campaign was launched. In a new sheet, I created a pivot table to display outcomes of theater campaigns broken down by the month of their launch. To create the desired pivot table layout, I used the date created conversion as the row label, the potential outcomes as the column labels, the count of outcomes as values, and filtered by parent category and years. These fields and the resulting pivot table are pictured below.

![FieldList](https://user-images.githubusercontent.com/91569387/136727400-f00899cd-5ddf-40cb-8e1d-fc1cabe174bc.PNG)
![TheaterOutcomesByLaunchDatePivot](https://user-images.githubusercontent.com/91569387/136727426-657901c3-7840-4ec6-8801-9d9fb8bbd248.PNG)

### From the theater outcomes by launch date pivot table I created a pivot chart in the form of a line graph as a visual representation of the data displayed in the pivot table. This line graph is pictured below.

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/91569387/136727464-bccddb00-012a-49b8-8851-0c38ccb5a59b.png)

### Moving on to the outcomes based on goals, I created a table in a new sheet to display the count and percentage of campaigns successful, failed, and cancelled broken down by goal range. To create the table, I utilized the =COUNTIF formula in Excel, which allowed me to filter data from the main kickstarter dataset through multiple specific criteria, resulting in counts of successful, failed, and cancelled projects populating the Outcomes Based on Goals chart. An example of this formula is pictured below.

![Formula](https://user-images.githubusercontent.com/91569387/136727487-866bae90-eec9-40df-9be7-5af535622de9.PNG)

### The purpose of this table was to analyze how different goal amounts might correlate to the outcome of a given campaign. To clarify the data further, I created a line graph charting the difference in rate of success, failure, and cancelation as goal values rise. This chart is pictured below.

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/91569387/136727499-6135ef93-d788-4eb7-aaaa-bc07c81d2550.png)

### Overall, this assignment was fairly straightforward, as many of the steps involved applying skills and knowledge acquired and explained directly in the module. The most challenging aspect was the use of the =COUNTIF formula to create a table, mostly because of the tedious nature of making sure all formulas are correct to ensure the accuracy of the data displayed. Though I ended up not doing this in this instance, after further research I realized I could have saved a bit of time by making cell references absolute rather than relative. Because the instructions are generally very clear and helpful, most challenges at this point come from familiarizing myself with the functions of excel and working through minor issues and errors I encounter throughout the process.

## Results

### Multiple conclusions can be drawn from the theater outcomes by launch date pivot table and chart. The visualization makes it clear that there are times in the year during which a theater campaign is far more like to succeed or not compared to other times. Specifically, the data indicates that a campaign is most likely to be successful if launched during late spring and early summer, with May having the most successes (111) followed by June (100) and July (87). On the other hand launching a campaign in fall or winter was far less likely to be a success, with December faring the worst in terms of successes (37 compared to 35 failures). Failures were generally more steady throughout the year, and are therefore less influential to launch strategy.

### From the outcomes based on goals we can conclude that there doesn't seem to be a defining, obvious correlation between goal value and percentage of success. It is notable, however, that the likelihood of failure tends to increase as the goal increases, and 
