# Kickstarting with Excel

## Overview of Project

### Purpose
The purpose of this analysis is to advise Louise when she should launch her play, *Fever*, based on the the outcomes of other Kickstarter campaigns launch dates and fundraising goals.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
Louise is looking to determine when she should launch her play *Fever* based on the outcomes of other Kickstarter campaigns successfulness based on Launch Date. 
To advise Louise when she should launch her play, I created a pivot table that shows the data of all theater Kickstarter based on the dates of when they were launched. I then created line graph to display which months have been historically more successful for plays.
This data shows that the month with the highest probability of having a successful launch is May and the month with the lowest probability of a successful launch is December. Additionally, the month of December has an almost equal chance of having a successful or failed launch.
![Theater Outcomes Based on Launch Date](https://github.com/AnnieShaffer/kickstarter-analysis/blob/master/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
Louise would like to know what the probability of success for her play *Fever* based on the goal of her Kickstarter campaign using data on previous Kickstart campaigns.
To advise Louise what her Kickstarter goal should be, I created a table that displayed the number of successful, failed, and cancelled campaigns for Plays based on their fundraising goals. I then calculated the percentage of the outcomes and created a line graph as a visual. 
From this data, it is clear that plays that had goals equal to or less than $19999 had the highest rate of success.
![Outcomes vs Goals](https://github.com/AnnieShaffer/kickstarter-analysis/blob/master/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
#### Challenge One
My first challenge with this data occurred while completing the steps in the analysis of the Outcomes Based on Goals. The outcome did not populate the same as the example shown in the challenge because I used the column for "pledged" (Column E) instead of "goals" (Column D).
#### Challenge Two
Additionally I was not able to mirror the pivot table shown in Deliverable 1 Step 10. This caused great confusion and I was stuck on this step for quite a while until I read the next step, which did mirror my pivot table. This error may have occurred because I am using the newest version of Excel (Excel 2019) and the screenshots are from older versions of the program.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
  - One conclusion we can draw from the data regarding the launch date is that the greatest number of successful outcomes occur in May of each year.
  - The second conclusion we can draw from this data set is that the number of successful and failed outcomes are almost equal in the month of December each year.

- What can you conclude about the Outcomes based on Goals?
  - We can conclude that the Kickstarter campaigns that are more likely to be successful for theaters have a goal between $0 and $19999 and $35000 and $44999.

- What are some limitations of this dataset?
  - Some of the limitations of this data set are that the population size of Kickstarters decrease as the goals and pledges of the campaigns increase in dollar amount. This creates data that may be skewed as there is not as much data for these sets. 
  - Additionally, there are not an equal number Kickstarters each year. This could leave out important data based on the economy at the time of the KickStarter. Campaigns closer to the Great Recession will have much different data than those in more recent years when economies have been much more stable.

- What are some other possible tables and/or graphs that we could create?
  - One graph that could be created to predict the best launch date for Louise's play is a bar graph. This graph is similar to the line graph in that it shows the number of successful, failed, and canceled Kickstarters in the Theater parent category. It also clearly shows when she has a more statistically significant chance of having a successful launch date and what months she may be more likely to fail.
  - Additionally, we could use the table in the Outcomes Based on Goals data differently. If we used the data to show the number of successful, failed, and cancelled Kickstarter campaigns instead of the overall percentage, we can see the most appropraite goal for a successful campaign. In this case, the most successful campaigns had goals of $1000 and $4999. However, a draw back to using this method is that this is also the range that the most failed Kickstarter campaigns occurred.

