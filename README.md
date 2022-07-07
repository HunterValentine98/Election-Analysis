# Election Analysis With Python

## Overview of Project
In this project, we were given data by Louise. Louise is working on his own play, titled Fever, and would like us to analyze the data he provided to us about other kickstarter projects to see how they performed in certain categories.

### Purpose
The purpose of analyzing this data was for many reasons. Louise wants his play Fever to be a success. The data provided included successful, failed, and canceled kickstarter projects. By analyzing the data in depth, we could provide Louise information about what made a campaign successful versus what caused a campaign to fail or be canceled. We are hoping to provide Louise with filtered data and visualizations about kickstarter campaigns that are similar to his so that he can decide how he wants to structure his own kickstarter campaign.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
![Outcome Based on Launch Date](Resources/Theater_Outcomes_vs_Launch.png)

*Based on the graph created above, Louise should most likely launch his kickstarter in either May, June, or July. The worst month appears to be December, where the number of successful and failed campaigns are almost equal.

### Analysis of Outcomes Based on Goals
![Outcome Based on Goal](Resources/Outcomes_vs_Goals.png)

*This graph provides us data about how successful campaigns were based on their monetary goal. We see that the categories of "Less than $1000" and "$1000 to $4999" appear to have the highest success rates.

### Challenges and Difficulties Encountered
While working on this project, I ran into a few challenges. When working with the graph based on goals, it would display failed and canceled percentages as 100% throughout. I changed the line graph to a different style, and it seemed to correctly display the data afterwards. I also struggled with the COUNTIFS function while learning the criteria that needed to be entered. The excel function would only let you enter 2 sets of categories to filter by. From here, I manually had to enter the location and what to filter by if I wanted to filter by a 3rd or 4th category. I believe this helped a lot because it taught me how to actually use the function rather than letting excel create the function for me. The last category that was challenging for me to figure out was filtering the worksheet with more than one filter. I soon realized that if you highlight the row completely and then apply filters, the prior filters will stay as you add more filters.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
  1. The most successful months appeared to be May, June, and July. I would advise Louise to try and launch his Kickstarter campaign within these three months, with        May being the most successful by a decent amount (in terms of an actual number of successful campaigns, not a percentage of total campaigns).
  2. I would advise Louise to not launch his campaign in December. It appears to be the worst month by far to start a campaign (in both total number of successful          campaigns and percentage of campaigns that were successful). The number of successful campaigns and failed campaigns that launched in December are almost equal.

- What can you conclude about the Outcomes based on Goals?
  1. The most successful campaigns appear to be those with a goal that is less than $5000. I would inform Louise to try to keep his goal as low as he can (preferably below $5000 if possible) because this seems to increase his chances of the goal being met.

- What are some limitations of this dataset?
-  With this dataset, we are looking at historical data. When looking at historical data for a future campaign, we have no idea if we can use old data to predict what    future trends will happen to look like. We are also only limited to tabular data as well. If we could have links to the actual kickstarter pages, we could look at      the pages for successful campaigns and provide Louise feedback about how he should design his campaign page.

- What are some other possible tables and/or graphs that we could create?
- It would have been interesting to look at line graph from when the data was collected until today. In this graph, we could see if the success rate of kickstarter       campaigns has decreased or increased as we have gotten closer to when Louise is trying to launch his campaign. If it appears that recently kickstarter campaigns for   plays have not been doing well, we could inform Louise to most likely hold off until we have new data showing that plays seem to be doing well again.
