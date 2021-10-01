# Kickstarting with Excel bootcamp-module-1 

## Overview of Project

An analysis of The Kickstarter Funding Campaigns was conducted based on the information given at module 1. This data set includes different parent categories such as film, games, food, plays, etc. It also includes several goals and pledges with successful, failed, and cancel outcomes. By using Excel and it´s formulas, pivot tables and charts a report would be provided based on the specifications made by Louise.


### Purpose

Louise wants to know how different campaigns performed in relation to their lunch dates and their funding goals. The main purpose of this project is to provide two graphical deliverables paying specific attention to the category theater and subcategory of playas in relationship with the launch dates and goals, along with this written document.

## Analysis and Challenges




### Analysis of Outcomes Based on Launch Date

This analysis is comprehensive of the outcome for successful, failed, or canceled campaigns by the launch date. To complete this, a pivot table was created by using the Parent Category: theater as a filter, but also the years, for the information to be displayed by month. As the result of this analysis, we must conclude that May was the best month to launch the Kickstarter campaign for theater, also we can say, that December is not that good of a month to do a campaign. 

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/37987602/135280401-7684c8e2-976c-4739-90e2-63bc11a7d711.png)



### Analysis of Outcomes Based on Goals

This analysis is comprehensive of the final percentage for (successful, failed or canceled) outcome of the subcategory of plays. To complete this a new spreadsheet was create with the range of goals given by the client, it also includes the number of successful, failed or canceled campaigns and their total, to finalize this information is also represented on percentages.


![Outcomes_vs_Goals](https://user-images.githubusercontent.com/37987602/135561681-29a10477-9cac-4232-982d-992533a2b5f8.png)


### Challenges and Difficulties Encountered

The main challenges I had was with the las formula COUNTIFS since the range for the Goals has values between different numbers. I had to add and extra if (new range, new criteria).

![Captura de Pantalla 2021-09-27 a la(s) 5 16 42 p  m](https://user-images.githubusercontent.com/37987602/134997773-965d2cd2-2828-45f3-8576-c3259500bb9c.png)

### Challenges and Difficulties Encountered afert fixing the COUNTIFS Formula

The main challenge was the use of the >= and <= signs, i was using them wrong. Now they are fixed. No wonder why the graphs looked different. 


## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

The first quarter is the better time to launch a campaign, the number of campaigns cancel it always stays the same.

- What can you conclude about the Outcomes based on Goals?

The best campaigns have goals less than 1000 or between 20000 and 24999, these two ranges get a better successful percentage. This also shows that no campaigns where cancel for the subcategory of plays.

- What are some limitations of this dataset?

It will be good to know where the plays are being shown, or what theaters are participating. Also, zip codes of where the theaters and people that pledge are.

- What are some other possible tables and/or graphs that we could create?

Relationship between outcome and pledge to compare it with the goals. Relationship between Outcomes by average donation in the different categories Relationship between number of backers and the outcome.
