# Kickstarting with Excel

## Overview of Project

### Purpose
The purpose of this project was to determine how Launch Dates and Goals might affect the outcomes of Kickstater campaigns for Plays.
## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
In order to analyze the results of Kickstarter fundraiser campaigns for Plays, I created a pivot table that would allow me to see the outcomes of the campaigns during each Month of the year. From this table I was able to see that most campaigns had been attempted in May, and see very specific results for each other month of the year. However, to make the data easier to read I converted it into a line graph with markers. This allowed me to see trends in a way that would make it easier for myself and other to understand.
### Analysis of Outcomes Based on Goals
For this analysis, I used a series of 'COUNTIFS' equations to limit the specific data I wanted, successful, failed, and canceled, for the subcategory of Plays, among different price ranged. Once the data was isolated and I determined the percentage of each category among the separate price ranges and then used that data co create a graph that would allow me and others to see trends for the dataset.
### Challenges and Difficulties Encountered
While completing my analysis of the information, I did encounter difficulty using the "COUNTIF" equation in excel. I found myslef attempting to use too many parameters within the equation to accomplish pulling the data I wanted. I later discovered the another equation "COUNTIFS" would accomplish what I wanted in a single equation. This allowed me to easily pull the data and information I needed for my analysis.
## Results
From the analysis of Outcomes Based on Launch Dates, we can make a couple of conclusions. The first of which is more successful campaigns for Plays are started in May. Both the data itself and the trend line demonstrated by the I created below shows that overwhelmingly more successful campaigns occur in May. However, it would appear the summer months, May, June, and July are all much more favorable time to begin Kickstarter campaigns for Plays. The data clearly shows these three months are the best time of the year to begin a fundraiser.

Kickstarter-Analysis/Resources/Theater_Outcomes_vs_Launch.png

Kickstarter-Analysis/Resources/Outcomes_vs_Goals.png

The analysis of the Outcomes Based on Goals, demonstrated how different goals could attribute to the outcome of the campaign. The data indicated, as seen in the graph above, that most campaigns were successful under $5,000. While the data might suggest that campaigns in the $35,000 to $45,000 range are also more succesful than other goals, the amount of campaigns that have been runs in that range is very small. Because of this, it is difficult to ascertain if that would be a legitamate conclusion from the dataset.

Despite our best analyses, the data we collected is limited. More information about the higher dollar goals would help create a more consistent trend line than the one in the Goals_vs_Outcomes.png. We could also create a table that would break down the success rate among the months of the year and the value of the goal. By breaking down that information month to month we could see if the success rate in May is related to the value of the goals in May.
