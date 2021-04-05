# excel-challenge
**Background**

Over $2 billion has been raised using the massively successful crowdfunding service, Kickstarter, but not every project has found success. Of the more than 300,000 projects launched on Kickstarter, only a third have made it through the funding process with a positive outcome.

Getting funded on Kickstarter requires meeting or exceeding the project's initial goal, so many organizations spend months looking through past projects in an attempt to discover some trick for finding success. This project will organize and analyze a database of 4,000 past projects in order to uncover any hidden trends.

**Tools Used**

1. Microsoft Excel
2. Pivot Table
3. Pivot Chart

**Project Tasks**

In the first step, I used conditional formatting to fill each cell in the "state" column with a different color based on whether the associated campaign was successful, failed, canceled, or is still live. I also created a new column called "Percent Funded" that used a formula to uncover how much money the campaign made to reach its initial goal. Next I used conditional formatting to fill each cell in the  newly created "Percent Funded" column on a three-color scale. I also used a formula to calculate the average donation for each project. Finally, I split the "Category and Sub-Category" column into two separate columns.

![](https://github.com/erinmann12/excel-challenge/blob/main/Images/exceldata.PNG)

Using the "Category" column, I created a new sheet with a pivot table to count how many campaigns were successful, failed, canceled, or is still live. I used that information to create a stacked column pivot chart that could be filtered by country.

![](https://github.com/erinmann12/excel-challenge/blob/main/Images/pivottable%20and%20chart%20for%20category.PNG)

I completed the previous steps to make a similar pivot table and stacked column pivot chart that could be filtered by country and parent-category.

![](https://github.com/erinmann12/excel-challenge/blob/main/Images/subcategory_pivottable.PNG)

I next took the "deadline" and "launched_at" columns to convert the timestamps to a normal date. Then I created a pivot table with a "state" column and "date created" rows that could be filtered based on parent category and years. From there, I created a pivot chart line graph to visualize the data. 

![](https://github.com/erinmann12/excel-challenge/blob/main/Images/linechart_pivottable.PNG)

-------------------------------------------------------------------------------------------------------------

Erin Mann

erin.mann2019@gmail.com