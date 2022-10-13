# Kickstarting with Excel

## Overview of Project

### Purpose
To make large sets of data easier to read and understand by converting data into organized charts and pivot tables according to user need 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
To display the number of different outcomes (successful, failed, canceled, and total number of projects) for each month under "theater" as parent category

### Analysis of Outcomes Based on Goals
To display the percentage of successful vs failed projects at different ranges for goal amounts

### Challenges and Difficulties Encountered
In general, I had little to no issues following the directions for this assignment. I had some syntax issues such as missing end parenthesis in a long formula. Over 4000 rows can seem intimidating at first because there's so much data that it's overwhelming to find a starting point to organize the data into more meaningful presentation. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

  Under theater category, October is the only month without any canceled campaigns, and December has nearly as many successful campaigns as failed campaigns and has the lowest successful rate

- What can you conclude about the Outcomes based on Goals?  

  There are zero successful projects in goal range 45000 to 49999. The lowest goal range of less than 1000 has the highest percentage of successful project, which is to be expected since it's the cheapest option and easiest to achieve.

- What are some limitations of this dataset? 

  It is not possible to view the total number of projects for each goal range based on the chart created, and therefore each data point carries the same weight. For example, only one project with goal set at between 45000 and 49999, and it carries all 100% for this range of data. In contrast, there's 186 total projects that have goals less than 1000, and each project in this price range only affects 1/186 of the point.

- What are some other possible tables and/or graphs that we could create?

  I would create a bar chart with "goal" as the x-axis and "total projects" as the y-axis to show that some of the low percentage of successful vs failed projects are due to the number of total projects instead of the ratio of successful vs failed proejects. For example, range 45000 to 49999 have a low successful rate because of the low number of total projects occurring in this range (only one total project). On the other hand, range 50000 and more have a high percentage of failed projects due to the low ratio of successful vs failed projects (16 total projects with 2 successful and 14 failed). 
