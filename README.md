# Kickstarter_Challenge
Analysis of theater kickstarter campaigns
# Kickstarting with Excel

## Overview of Project
A comparison of theater outcomes by launch date and an analysis of kickstarter campaign goals.

### Purpose
The purpose of this project is to predict a time frame to launch a kickstarter campaign and compare kickstarter goals to campaigns that were successful and those that failed. 

## Analysis and Challenges
I was able to filter categories into a parent category and their subcategories.  Using the subcategories, I filtered by theater plays, then the time of year the kickstarter campaign launched, and finally a filter of the outcome of the kickstarter campaign.  I did a further anaylsis based on $5000 incremental kickstarter goals.  The anaylsis is broken into quantitative data for the number of successful, failed and canceled campaigns as well as a percentage of the same. 

### Analysis of Outcomes Based on Launch Date
After filtering the data to theater ouctomes by the month of year the kickstarter campaign was launched, the best months to launch are between May and July.  During these months over 450 campaigns were launched and nearly 300 were successful.  May had the most campaigns launched (166) with the most success (111).  On the other end of the comparison, the month of December saw only 50% of the campaigns to be successful.   

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/96890065/155855346-4bb4376d-a340-4b6d-8d31-cc7d05c7c6c8.png)

### Analysis of Outcomes Based on Goals
The kickstarter goals were broken down in 12 ranges.  The first range was less than $1000, the next 10 ranges were in increments of approximately $4999, with the final range over $50,000.  The data is broken down into quantitative data as well as percentages fo the total projects launched in those goal ranges.  The most successfull campagins were those that set a goal under $5000. In the range of less than $1000, 76% of the projects that set this goal, met their goal.  The campaigns in the range of $1000 - $4999, had a 73% successful range.  The outcomes also showed that the projects that met their goal, saw no cancelation of the project. 

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/96890065/154868201-86375147-a59d-46a5-a3c1-34141902c3c6.png)

### Challenges and Difficulties Encountered
A challenge I encountered was with my IFCOUNTS.  In seeting a range from say $5000 - $9999, I was not able to figure out on my own how to create lower and upper boundaries.  I was able to get help from the AskBCS Learnging Assistants.  She helped me to realize that I needed to include the code "Kickstarter!" for both the upper and lower limits of the range.  Once I did this, the numbers matched my filtered tab.  Another learning experience was to lock the cells before copying and pasting.  I waited to late and this lead to some wasted time.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
In conclusion, the best time to launch a kickstarter campaign is late Spring/early Summer.  December saw the highest failure rate, so I would not recommend launching at this time.  It would be best to hold off until after February to launch a kickstarter campaign.

- What can you conclude about the Outcomes based on Goals?
Plays that set a goal under $5000 had a high percentage of meeting their goal.  Plays also appear to be a project that once the goal is met they are not canceled. 

- What are some limitations of this dataset?
Some limitations of the dataset are, first the launch date and outcomes based on goals are worldwide.  They are not filtered down to country.  If the client would like to know the US market or Great Britain's, the data should be filtered for these 2 countries.  Another limitation that is not considered is how much time it took each project to meet their goal.  This would be valuable information to a client as they would need to know how much time to dedicate to reaching a goal.
