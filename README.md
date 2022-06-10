# Kickstarting with Excel

Analyzing Kickstarter data to uncover trends and visualize the factors that would make for a successful funding campaign.

## Overview of Project

Louise is an up-and-coming theater writer who would like to begin a campaign to aid in funding her play “Fever”. She is aware that there are many factors that lead to a successful campaign. Louise would like some help in visualizing the data so that she is aware of all the factors it takes to reach her project goals.

### Purpose

Helping Louise visualize campaign outcomes based on their launch date and funding goals to determine that best steps for her project to take in order to launch a successful campaign. 

## Analysis and Challenges

In order to prepare the data, I split the categories into Parent categories and subcategories. I determined the average donation per backer to get an estimate on how much each donator is willing to contribute. I then converted the dates of when the campaigns were launched and when they ended into a more common format to read. Lastly, on this raw data set, I extracted the year of when each campaign launched to later determine if years played a role into the best launching time for a campaign. With this analysis, I was able to determine that theater campaigns were the most successful and most prominent parent category to be funded. Then with the look at the subcategories, the plays by far were the most successful in reaching their funding goals. 

This is promising for Louise’s play, so I will take it a step further and determine when these plays were most successful in gaining capital. 

### Analysis of Outcomes Based on Launch Date

I created a PivotTable which displayed the outcomes of the theater campaigns based on the month that they launched. From this data set, most campaigns launched in May and also saw the highest success rate in reaching their goal. June was right behind, as the warmer months seemed to reach more successful outcomes than the colder months. More campaigns were launched in May and June and most were successful. Not as many campaigns were launched in the winter months such as November and December and almost as many campaigns that were successful also failed to reach their goal. 

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/105755095/173149295-01f4c90b-bfcd-4d04-94a7-f42f5f9ef44f.png)

### Analysis of Outcomes Based on Goals

I then created a table that determined which monetary goals were most successful. In this analysis, I divided the monetary goals first that were less than $1,000, then by intervals of every $5,000. This analysis was preformed specifically on the subcategories of plays. I analyzed how many plays were successful, how many failed, and how many cancelled. From there I created a line graph which visualized the percentage of that information. From this graph, the most successful goals to reach were those less than $1,000 and the campaigns whose goals were $1,000- $4,999. More than 70% of these campaigns were able to reach their goals. Those campaigns that had goals of $35,000-$39,999 and $40,000- 44,999 were also above 60% successful, however, not many of these campaigns were launched so those would-be a risky goal to try and achieve for.  Those campaigns that asked for greater than $19,999 were more likely to fail than succeed. 

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/105755095/173148566-64eb2b2b-733f-4266-9c2c-df9de85b185f.png)

### Challenges and Difficulties Encountered

-	Trying to count the number of successful/failed/canceled campaigns based on their goals was very tedious at first and I made many mistakes before I figured out the correct formula to use as I was not defining the goal values correctly and was getting repeating results. 
-	Creating the formula for date created and date ended conversions was a little confusing to figure out which numbers to divide by in order to get the date. That was overcome by finding the correct formula online. 

## Results

These are the determined results based on the analysis preformed. 

### What are two conclusions you can draw about the Outcomes based on Launch Date?

-	Launching the campaign in May or June would give the highest success rate to reach your goals. 
-	Not as many campaigns are launched September – April and the likelihood that it fails is almost the same to if it is successful. 

### What can you conclude about the Outcomes based on Goals?

-	Lower campaign budgets were more successful in reaching their monetary goals. 
-	If the campaign wants to launch with a goal greater than $19,999, they are more likely to fail than succeed.  

### What are some limitations of this dataset?

-	There isn’t campaign data after 2017. It would be helpful to have more up to date data sets to see how campaigns are doing with funding now, especially after the pandemic. 
-	This dataset does not share how successful the plays were after launching and if the budget/goal they had in mind panned out to make a successful play. Knowing this information can help determine if one’s budget is too much or not enough and if they should try a campaign in other countries to be more successful. 

### What are some other possible tables and/or graphs that we could create?

-	A line graph that shares the average number of backers that contributed and the success rate in reaching their goals. 
-	A pivot table that shows the average of how much each backer is willing to contribute to the campaign depending on the month can show how many backers you will need to reach your goal and when the best time to ask would be. 

