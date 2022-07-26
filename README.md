# An Analysis of Kickstarter Campaigns 

## Overview of Project

### Purpose
This analysis is intended to inform Louise's approach to crowdfunding so that her play, "Fever", can be funded and performed successfully.

### Background
The data used in this analysis consists of thousands of crowdfunding projects of varying countries of origin, launch dates, fundraising goals, and ultimate levels of success.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
![Outcomes Based on Launch Date](https://github.com/vivek-gurumoorthy/kickstarter-analysis/blob/main/Screen%20Shot%202022-07-26%20at%201.00.49%20PM.png)
![Outcomes Based on Launch Date](https://github.com/vivek-gurumoorthy/kickstarter-analysis/blob/main/Theater_Outcomes_vs_Launch.png)


### Analysis of Outcomes Based on Goals
![Outcomes Based on Goals](https://github.com/vivek-gurumoorthy/kickstarter-analysis/blob/main/Screen%20Shot%202022-07-26%20at%201.01.14%20PM.png)
![Outcomes Based on Goals](https://github.com/vivek-gurumoorthy/kickstarter-analysis/blob/main/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
- Analysis of Outcomes Based on Launch Date - Before creating the pivot table required for this analysis, I did not filter out the projects with the outcome labeled as "live". For this reason, I kept noticing a different number of total projects in the analysis from what the example output showed in the instructions. Only after carefully examining all of the columns of the pivot table was I able to determine why my total numbers were not matching and then that made creating the associated graphic significantly easier.
- Analysis of Outcomes Based on Goals - Constructing the COUNTIFS statement to tally the number of projects that were either successful, failed, or cancelled based on crowdfunding goal proved to be challenging at first because of just how many criteria were required for each statement. Each had to individually evaluate either one or two numeric conditions and an outcome condition, and therefore this was difficult to syntactically approach initially. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
   1) In the months of May, June, and July, the number of successful theater outcomes skyrockets, indicating that theater crowdfunding may be most    successful in the late spring and early summer. 
   2) Contrarily, in winter months such as December, January, and February, the number of successful campaigns is significanty reduced and a much larger proportion of failed theater outcomes appears, suggesting that winter months may be less than optimal for these crowdfunding efforts. 

- What can you conclude about the Outcomes based on Goals?
   - As crowdfunding goals of campaigns become more and more ambitious, the success rate of these campaigns also drops off significantly. This can be seen in the steady decline of the line representing successful campaigns and the ascension of the line representing failed campaigns.

- What are some limitations of this dataset?
  - This dataset does not have any data that can be used in the analysis to control for the genre of a play. Certain genres may be inherently either more or less likely to be funded successfully. Additionally, while having data on other countries may provide a more comprehensive view of the global dynamics of crowdfunding theater campaigns, having more data within one country of interest and being able to see how success of these campaigns can vary based on location within a country of interest would perhaps be more analytically applicable.  

- What are some other possible tables and/or graphs that we could create?
  - Another graph that could be created could be time to success for successful campaigns, which could be ascertained by comparing the "Date Created Conversion" to the "Date Ended Conversion".
  - Building on the idea of comparing these started and ended dates, how long successful campaigns took to reach their associated goals could also be compared against the fundraising goals that were established at the beginning of the project. 
  - Within the theater parent category, plays could be compared against musicals and their associated successes based on goal and date of creation viewed side-by-side.
