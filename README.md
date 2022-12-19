# Kickstarting with Excel

## Overview of Project
The client is curious if launch date or funding goals can influence the outcome of projects.

### Purpose
This analysis will be used to determine if there is a correalation between the launch date of theater projects and their kickstarter outcome, and the funding goal of plays and the kickstarter outcome. This will help make an informed decision in regards to funding goals and timing of launches.

## Analysis and Challenges
Using the kickstarter dataset I was able to quickly put together two pivot tables and pivot charts to perform a quick analysis. There is a clear correalation with timing and funding goals in regards to the success of a play or theater project. I personally did not come across a challenge, but I can see if someone is unfamiliar with pivot tables this could be a struggle. 
### Analysis of Outcomes Based on Launch Date
![Outcomes Vs Launch](https://github.com/ecregger/kickstarter-analysis/blob/main/resources/Theater_Outcomes_vs_Launch.png)
The two takeaways from this portion of the analysis is:
1. The most success occurs for a theater project in May and the upcoming summer months of June and July.
2. Theater projects are more likely to fail in the fall and winter months. The failure count is steady through the summer months but the volume of projects seeking funding is much higher, so the rate of failure here is lower. 
### Analysis of Outcomes Based on Goals
![Outcomes Vs Goals](https://github.com/ecregger/kickstarter-analysis/blob/main/resources/Outcomes_vs_Goals.png)
if the funding goal is less than 5000, then the project is more likely to succeed. The bulk of the projects fall within this range and has a success rate of over 70%. Once we get above 15000 the analysis becomes more difficult because you simply don't have many observations to help draw a conclusion.

### Challenges and Difficulties Encountered
The dataset is a bit limited in that there aren't enough high-end funding goals to definitively say if that's a no-go for kickstarters. Also, it is difficult to tell whether it's a quality project or not, there can be more issues with the project that could affect funding goals and outcomes. 

We could possibly pull "staff picks" and "Spotlight" and chart those out to see if staff picks or spotlight projects succeeded or failed. 
