# Kickstarter-Analysis
---
## Overview of the Project
###### The purpose of this analysis is to use Kickstarter data to determine how other campaigns performed in relation to their launch dates and funding goals.
---
## Analysis and Challenges
### 1. Theater Outcomes Based on Launch Date
   - In order to capture the number of successful theater campaign outcomes based on the launch date, I created a line chart to show the canceled, failed, and successful theater campaigns in relation to their launch date.
 
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/91445591/147862965-934f7ffe-8811-4292-bb34-69fabe39fe58.png)

   - There are 1369 outcomes falling under this category. It would be challenging to view a chart displaying each individual launch date. This chart has been grouped to display the launch dates by month. 

### 2. Outcomes Based on Goals
   - I created a line chart to show the percentage of canceled, failed, and successful Play campaigns based on their goal. In order to bring in this data, the goal values were divided into twelve groups.

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/91445591/147863112-cdeea904-f4de-4e4a-a8bb-09936ac5c66d.png)

   - I encountered a challenge where the data appeared to be skewed. I was able to locate the error by revieweing the goal ranges used in the formulas that are bringing in the number of successful, failed and canceled campaigns. The range set within the formula was corrected whicn then brough in the correct data. 
---
## Results

With the data from the theater outcomes based on launch date, we can conclude that May and June launch dates result in the highest number of successful theater campaigns. We can also conclude that, although May and June launch dates have the most successful campaigns, they also have the highest count of failed campaigns. 

The data from the outcomes based on goal shows that the campaigns with a goal between $45,000 and $49,999 have a 100% success rate. 

Although both charts are bringing in accurate data, this data does not show the full picture. For example, the outcomes based on goal shows a 100% success rate for campaigns with a goal between $45,000 and $49,000 however there was only one campaigns that fell under this goal range. With this being known, I would suggest a bar graph showing the outcomes based on goal by count instead of percentage. 

On the other hand, we have the theater outcomes by launch date which is being shown based on count. Because the highest number of campaigns start in May and June, this data can also be a challenge to fully understand. I would suggest an additional line graph that shows the theater outcomes by launch date based on percentage instead of count. 
