# An Analysis of Kickstarter Campaigns
Performing analysis on Kickstarter data to uncover trends in order to assist Louise and her own Kickstarter Campaign
---
## Overview of Project
For this analysis we looked at Kickstarter data sets in order to assist Louise who recently started her own Kickstarter campaign for her play, Fever, which came close to its goal amount in a very short period of time. Louis has an interest in looking at how comparable Kickstarter campaigns fared, relative to their goal amounts and the launch dates of their respective campaigns. Through analysis of these data sets, we were able to identify trends regarding these metrics which we can now present to Louise so she can understand these trends and consider them in future campaigns or use them to properly assess the success of her own campaign.
---
## Analysis and Challenges
---
### Outcome Based on Launch Date
---
The first thing that we considered in this analysis is the launch dates of various Kickstarter campaigns in an attempt to understand if there were identifiable trends that showed the impact of these dates on the outcome of the campaign. To do this we created several charts that showed us which months saw the highest number of successful kickstarter campaigns. Of the 4114 total Kickstarter campaigns within the data set, 2185 of them were determined to be successful. A campaign with a "successful" outcome is one in which the amount of money "pledged" to a campaign was equal to or greater than the "goal" amount of money for the campaign. Below is a chart that shows the success, failure, and cancellation rate based on the month in which these campaigns were started.
---
![Outcomes_Based_On_Launch_Date](path/to/Outcomes_Based_On_Launch_Date.png)
---
As we can see from the graph, there is a spike in the number of successful Kickstarter campaigns starting in the month of May. That number remains high in the month of June, although it dwindles every month from May to September. There is another noticeable spike in October and November before falling to its lowest point in December. The overall success rate in the month of May is roughly 61%, in comparison to the overall success rate of roughly 53%. In June, this success rate is roughly 55%. While this is lower than the success rate of May, it is important to note that it is still higher than the overall success rate. The success rates in January, July, August, September, and December are 50%, 50%, 50%, 49%, and 44%, respectively. These are the only months in which 50% of total kickstarter campaigns, or fewer, are successful.
---
![Outcomes_Launch_Date_Pivot](path/to/Outcomes_Launch_Date_Pivot.png)
---
Now that we understand these trends, we specified for the theater category, as Louise started a theater campaign and this can give us a better understanding of if trends within the theatre category deviate from the trends we found in the overall data. As a whole, Kickstarter campaigns in the theater category are more successful than the average Kickstarter campaigns. The success rate of these Theater campaigns is roughly 61%, higher than the overall success rate of 53%. The trends of Theater-based Kickstarter campaigns very much fall in line with the overall trends we saw in the total data. Nearly 67% of theater-based Kickstarter campaigns launched in the month of May were successful. The only month in which fewer than 50% of these campaigns were successful was the month of December.
---
![Theater_Outcomes_vs_Launch](path/to/Theater_Outcomes_vs_Launch.png)
---
![Theater_Outcomes_Pivot](path/to/Theater_Outcomes_Pivot.png)
---
While I don't believe there were many difficulties in this piece of analysis, it is possible for difficulties to arise. One particular difficulty is that this data may be considered too broad by Louise if she intends to target a more specific subcategory of theater such as musicals. Even then, the data may still be too broad, as Louis may wish to consider campaigns with similar genres of musicals or similar production durations. If this were the case, we may not have enough data points to give Louise accurate data and we may identify trends that are merely the product of small data sets.
---
### Outcomes Based on Goals
---
The second component that was considered was the "goal" amount of money for these various Kickstarter campaigns and how these goal amounts had an impact on the chances of a successful campaign. We looked at the number of successful campaigns relative to this goal amount in an attempt to identify any trends that may exist. To do this, we grouped Theater-based Kickstarter campaigns into different blocks, based on the amount of money set as the "goal" amount by these campaigns. The table below shows the total number of theater-based campaigns, number of successful theater-based campaigns, number of failed theater-based campaigns, number of canceled theater-based campaigns, success rate, failure rate, and cancellation rate based on the goal amount of money for each of these campaigns.
---
![Outcome_Goals_Table](path/to/Outcome_Goals_Table.png)
---
As we can see, that success rate of these campaigns dwindles as the goal amount increases, from $0 to $34,999. There is then a jump once the goal exceeds $35,000. This is made more clear in the chart below.
---
![Outcomes_Vs_Goals](path/to/Outcomes_Vs_goals.png)
---
One of the difficulties in this analysis is the extremely small number of Kickstarter campaigns with goal amounts exceeding $15,000. While the success rate of campaigns with goals between $35,000 and $45,000 is exceptionally high, there were only 9 total campaigns that had goals within this range, meaning that there is a high susceptibility to randomness. While it is important to included these data points in our overall analysis, it is also important to consider the small number of total theater-based campaigns with goals that fit in this range and deduce that the reasoning for this small sample size is that it is uncommon for theater-campaign to require this much money, or that this size of campaign is an outlier in the total population of theater based kickstarter campaigns.
---
## Results
---
### Outcome Based on Launch Date
---
Based on the analysis we conducted on this data, there are a couple conclusions that we can come to in regards to the impact of campaign launch date on success.
---
*The best time to launch a theater-based Kickstarter campaign is between the months of May and August. Seasonally, this can be considered late-spring to mid-summer. One possible explanation for this is that this is the exact portion of the year when school is out of session for students, which may encourage families to invest in plays and performances for the future.*
---
*The worst time to launch a theater-based Kickstarter campaign is between the months of October and February. This is also considered to be late-fall to mid-winter. During this time, students are still in school and it is typically very cold, meaning that people may be less inclined to invest money into plays or productions. It is also important to note the many holidays fall within this range of months, specifically gift-giving holidays like Thanksgiving and Christmas. Since people are spending a lot of their discretionary income on gifts for others, they may be less inclined to spend on other things, specifically Kickstarter campaigns.*
---
### Outcome Based on Goals
---
Based on our analysis of data pertaining to campaign success rate versus goal size, there is one big takeaway that can be made. It is clear from the data that the smaller the goal amount, the higher the success rate of the Kickstarter campaign. That being said, this should be fairly obvious, as a smaller goal will require less investment from individuals as well as possibly a smaller number of total investors. While that is important, it should be of greater note that chances of success diminish greatly once the goal amount exceeeds $5,000. For that reason, it should be understood that is in the best interst of someone starting a theater-based Kickstarter campaign to keep their goal under $5,000, as this has an extremely high success rate. If the goal amount needs to exceed $5,000, it is probably in the best interest of the campaign creator to look for other ways of generating investments outside of Kickstarter.
---
### Dataset Limitations and Table Recommendations
---
The limitations of our dataset include the small sample size of large goal campaigns. Based on the data set we have, it appears that very few people are making Kickstarter camapgins with goals that exceed $5,000. It stands to reason that goals that exceed $5,000 typically do not use Kickstarter as their primary way of gaining investments. Other limtations include somewhat broad data about these campaigns and may not paint an accurate picture for Louise. Perhaps Louise wants to understand how her campaign stacks up against plays with similar subject matter or in specific locations such as a midwestern suburb or a city with a population greater than 500,000. I would recommend additional tables such as outcomes relative to campaign duration, outcomes relative to country of origin of the campaign, or trying to identify the average deviation between goal amount and pledged amount of all theater-based campaigns.
