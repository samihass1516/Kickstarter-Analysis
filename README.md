# "An Analysis Of Kickstarter Campaigns"

## This analysis aims to help Louise, who wants to start a crowdfunding campaign, determine how much money is needed for her campaign. Her play “Fever” is estimated to cost around $10,000.  So, she needs help to determine if she can have a successful campaign or not. I used Excel because its widely used for data analysis and is a good source for data visualization.  

### Louise wants to start a play, so I set up different campaigns from different categories to show her if these campaigns would succeed or fail.  I used the pivot stacked column chart. And in the chart, you can see that theater has the highest success rate.  And the other campaigns didn’t do so well except for music and film, but Louise is not interested in these campaigns. 


![Subcategory Statistics](https://user-images.githubusercontent.com/114379268/195384955-51f821fd-d39b-4365-8a03-971594437602.png)

#### I then needed to determine the timing or the length of the campaign correlated with its success.  So, I created another pivot chart, using a line chart to view the dates.  Using chart graphs is easier to visualize, and they are more helpful in determining trends.  

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/114379268/195396945-29377ce1-4816-49cb-98a0-4e958787bfcd.png)

##### And to continue to help Louise plan her campaign, I had to dig deeper.  We needed to use statistics and calculations to make an accurate decision on the play.  I used a formula =COUNTIFS() to calculate the goal of the other campaigns. COUNTIFS helps count cells to meet our criteria.  And our standard here is to see if Louise will meet her $10000 goal.  I also created another pivot line chart to visualize the outcomes based on goals.

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/114379268/195397517-a21d7cc2-67e3-4061-b4a6-f8602dceafc7.png)

###### After completing my analysis, I can determine from the “Theater Outcomes by Launch Dates” chart that a booming trend is running between May and June.  It explains that people tend to go to theaters and plays more often during the summer, which means that Louise should consider starting her play during this time. And in the “Outcomes Based on Goals” chart, we can see that when the goal of the campaigns reached more than $10,000, they were more likely to fail.  That is why I recommend that Louise not exceed her $10000 goal because she has a higher chance of failing.  Some Limitations of this dataset were a lack of what types of plays and theaters there were.  It didn’t specify if there were comedy, drama, or musical plays.  And it would have been more helpful if it played from last year or this year.  
