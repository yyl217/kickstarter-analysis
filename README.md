# Kickstarting with Excel

## Overview of Project

### Background

Louise started a play named Fever came close to its fundraising goal. Louise wants to use the Kickstarter dataset to find the relationship between launch dates and their funding goals.

### Purpose

This project aims to analyze Kickstarter dataset to form analysis and visualizations on the potential relationship between variables based on historical data.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

A pivot table and a line graph were created for the Kickstarter dataset. 
The pivot table involves the starting date of all the fundraising projects as the rows and outcomes as the columns. 
The pivot table can also be filtered by year and category. 
The line graph was form based on the pivot table that was created, and it can display the trend of the outcomes based on the month of the year.

### Analysis of Outcomes Based on Goals

Twelve new rows, eight columns were created to calculate the outcome percentage based on the goal in the dollar-amount range for all the fundraising events in the dataset. 
A line graph was also created to show the overall trend of the outcome percentage based on the goals in the dollar-amount range.

### Challenges and Difficulties Encountered

The challenge for me was to group values based on a given parameter. 
The analysis of "Outcomes Based on Goals" asked to create dollar-amount ranges so projects can be grouped based on their goal amount. 
There is no easy way to create a cell that can reference a list of values with added conditions. 
My solution was to create two separate conditions next to the "goal" column so that my function "=COUNTIFS" implementation can utilize the conditions and quickly for all rows.

## Results

For the "Theater Outcomes by Launch Date" analysis, we can see a spike of successful cases between May and June. This shows that there could be a potential increase in probably if one fundraising event starts between May and Jun. One possible explanation for this phenomenon is that human activity increase during the summertime because of the warmer weather and longer day time. More people were able to participate in fundraising events. However, the dataset only has 1369 rows of data for theater, which is relatively small, and such a phenomenon could just be random events.

For the "Outcomes Based on Goal," we can see that the overall trend for successful rate goes down as the goal dollar amount increases, and fail rate goes down as the goal dollar amount increases. We can also see that the canceration rate also increases as the dollar amount increases, but not as dramatically as the success and failure rate. Based on the graph, we can conclude that as the dollar-amount increases, the fundraiser will be less likely to be successful. The potential explanation is that it is inherently harder to gather a large amount of the fund.

