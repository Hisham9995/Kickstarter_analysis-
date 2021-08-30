# Kickstarter_analysis-
Performing analysis on Kickstarter on data to uncover trends  

# Overview of Project

# Purpose
The purpose of this analysis is to compare the results of fundraising campaigns based on their launch dates and their funding goals using Excel we did check the trends of theaters And plays to determine the successful, failed, and canceled campaigns

# Analysis and Challenges
We can see the data provided  is organized based on different aspects,
1.  Average amount of donation 
2.  Status and goal of the campaign
3.  The description
4.   Amount pledged, the average amount of donation
5.   Category and subcategory type
6.   The dates on which the campaigns began and ended


This analysis was achieved  by Filtering  the data




# Analysis of Outcomes Based on Goals

I have created a table that retrieved the total number of campaigns based on certain criteria, I did use the COUNTIF()  statement, I retrieved the number of successful, failed, And canceled campaigns for each goal range, I found the percentages by dividing each sub-total with the overall total. The filter did  set multiple criteria, including a range for The desired campaign goal



![Screenshot (619)](https://user-images.githubusercontent.com/82621077/131405973-f46de4da-6913-4c2a-bbe1-8e7e6e08e10f.png)



# Analysis of Outcomes Based on Launch Date

I have created a pivot Table filtered the outcome by category and the launch data, we can see the total count of successful, failed, and canceled theater campaigns



![Screenshot (618)](https://user-images.githubusercontent.com/82621077/131405240-1e48fa37-2c85-48e1-a319-92ef079cf727.png)



# Challenges and Difficulties Encountered

I had faced some challenges that I encountered was forgetting to include the criteria within the COUNTIFS() statement. and the Outcomes vs Launch Date analysis difficulties were Grouping the launch date every month in the PivotTable


# Results 

# Outcomes Based on Goals Conclusions


![Screenshot (620)](https://user-images.githubusercontent.com/82621077/131406657-07f3458f-48a6-4086-8f88-7adb38e5aa44.png)

We can conclude campaigns with higher goals tend to have a greater percentage chance of failing. We can see that there is a subtle decrease in campaign success as the goal amount Becomes larger., there is an anomaly at about $35,000, in which we see a sharp increase in the success rate and a sharp decrease in failure rate.




# Outcomes Based on Launch Date Conclusions

![Screenshot (621)](https://user-images.githubusercontent.com/82621077/131407012-dc2f4d13-b15b-4c97-a7aa-87c3efe31a21.png)


The best month to start a theater campaign is in May, with the highest amount of successful outcomes. Similarly, we can tell that December would not be the best month to launch a Theater campaign, as it has the lowest number of successful outcomes. But In December the number of successful campaigns is almost equivalent to the number of failed.


# Dataset Limitations

__Incompletes data__ 
Some data were missing for campaigns that were never recorded and There are a few outliers within the dataset. unable to determine the cause of these outliers.


# A recommendation for additional tables or graphs
One graph that would be useful to include for the analysis would be a box-and-whisker plot that compares the outliers by campaign category to see if outliers are influenced by other factors within the dataset. A graph that compares the Outcomes based on the duration of the campaigns would also help determine the duration for each campaign and what campaigns were successful 
