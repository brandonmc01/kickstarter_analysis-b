# Kickstarting with Excel

## Overview of Project
Kickstarter is a crowdfunding platform to help creative projects get off the ground.  In this project we will analyze kickstarter campaign data to find insights that can help launch a successful campaign.

### Purpose

The purpose of this analysis is to understand how different campaigns fared in relation to their launch dates and funding goals.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

The focal point of this analysis is understanding how the outcome of a theater campaigns are affected by the launch date.  Our Kickstarter data set is comprised of 4,114 rows of raw data for campaigns that occurred between 2009 and 2017.  To start we created a pivot table and filtered the data which had a parent category of “Theater”.  After creating our pivot table, we see the following campaign totals:

- 839 successful 
- 493 failed 
- 37 canceled
 
Next, we create a line chart to help examine the relationship of outcomes and their launch month. 
!https://github.com/brandonmc01/kickstarter_analysis-b/blob/2bcd250cb3355a7f29a9abcceb494e6a67af8430/PNGS/Theater%20Outcomes%20by%20Launch%20Date.png

The focal point of our next analysis is understanding how the outcome of theater campaign are affected by the funding goal amount.  For this analysis we create a goal to percentage table.  

!https://github.com/brandonmc01/kickstarter_analysis-b/blob/32800f4da34a9a5ae96a1a79ca8c1b77f0d7b1e0/PNGS/Percentage%20to%20goal.png

We then create a line chart visualizing the outcome of the Kickstarter campaign based on the goal.

!https://github.com/brandonmc01/kickstarter_analysis-b/blob/2bcd250cb3355a7f29a9abcceb494e6a67af8430/PNGS/Outcome%20Based%20on%20Goals.png

### Challenges and Difficulties Encountered
One challenge that others may face when analyzing this dataset is picking the best column, row, and value fields when creating their pivot tables.  

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
    - The best month to launch a Kickstarter campaign is May, followed by June.
    - The worst month to launch a Kickstarter campaign is December.
    - The highest number of theatre cancellations are in January.
- What can you conclude about the Outcomes based on Goals?
    - Campaigns with a goal of less than 1000 were the most successful followed by campaigns with a goal from 1,000 to 5,000.  

- What are some limitations of this dataset?
    - Most campaigns in our dataset have a goal of less than 15,000 which diminishes the statistical relevance of the campaigns with higher goals
    - This dataset has a country field however we are not able to drill down further into the states, provinces, or territories.  Specifically, for plays it may be helpful to deep dive into the cities. 

- What are some other possible tables and/or graphs that we could create?
    - We can perform a descriptive analysis on the data (goal and pledged amounts) to find the central tendency and variability and plot it on a Box and Whisker chart for visualization.
- We could also analyze the data by filtering the country to check where theatre campaigns have the highest chance of success.
- In ser a line chart to understand the trend in theatre campaign funding 
