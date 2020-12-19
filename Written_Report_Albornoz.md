# Kickstarting with Excel

## Overview of Project

### Purpose
The purpose of this challenge is to practice Vlookups, CountIFs and charts creation in Excel in order to reach some conclusions/recommendations regarding how different campaigns behave in relation to when they are launched and their funding goals. The exercise is based on the Kickstarter dataset 
## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
**Campaigns launched in May and June are the most successful ones** followed by those launched in July.
The curve of the *failed* campaigns is very similar to the one of the *successful* ones, suggesting there might be a somewhat steady relation between success, failed vs started. There are two exceptions: in comparison, the failed curve is a bit flatter for the good months (May to July), confirming the conclusion above, and it grows instead of decreasing for December from which I infer that **December is the worse month to start a campaign**.

In other words, if based just on this analysis alone, we could recommend launching a campaign between May and Jun and avoid launching it in December

### Analysis of Outcomes Based on Goals
The campaigns with goals below 5K have the highest *success percentage*. Conversely campaigns with goals 45K and up have the lowest *success percentage*.
Seems *success percentage* have an inverse relationship to the goal size when the goal is up to 29999, and even though the same cannot be said for the second group of goals, it is important to notate the amount of campaigns with larger goals are way fewer than those with goals within the lower buckets.

### Challenges and Difficulties Encountered
Given that I've never used GitHub before, it was somewhat challenging, so I'm crossing my fingers so this gets properly uploaded :o)

It was also interesting having to limit the analysis to the items specified on the challenge and witheld the impulse to *play* more with the data and graphs to see what other conclusions/recommendations could be drawn from the same dataset.

## Results

***What are two conclusions you can draw about the Outcomes based on Launch Date?***
1. Campaigns launched in May and June are the most successful ones followed by those launched in July.
2. December is the worst month to start a campaign

In other words, if based just on this analysis alone, we could recommend launching a campaign between May and Jun and avoid launching it in December

***What can you conclude about the Outcomes based on Goals?***
The campaigns with goals below 5K have the highest *success percentage*. Conversely campaigns with goals 45K and up have the lowest *success percentage*.

***What are some limitations of this dataset?***
For this part of the analysis, we are not considering the amount pledged, thus we’re not considering how close (or far) a campaign that failed was to be successful. 

Also seems would be wise to consider the number of campaigns when trying to reach conclusions, for example one might be tempted to say that a campaign with a goal 35 to 50K is more likely to be successful (66% successful percentage) vs say one in the $5 to 15K ranges (~55%) – however the total campaigns in the later range is way larger than the ones in the former one, so perhaps even when the *success percentage* is higher, does not necessarily mean we should advice a campaign with a goal in the higher range to be deployed. We should first determine if they are outliers. 

***What are some other possible tables and/or graphs that we could create?***
Some would be pledges vs goals, pledges vs launch date, and find a way to create some context in relationship to the total of campaigns if/when analyzing percentage of success and total pledges per month vs total campaigns and goals to see if there is a relationship. We should also consider filter down further to analyze deeper data for projects closer *Louise’s*
