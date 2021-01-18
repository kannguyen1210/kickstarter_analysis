# Kickstarting with Excel

## Overview of Project

### Purpose
The project was to analyze a set of kickstarter campaigns data to identify the factors that influences the success of a fundraising campaign using data points such as launch dates, goal amount, pledge amount, categories, etc. Since the data set is rather a large one, we will be using Excel as the main tool to analyze it through Pivot Tables, formulas and visualization.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
![alt text](https://github.com/kannguyen1210/kickstarter_analysis/blob/main/Theater_Outcomes_vs_Launch.png)
The first graph, Theater Outcome by Launch Date, gives us an overview on how timeline affects the likelihood of success for campaign in the theater category. Using this graph effectively will enable us to define an appropriate launch date for a project in this category so that we will have the best chance of success in fundraising.

### Analysis of Outcomes Based on Goals
![alt text](https://github.com/kannguyen1210/kickstarter_analysis/blob/main/Outcomes_vs_Goals.png)
The second graph, Outcomes based on Goals, gives us an overall success rate of campaigns within the theater category across different ranges of fundraising goals. Using this graph effectively will enable us to define what is the best fundraising goals we should be in to have the best success rate. 

### Challenges and Difficulties Encountered
A challenge I encountered while working with Excel formula to generate the outcome based on goal analysis. it is very time consuming and prone for errors while using the COUNTIFS formula since there are a lot of variable to be hardcoded into the formula through out the table. This could lead to error if the amount of row was significantly more than what we have currently and of course would consume much more time. It is better to create separate columns for these variable and utilize referencing to be more efficient in this step.


## Results
Theater Outcomes by Launch Date gives us two useful information:
1. May and June are the best months to launch the campaign as there is a spike in successful campaign in the graphs with May giving the best success rate.
2. Q3 is the worst time to launch a campaign in the theater category as these months have the lowest successes compare to all other months throughout the year

Outcomes based on Goals shows us that the lower the fundraising goal, it is more likely to be successful rather than the bigger ones, the amount of the record from 25000 onward is very low so it would be best for us to ignore this part of the graph as the population is not enough to represent a causation.

However, there will be a few challenges while we analyze our theater campaign data using the graphs above. First of all, the Outcome by Launch Date gives us only one influence source over the success rate, therefore, even if we chose to launch when it supposedly yields the best success rate, there are other factors that could affect the outcome. The same applies for the outcome based on goals analysis, while it shows us the success rate, it is missing one crucial data which is the actual volume of the campaigns. For example, we see that the failure rate is 100% for 45k to 50k campaign but there is only 1 record in the data set.
