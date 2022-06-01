# Kickstarting with Excel

## Overview of Project

This is an analysis on kickstarter data to discover trends and success rates of productions done by Louise to determine the best time to start a new kickstarter for her new play Fever. With the use of the information Louise provided on past Kickstarters and Excels conditional formatting and pivot tables/charts I was able to produce the best possible time frames for Louise's new play Fever. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

For the analysis of outcomes based on launch date I gathered the information provided on the original kickstarter sheet and made a Pivot Table. I first made a "Years"" column in the original table which was used as one of the filters for the pivot table along with parent category. I made the outcomes the columns and values, and the date created the rows. I then filtered to show only theater for parent categories. With this table I then made a pivot chart. I struggled with formatting the chart, however, the outcome was worth it. 
![chart](https://github.com/tsmtruong/kickstarter-analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png)
[Outcomes Based on Launch Date](https://github.com/tsmtruong/kickstarter-analysis/blob/main/Kickstarter_Challenge.xlsx)


### Analysis of Outcomes Based on Goals

The analysis done for the outcomes based on goals was not anymore challenging in the coding aspect but it was difficult in the time aspect. For the analysis I created a new worksheet and performed the countifs function on all of the data provided in the kickstarter worksheet. I used the function to calculate the number of successful, number of failed, and number of canceled kickstarters on a range of dollar amounts grouped in 5000 dollar increments starting from 1000 dollars. I them used the sum function to figure out total projects and calculated the percentage of failed, successful, and cancelled projects. I then used this information to create a line chart to visualize the relationship between the goal amounts and the outcomes. 
![outcomes_vs_goals](https://github.com/tsmtruong/kickstarter-analysis/blob/main/Resources/Outcomes_vs_Goals.png)

[Outcomes vs. Goals](https://github.com/tsmtruong/kickstarter-analysis/blob/main/Kickstarter_Challenge.xlsx)

### Challenges and Difficulties Encountered

For the first deliverable the, Outcomes Based on Launch Date, I only had one very minor challenge when it came to the formatting of the pivot table and pivot chart but bot problems were resolved in under 5 minutes. I can see how the formatting of the two areas could become a larger issue if the excel interface is different or if the filtering functions were not similar to the one on my computer. For the Outcomes vs. Goals deliiverable, as previously stated the most challenging part was to go in and rather than automatically populating the data as I usually did in prior worksheets, each individual cell had to be manipulated slightly causing this aspect to take up a large chunk of time. I believe that there are faster ways of populate the data when it come to count-ifs and I hope to figure it out soon.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

The rwo conclusions I can draw about the outcomes based on launch date are that the most successful months to launch a play Kickstarter are in the months of May and June with 111 and 100 successful launches. The months that have the most failed Kickstarters are the months of May and a tie between July and October. With 52 and 50 failures recorded. Even though May has the highest recorded failures, it has a significantly higher number of successes. My recommendation would be to launch a kickstarter in May or JUne and avoid the months of October or December. As both months only recorded a small amount of successes as opposed to failures

- What can you conclude about the Outcomes based on Goals?

Besed on my analysis the most successful kickstarters usually have a goal from less than 1000 dollars to about 4999 dollars. While the analysis shows that goals between 20,000 and 24,999 had the most successful outcomes, the percentage of failures was also higher. While I would still feel mildly confident to advise Louise to launch a play with a higher budget, I would feel the most confident to advise her to stay under 5,000 dollars. 

- What are some limitations of this dataset?

The dataset is limited in the fact that the two charts could not be combined to be analysed together. I believe that the charts would be more accurate if we had information on which price range as the most successful in the months with the most successful launches.

- What are some other possible tables and/or graphs that we could create?

I would create a graph or table comparing all of the goals with outcomes and months to get a clearer understanding of what would be the ideal launch date. I would also make all of the charts and graphs filterable by country as we would want information specific to the country we would be launching in. 
