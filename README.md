# Kickstarting with Excel

## Overview of Project

Finding, listing, and visualizing the outcomes of the theater Kickstarters based on launch date as well as their fundraising goal as listed in the dataset.

### Purpose

To find out how different projects did in raising funds by comparing dates of launch as well as what their final fundraising goal was.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

![Launch Outcomes Pivot Table](https://github.com/LnzyDee/kickstarter-analysis/blob/main/outcomelaunch.png)

![Theater Outcomes Based on Launch Date](https://github.com/LnzyDee/kickstarter-analysis/blob/main/Theater_Outcomes_vs_Launch.png)

For this analysis, I sorted the Kickstarters in a pivot table to list only those in the theater category, and then listed the amount of which were successful, failed, or canceled and filtered these to list them by month to show differences in outcomes based on the project launch date.

### Analysis of Outcomes Based on Goals

![Outcomes vs Goals Spreadsheet](https://github.com/LnzyDee/kickstarter-analysis/blob/main/outcomesgoals.png)

![Outcomes vs Goals](https://github.com/LnzyDee/kickstarter-analysis/blob/main/Outcomes_vs_Goals.png)

To get the outcomes based on goals, I sorted the theater Kickstarters by how much the goal was, from less than $1,000 to over $50,000, going up by $5,000 increments. I then sorted the number of those that were successful, those that failed, and those canceled into their respective columns by using the COUNTIFS function of Excel. After totaling those results, I was then able to then get the percentage of each successful, failed, or canceled project.

### Challenges and Difficulties Encountered

Had some struggles getting the months listed when setting up the pivot table, but the link showing how to group and ungroup data in a pivot table listed in the hint helped: 

[Group or Ungroup Data in a Pivot Table](https://support.microsoft.com/en-us/office/group-or-ungroup-data-in-a-pivottable-c9d1ddd0-6580-47d1-82bc-c84a5a340725?ui=en-us&rs=en-us&ad=us)

Also, getting the coding correct when typing out the COUNTIFS function was a challenge; making sure every column listed was correct, and punctuation was where it was needed.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

  More projects fared better in the late spring, early summer months; others tapered off later in the year and at the start of the year.

- What can you conclude about the Outcomes based on Goals?

  Kickstarters with goals less than a $5,000 goal did significantly better in being fully funded. With projects in the range of less than $1,000 to $5,000, over 70% were successful.

- What are some limitations of this dataset?

  You don't get details of what types of theater projects were funded, the popularity of certain projects that may have aided in making them successful. Maybe some subjects of a theater project are more popular than another that may contribute to it becoming successful.

- What are some other possible tables and/or graphs that we could create?

  We could use a bar graph to visualize the pivot chart data.
