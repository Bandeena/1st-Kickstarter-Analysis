# An Analysis of Kickstarter Campaigns
An analysis on Kickstarter campaigns to uncover funding and outcome trends in theatrical projects.

## Overview of Project
To better anticipate the success of the play *Fever*, we looked at trends in funding based on various data points provided by the client. We focused first on the success of other theatrical Kickstarter campaigns based on when they began their project and how much funding was requested, as well as the location of the campaign's origin. The findings presented here are a more refined projection of how long it took for other theatrical Kickstarter campaigns to be funded, so that we may better be able to anticipate the success of *Fever*.

## Analysis and Challenges
The analysis was performed in several stages. First, we converted dates for readibility and refined categories into subcategories to better break down the dataset into chunks that could be effectively analyzed. The dates presented were intially in a Unix format, so we used https://www.epochconverter.com/ to convert them into a format that Excel could process. Using those dates, we extracted the months and years to refine our analysis of what made a campaign successful.

Then we isolated the categories of interest to the client--in this case, theater and plays--so that we could focus our analyses on the success of comparable projects. This helped us to filter out information that could skew data in unexpected ways. In these analyses, we looked at various factors to determine success, including amount funded and outcomes by country, date, and category. Then we visualized these analyses with charts with embedded filters to highlight our findings. Our first focus was on launch date outcomes, and we then looked at the success of campaigns based on their stated goals, as highlighted in the following images: ![Theater Outcomes by Launch Date](/assets/images/Theater_Outcomes_vs_Launch.png)
![Outcomes Based on Goals](/assets/images/Outcomes_vs_Goals.png)

## Results
#### What are two conclusions you can draw about the Theater Outcomes by Launch Date?
*Based on the chart, one can see that the most successful month is May, but this is also when failed campaigns begin to pick up. The first part of the year is generally more successful than the second, and May is the month marking the change in trends. In addition to this, December is the least successful month, as well as the month most likely to see a failed campaign. Therefore, Spring is the best season for theater Kickstarters, where Summer and early Fall are the riskiest. February through May have the highest success to failure ratio, where June through September show a marked decrease in success. December could spell disaster for your campaign.*


#### What can you conclude about the Outcomes based on Goals?
*Campaigns are more successful when their funding goal is less than $10,000. As the funding goal increases, so does the rate of failure and cancellation. The data available for funding goals also shows that goals of less than $10,000 and more than $50,000 make up the majority of the dataset.*

#### What are some limitations of this dataset?
*This dataset does not account for qualitative or socio-economic conditions.*


#### What are some other possible tables and/or graphs that we could create?
*A comparison showing percentage funded could be useful to measure success. For this client, I think a chart showing time it took a goal to be achieved would also be useful, with filters available to refine the information presented by country and category.*
