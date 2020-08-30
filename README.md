# Performing analysis on Kickstarter data to uncover trends
## Overview of Project
Client wants to crowdfund a play with an estimated budget of $10000.
### Purpose
The purpose of this Kickstarter Campaign Analysis is to provide key insights to create and manage a successful campaign. These insights describe how it can be run; from setting an optimal goal to the best time to start it.  
## Analysis and Challenges
### Analysis of Outcomes Based on Launch Date
![Theater_Outcomes_vs_Launch](https://github.com/luisnewmanh/kickstarter-analysis/blob/master/Resources/Outcomes_vs_Goals.png)

It is important to select the correct filters to achieve the desired visualization. In this case theater is the objective of our analysis; hence the importance of having a Parent Category filter. Also, adding year as a filter gives us more flexibility and detail by allowing us to explore the number of campaigns per year.     
### Analysis of Outcomes Based on Goals
![Outcomes_vs_Goals](https://github.com/luisnewmanh/kickstarter-analysis/blob/master/Resources/Theater_Outcomes_vs_Launch.png)

By using COUNTIFS() it was possible to set the conditions to get the number of campaigns per outcome. After translating the numbers to percentages, it is easier to identify the breaking point; it is a helpful tool to factor risk while designing a campaign. 
### Challenges and Difficulties Encountered
The biggest challenge was to type the conditions for the COUNTIFS(), while not complicated it was time consuming. I missed the option of having a for and counters to tackle the challenge. 
## Results
Overall, it can be said that Louise's Fever campaign has an 54% to be successful given the $10000 budget. Decreasing the budget would not impact the odds for success so the recommendation is to target the campaign to start on May.
- What are two conclusions you can draw about the Outcomes based on Launch Date?

Based on the date there are two clear takeaways:

1. Given the fact that most successful campaigns are launched in May it is recommended to treat this month as an anchor to the business.

2. If it is viable avoid launching a campaign during December, the possibility of reaching the goal is just above 50%. 
- What can you conclude about the Outcomes based on Goals?

1. The decision of the goal for a campaign is crucial to its success. There is a tendency in which the highest the goal the highest is the risk for not achieving it; to have the best odds to be successful the goal should be no greater than the range between $15000 to $19999.

 
- What are some limitations of this dataset?

The biggest limitation is the sample size, only 26% of the data set is related to plays which is the main interest of our customer.
- What are some other possible tables and/or graphs that we could create?

A graph that could be created is Outcomes vs Duration, it is important to find out if there is a correlation between a successful campaign and its duration; with this information Louise can have more details on how to manage her crowdfunding campaigns. Moreover, it could be interesting to analyze the number of backers as well as their behavior per campaign; with the help of a box plot it could be possible to answer questions such as: How many campaigns are being funded by 5 or less backers? How many outliers are? 

It is important to note that having plotted theater outcomes based on launch date does not tell the complete story. At stated in the conclusion it can be seen that May seems to be the best month to start a campaign; however, is this peak because May is the month with more campaigns launched or does the percentage of successful campaigns remain somewhat constant through the whole year? Also, it would be interesting to visualize number of campaigns per year and its outcome; it could be possible to identify a trend of the theatrical industry.

Finally, deeper analysis is needed to understand why campaigns between $35000 and $44999 are successful for the most part. Are they special causes? Are they linked to backers behavior?

