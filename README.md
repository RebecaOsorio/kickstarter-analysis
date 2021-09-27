# Kickstarting with Excel

## Overview of Project
In this project we are helping Louise to uncover trends and ways to make a successful crowdfunding. We organized and sorted crowdfunding data so we could make relations and assumptions of how different campaigns faded based on elements like launch date, type of project, country and goal amount.

### Purpose
Louise wants to launch a play, and she noticed that her play, *Fever* came close to its fundraising goal in a short amount of time. She is interested to find a pattern so she can have more campaigns with successful outcomes.

## Analysis and Challenges
### Analysis of Outcomes Based on Launch Date
To make this analysis, with a Pivot Table obtained from all the data of `StarterBook.xlsx`; we filtered the data by Parent Category and counted all the Theater Campaigns that have asked for fundings since 2009, classifying them by month.

![outcomes_vs_launch_chart](https://user-images.githubusercontent.com/90414330/134620123-769744f9-4b25-4508-b995-e8e3b907ef21.png)

The columns are sorted in descending order according to their name, so first we have the Successful Campaigns. For example, in January we found that every year, since 2009 to 2017, were launched 84 plays in which 42 we successful, 38 failed and 4 were cancelled.

Finally, we added a Chart Line from the organized Pivot Table 

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/90414330/134256020-126f4753-32bf-45bb-9421-0a1d9cf260a3.png)

### Analysis of Outcomes Based on Goals
For this analysis, we wanted to count all the plays and visualize the percentage of successful and failed plays -since none of them were cancelled- based on the funding goal amount. 


1. We used the Excel formula: `COUNTIF` to populate the columns that will count the amount of plays that were successful, failed or cancelled depending of the Range of Goal.
 
![outcomes_vs_goals_count](https://user-images.githubusercontent.com/90414330/134621692-a54b7fcb-c8c4-432c-b4b0-89988c2da630.png)

2.  With the sum of each Row we got the Total for each range, and then the percentage of the Successful, Failed and Cancelled Plays.

![outcomes_vs_goals_percentage](https://user-images.githubusercontent.com/90414330/134622053-24d26539-8fa1-4347-bcb9-d3b7d9b5f78d.png)

3. Finally, we selected the ranges and the percentages of each category so we can obtain a Line Chart. 
Here, we can clearly see that the Goal is an important variable to keep in mind when asking for funds. 

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/90414330/134617676-8d85c26b-3b19-42c7-a7eb-64af899e95bf.png)

### Challenges and Difficulties Encountered
One Challenge is to keep true the `COUNTIF`, you should verify at least 3 times that you are correctly filtering the information, and that the Rows are the ones that you should count. Also, we have to keep an eye in the data that we are selecting to do the analysis, because when some rows are hidden, we miss them in the calculates and counts.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

In the analysis we found out that **the most successful month was July**. Additional, in June we can see that the campaigns start to take off until August, giving the clue that the **plays launched in summer vacations are the most likely to have a successful outcome**. 

We can also see that regardless the total amount of Theater Project launched, it seems like the failed projects keep in a range from 30 to 50.

- What can you conclude about the Outcomes based on Goals?

**If we want our Crowdfunding to succeed, regardless the country, we should ask for less than $10,000USD**. But if we Louise is felling conservative, she can ask up to $4,999USD.

- What are some limitations of this dataset?

**The principal limitation is the amount of data that was collected in 8 years**. 

In the total Failed Outcomes Chart, we see that the failed Campaigns are almost constant every month, but we can't declare that the number will keep constant during the year because we don't have information about plays launched after May 2017. Unless we have had data until December 2017, we canot make some estimates about how many campaigns will fail during a month and I don't feel comfortable about cutting the information untill 2016 because we already have a small amount of records.

In *Outcomes Based on Goal*, I dont want to make any assumption based on the percentage of the plays that asked for a Goal greater than $25,000 because of the amount of Data we obtained after that Range - **less than 20 events can't tell a generalized result**. So we'll need more information about big plays that ask for fundings to truly tell what happens if we ask for more money.

- What are some other possible tables and/or graphs that we could create?

An important table to show Louise, is the Category and Subcategory Statistics. There, she can see that Plays is the most popular option and that it has the best outcomes.

| Parent Categories | Subcategories |
|--|--|
| ![general_statistics_outcomes](https://user-images.githubusercontent.com/90414330/134754430-a9d5d610-53af-4285-ba9e-8e88ddbc1e76.png) | ![theater_statistics_outcomes](https://user-images.githubusercontent.com/90414330/134754431-f3543b94-192d-40b4-b750-32e9cf6bf1e0.png)
 
