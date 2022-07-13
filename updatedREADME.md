# Kickstarting with Excel

## Overview and Purpose of Project
This analysis was done for Louise, who is looking to start a Kickstarter campaign to fund her Theater and play projects. She wants to know what a good funding goal should be, as well what time of year she should launch her campaign.
## Analysis and Challenges
To find insights with this data, I ran some analysis on Kickstart Campaigns in general as well as Kickstarter Campaigns for Theater and Plays.


![Outcomes_vs_Goals](https://user-images.githubusercontent.com/108035549/178830782-e15d8636-a462-4c9f-a9b1-2b07fc59dea1.png)


I was able to find the mean and median Funding goals for both successful and failed campaigns, and break down the percentages of successful campaigns based on their funding goal amount by building an easy to read graph.

![image](https://user-images.githubusercontent.com/108035549/178831176-b6908e9d-5dec-4ad6-9a68-03838c16e29d.png)


In addition, I created a sheet where you can filter by country as well as by Category. It is currently selected to Theater, allowing you to see the number of failed, canceled, successful, and live campaigns for every country. 

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/108035549/178831392-6cbda096-e970-43e3-ae4b-6be3da23b802.png)


I also created a PivotTable allowing Louise to see the number of successful, failed, and canceled Theater Kickstarters based on the month that they launched.

The biggest challenge for me was finding what columns to put in PivotTables to make it look nice and have insightful data showing. I overcame this by playing around for a while with different columns in the Rows, Values, and Filters in my PivotTable and double and triple checking the table once I was done.

### Analysis of Outcomes Based on Launch Date
When looking for the best date to launch a campaign, using the data is very insightful. 

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/108035549/178831802-3dbe46f9-b6aa-46ef-9b33-dcb5664552e0.png)

This graph above allows us to see that there is a large jump in the total number of campaigns launched between March and September. In total for the year, there are 779 Successful theater plays launched out of 1372 total campaigns for a baseline of 56% success rate. 489 campaigns failed in total, for a baseline of 35% failure rate.


				
![image](https://user-images.githubusercontent.com/108035549/178836338-fb22aedb-fc74-4f4a-b4fb-2a504f681f96.png)

May, June, and July see a significant jump in the total number of campaigns launched when compared to the rest of the months. There are 450 total campaigns launched in that 3 Month window, which is roughly 1/3 of the total number of theater campaigns for the year. We would normally expect that to be about 25% of all campaigns since 3 months is 25% of the year. Despite the increase in the number of campaigns launched between May and July, the success rate actually drops from our baseline to 54% (245 Successful campaigns divided by 450 total campaigns) and the failure rate rises to 37% (167 failures divided by 450 total).


![image](https://user-images.githubusercontent.com/108035549/178837360-5c61a5d3-9b6c-4756-9272-790230128475.png)

If you notice, although August only has 78 successful plays launched, it actually has the highest RATE of successful plays launched with 64% of all plays launching in August succeeding. May has the highest NUMBER of campaigns successfully launched with 88, but as noted earlier, the success rate for campaigns launched in May is only 53.6%. That's because May also sees the highest number of Failed campaigns as well with 62 failures(37% of all Campaigns launched in May). Compare that with August, who only sees 35 failed campaigns launched (28% of all campaigns launched in August).

My analysis would say to pick either August or May as the Launch Date for Louise's Campaign.


### Analysis of Outcomes Based on Goals
I broke down the success rate based on Funding Goal in increments of $5000. 
![image](https://user-images.githubusercontent.com/108035549/178839360-27b1c5fe-25cf-402d-9425-95457d621286.png)

As most would expect, in general the lower the Funding Goal amount, the higher percentage of success. Campaigns with funding Goals under $1000 see an almost 75% success rate. The rate of success drops the higher you go until roughly $15,000. Interestingly enough, goals between $15,000 and $24,999 succeed and fail at essentially an equal rate. However, goals between $25000 and $35,000 have a higher success rate and lower failure rate. The lower failure rate is likely due to the increase in cancellations as well. The vast majority of projects have funding goals under $15,000.

This graph makes it easy to see that under $15,000 seems to be the best aiming point for Louise.
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/108035549/178840100-07cbdd5b-3068-4654-91ca-a26a4a6990bf.png)


### Challenges and Difficulties Encountered
The biggest challenge for me was finding what columns to put in PivotTables to make it look nice and have insightful data showing. I overcame this by playing around for a while with different columns in the Rows, Values, and Filters in my PivotTable and double and triple checking the table once I was done.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
1. May sees the highest total number of successful Theater Campaigns with 88. However, the rate of success is only 53.6% in May and the rate of failure is 37%.
2. August sees the 3rd highest number of successful Theater Campaigns with 78 AND has the highest success rate with 64% of all Play Kickstarter Campaigns successfully achieving their goal. It also has the lowest failure rate at 28% (only 35 play campaigns failed!).
- What can you conclude about the Outcomes based on Goals?
1. The vast majority of successful campaign funding Goals are under $15,000.
2. In general, the higher the funding amount, the more likely it is to Fail or being Canceled. 
- What are some limitations of this dataset?
It doesn't have enough data to show more reasons as to why campaigns fail or succeed. For example, if we had the data for page views or for link shares for individual campaigns, we could see which social medias to share the link to in order to increase the number of views and therefore increasing the likelihood of funding.
- What are some other possible tables and/or graphs that we could create?
1. The number of months it took successful campaigns to reach their goal.
2. Which genres of plays have the highest success rate for funding?
3. Of those genres of plays, what is the average funding goal?
