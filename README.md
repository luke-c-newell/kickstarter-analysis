# Kickstarting with Excel

## Overview of Project
This analysis provides a review of historic kickstarter campaigns, in order to determine whether there are specific factors that make a crowdfunding campaign successful. Using global crowdfunding data from 2009-2017, this report provides a deep dive into whether launch dates and goal amounts affect the overall success of a campaign. This analysis uses pivot tables, scatter plots, line graphs and data tables to provide an analysis and visualization of the data.
### Purpose
My client, Louise, is a playwright looking to launch a kickstarter campaign to fund her new play, Fever. She would like to understand which factors influenced the success of previous theater campaigns, so she can set herself up for success! Her estimated budget is $10,000 and Louise would like to use the results of this analysis, to inform the creation of her own campaign.
## Analysis and Challenges
### Overview
The analysis has been segmented to highlight the outcomes based on both the launch date and the monetary goal of the campaigns. 
[The full analysis and dataset can be found here.](https://github.com/luke-c-newell/kickstarter-analysis/blob/master/Kickstarter_Challenge.xlsx.zip) Please find the raw data on the Kickstarter tab.
### Analysis of Outcomes Based on Launch Date for the Theater category
To complete this analysis, a pivot table was created to show the number of theater kickstarter campaigns that were either successful, failed or cancelled within each month between 2009 and 2017. 
![alt text](https://github.com/luke-c-newell/kickstarter-analysis/blob/master/resources/Theater_Outcomes_vs_Launch.png "Outcomes Based on Launch Date")
May was the month with the highest number of successful campaigns with 111 and the lowest month was December with 37. 
### Analysis of Outcomes Based on Goals for the Plays subcategory
To complete this analysis, a table was created using the countifs function to show the number of plays that were either successful, failed or cancelled within the shown goal amounts between 2009 and 2017. 
![alt text](https://github.com/luke-c-newell/kickstarter-analysis/blob/master/resources/Outcomes_vs_Goals.png "Outcomes Based on Goals")
Campaigns that started with a goal amount of $5000 or less had over 70% chance of being successful. Campaigns with a higher goal had a lower chance of success, with 88% of campaigns with a goal over $50,000 being unsuccessful.
### Challenges and Difficulties Encountered
While creating the table for the 'Outcomes Based on Goals' analysis, I ran into some difficulty ensuring I had the correct syntax for the 'less than' and 'greater than or equal to' operators within the COUNTIFS function. I had to lookup how to correctly use those operators within a formula in Microsoft Excel after initially running into an error.  I also decided to create a table for pulling the limits of each row, which enabled me to copy the formula down the table instead of typing each COUNTIFS function individually.
## Results
### Conclusions about the Outcomes based on Launch Date
1. May and June are the months with the most successful theater crowdfunding campaigns. I would recommend that Louise starts her campaign in one of these months to maximise her chances of success.
2. November and December are the months with the least successful theater campaigns. I would recommend avoiding starting a campaign in either of these months as the number of successful campaigns is reduced during this time of year.
### Conclusions about the Outcomes based on Goals
Campaigns that start with a goal amount of less than $5000 have shown that they are historically the most successful. Over 70% of plays with a goal amount of less than $5000 reached their target. I would recommend that Louise starts with a goal of around $5000 (but no more than $10000) as the largest number of successful campaigns began with a request of between $1000 and $5000.
### Limitations of this dataset
1. The data includes outliers that skew the dataset, including campaigns that request very little money and some that request very large amounts
2. There are considerably fewer campaigns with large goal amounts, which makes conclusions about larger goal amounts less robust
3. Not all the kickstarter campaigns may be relevant to Louise's campaign but for data integrity, we have used all campaigns in this analysis
### Suggestions for possible tables and/or graphs that we could create
I could create a clustered column chart to show the relative number of successful/failed campaigns in different countries. It could also include the average number of donors per country so that Louise is able to determine how many donors may be required to be successful.
