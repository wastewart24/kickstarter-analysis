# kickstarter-analysis

Analysis of Kickstarter Projects

## Overview of Project
This project was created to analyze different Kickstarter projects and determine which ones were successfully funded and what differentiated them from one another. I analyzed two specific outcomes of successfull kickstarters using different Excel functions and presented the data to show what was more effective.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
I was able to create an analysis of how successful theater kickstarter campaigns were based on the month. I created a pivot chart and categoized the data to show me successful, failed, and cancelled outcomes for only theater kickstarters. I then created a line chart to visualize the data that you can see attached. It appeared that the summer months around June-August had the most success in getting their fundraising goals. 
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/43667985/187832404-fc764d6e-b640-4beb-ae16-ab0d41903b62.png)


### Analysis of Outcomes Based on Goals
I also created an analysis of successful cmampaigns based on how much money they were asking in donations. I performed calculations using "CountIfs" to collect the data and categorized it based on tiers of money asked for donation. I then created a line chart to visualize the data that you can see attached. It appeared that there campaigns were more successfull when the donation amount was less than $10,000. It also rose back up to above 60% when the donation range was around $40,000. Then, it spiked downwards when it increased above $40,000.
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/43667985/187832416-ddc8994a-aa54-47d7-a4d4-2e852b76549b.png)


### Challenges and Difficulties Encountered
There were many challenges in presenting the data effectively. The most difficult was being able to draw the correct data from the Kickstarter sheet and filter it correctly to present clear information in the form of charts and graphs. It was also challenging to format some of the equations like the "CountIfs". There were many criteria that had to be met and one incorrect error would sometime be difficult to debug. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

One conclusion is that theater campaigns are more successful in the summer. This makes sense because movie festivals happen over the summer and more people generally are outisde and doing activites like going to the movies and seeing plays. Another conclusion is that theater campaigns are generally successful all year as the percentage does not dip below 40% for every month of the year.

- What can you conclude about the Outcomes based on Goals?

I can conclude that kickstarter campaigns are more successful when the goal is under $5,000. Once the goal is over $45,000, the chance of a successful campaign is significantly decreased.

- What are some limitations of this dataset?

There are many limitations including how were the campaigns were marketed, who handled the campaigns, who donated to each campaign, what the donors would receive, and specific details about each product the campaigns were offering.

- What are some other possible tables and/or graphs that we could create?

We could create a graph visualizing the amount of successful campaigns based on the amount of donors who gave money. This would help determine if more donors correlated with more success. We could make bar charts about which categories were more successful and then make another chart comparing that success based on the funding goal. We could also use the average donation amount and compare it to the donor count to see how successful campaigns were with higher average donations.
