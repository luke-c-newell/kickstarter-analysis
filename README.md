# Kickstarting with Excel

## Overview of Project
This analysis provides a review of historic kickstarter campaigns, in order to determine whether there are specific factors that make a crowdfunding campaign successful. Using global crowdfunding data from 2009-2017, this report provides a deep dive into whether launch dates and goal amounts affect the overall success of a campaign. This analysis uses pivot tables, scatter plots, line graphs and data tables to provide an analysis and visualization of the data.
### Purpose
My client, Louise, is a playwright looking to launch a kickstarter campaign to fund her new play, Fever. She would like to understand which factors influenced the success of previous theater campaigns, so she can set herself up for success! Her estimated budget is $10,000 and Louise would like to use the results of this analysis, to inform the creation of her own campaign.
## Analysis and Challenges

[The full analysis and dataset can be found here.](https://github.com/luke-c-newell/kickstarter-analysis/blob/master/Kickstarter_Challenge.xlsx.zip) Please find the raw data on the Kickstarter tab.
### Analysis of Outcomes Based on Launch Date
![alt text](https://github.com/luke-c-newell/kickstarter-analysis/blob/master/resources/Theater_Outcomes_vs_Launch.png "Outcomes Based on Launch Date")
### Analysis of Outcomes Based on Goals
![alt text](https://github.com/luke-c-newell/kickstarter-analysis/blob/master/resources/Outcomes_vs_Goals.png "Outcomes Based on Goals")
### Challenges and Difficulties Encountered
While creating the table for the 'Outcomes Based on Goals' analysis, I ran into some difficulty ensuring I had the correct syntax for the 'less than' and 'greater than or equal to' operators within the COUNTIFS function. I had to lookup how to correctly use those operators within a formula in Microsoft Excel after initially running into an error.  I also decided to create a table for pulling the limits of each row, which enabled me to copy the formula down the table instead of typing each COUNTIFS function individually.
## Results
- What are two conclusions you can draw about the Outcomes based on Launch Date?
1. May and June are the months with the most successful theater crowdfunding campaigns. I would recommend that Louise starts her campaign in one of these months to maximise her chances of success.
2. November and December are the months with the least successful theater campaigns. I would recommend avoiding starting a campaign in either of these months as the number of successful campaigns is reduced during this time of year.
- What can you conclude about the Outcomes based on Goals?
Campaigns that start with a goal amount of less than $5000 have shown that they are historically the most successful. Over 70% of plays with a goal amount of less than $5000 reached their target. I would recommend that Louise starts with a goal of around $5000 (but no more than $10000) as the largest number of successful campaigns began with a request of between $1000 and $5000.
- What are some limitations of this dataset?
1. The data includes outliers that skew the dataset
2. There are considerably fewer campaigns with large goal amounts, which makes conclusions about larger goal amounts less robust
- What are some other possible tables and/or graphs that we could create?
I could create a clustered column chart to show the relative number of successful/failed campaigns in different countries. It could also include the average number of donors per country so that Louise is able to determine how many donors may be required to be successful.
