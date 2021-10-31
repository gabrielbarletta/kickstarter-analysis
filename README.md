# kickstarter-analysis
Performing analysis on Kickstarter data to uncover trends
# Kickstarting with Excel

## Overview of Project

### Purpose
Fundraising is no easy task. Many different variables can affect the outcome of a fundraiser. Data from successful and failed campaigns can guide us through the challenges of a fundraiser. By analyzing trends of past campaigns, we will be able to make data-based decisions, increasing the chances of success. For this analysis, I used data from a sample of 4113 different fundraisers. The data was sorted and filtered to meet our client’s needs.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/92552837/138784522-618a4710-f98b-48c7-acdf-416ec7f10d55.png)

By using pivot tables, the data was filtered to get results based on launch date and theater only. This approach provided a targeted focus to meet Louise’s needs. Once the needed data was extracted, a linear graph was created. The linear graph showed the relationship between launch dates and their outcomes. One of the challenges while analyzing the data, the original filter showed the data by year which did not meet the needs of the client. Once the filter was adjusted and the data was reorganized and shown by month instead of by year, the graph was created.

### Analysis of Outcomes Based on Goals
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/92552837/138784802-21aa2425-6185-4c44-bf24-e62290f009c3.png)

For this analysis, the data was sorted based on the goal of the fundraiser. The first set of data included fundraisers with a goal of less than $1,000. Then, the following set of data includes projects having a goal between $1,000 to $4,999. Each subsequent group of fundraisers is placed in brackets showing the same range in increments of $5,000. The last set of data was grouped containing any fundraiser with a goal of more than $50,000. 
In order to obtain the necessary data, the COUNTIFs formulas were used. This allowed the use of specific conditions that extracted the required information and placed it on the corresponding bracket. Once the table was populated with the data linked to the specific projects, the percentages of each outcome were able to be determined.
After getting the percentages of each outcome, a linear graph was created to illustrate the relationship of successful, failed, and canceled projects based on goal amount. 
### Challenges and Difficulties Encountered

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

This analysis suggests that there is a significant association between the launch dates and their outcomes. The chart indicates that a campaign launched in May, June, or July has a greater success rate than the rest of the months. The data suggests that a campaign launched in December has an almost equal chance of failure or success. 

- What can you conclude about the Outcomes based on Goals?

This analysis suggests that a campaign with a goal of less than $1000 and no more than $5000 has a high success rate of 73%-76%. The graph also reveals that a campaign with a goal of $50000 or more has a high failure rate of 83%.

- What are some limitations of this dataset?

There are several limitations to the models above. While this model shows a significant association with the outcome and the month it launched, it doesn’t consider how long the fundraiser was running. It also doesn’t take into consideration where the fundraisers have taken place
- What are some other possible tables and/or graphs that we could create?

A graph that includes the average donation and the number of backers would perhaps show other variables affecting the outcome of each fundraiser. This might offer some insight on why the months had variations in levels of success. 
