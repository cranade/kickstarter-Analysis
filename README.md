# Kickstarting with Excel

## Overview of Project

### Purpose

In this project we deal with the Kickstarter dataset which is reasonably large. It is populated in a table form with 13 columns and 4115 rows in an excel spreadsheet. It is a time-series data from 2009 to 2017 on various  and their outcomes, funding goals and related pledges, the creation and launch of campaigns in 13 countries.

Louise's Play ***Fever*** came close to its fundraising goals. Now he wants to know how different campaigns fared in relation to their launch dates and their funding goals. Using the Kickstarter dataset we will help Louis in checking how other campaigns have faired.

## Analysis and Challenges

The analysis was done on the following topics and is submitted on the Git Hub with the repository name KICKSTARTER.

(1) **Formatting of date** and changing it in a readable form.

(2) **Data visualization** was done for each Industry in the US with respect count of Successful, Failed, Canceled and Live outcomes. From the following chart we can see that theater ranked first in terms of successful outcomes while Food industry was the lowest. Music industry also did well an received a second rank.

![Chart](https://i.imgur.com/bASEyYB.png)

**Summary statistics** showed that the average amount of goal ($5049)for funding for successful outcomes was substantially lower than that for failed outcomes.  It is not clear if it means that outcome is negatively related when it comes to funding. Other factors must be at play. Based on the *Box and Whisker* plot it was found that there is one outlier related to the amount of funding for each of successful and failed projects. It should be noted that excel certainly was useful quickly summarizing various results.

### Analysis of Outcomes Based on Launch Date

This analysis was done for Theater Project by using Pivot Table and Pivot Chart (see the following chart)
The chart shows that for successful outcomes were the largest in the month of May. This may have some relationship with the end of the Spring and beginning of Summer season. As expected, in the winter months number of successful outcomes declined substantially.

![Chart](https://i.imgur.com/LV6DmWo.png)

### Analysis of Outcomes (for Play) Based on Goals (Challenge 1)

This analysis for Play was complex and was done by grouping funding goals into 12 different group, starting with less than $1000 to Greater than $50000.

The chart shows that there was only one canceled Play. Also for lower funding goals (upto $15,000) successful outcomes were more than the failed outcomes. This situation reversed and between $20,000 to $35,000 failed outcomes exceeded the successful outcomes'. This situation reversed between $35,000 to $45,000. While in the last group of greater than $50,000 failed outcomes were more than the successful outcomes.

![Chart](https://i.imgur.com/2MwdqWR.png)

### Challenges and Difficulties Encountered

It was not too difficult to do the analysis because the instructions in the Module were very clear. The only place where a main difficulty was Encountered was while using COUNTERIFS() function for the grouped data for Play project.

## results

### Conclusions based on Launch date

When one looks at the US industry as a whole (first Chart), one finds that the following main categories successful outcomes far outstripped failed and canceled outcomes: (1) Film and Video, (2) Music, (3) Technology and (4) Theaters. This conclusion is also valid when one creates a Pivot Table for all countries. For the following categories the failed outcomes far outstrip successful outcomes: (1) Food, (2) Games, (3) Publishing, and (4) Technology.

The above finding is crucial while doing business analysis to see which industry is doing well globally.

The sample size of the Kickstarter campaign is large and one can accept the above conclusion with a high level of confidence.

###  Outcomes (for Play) based on Goals?

When it comes to the sub-category of Play, the outcomes based on the last chart show a mix picture. Louis will have conclude that there is no relationship between the funding goals and success or failure of an outcome. Her *Fever*
play belongs to the group of low budget plays.

The chart also shows that uncertainty regarding outcomes increases as on examines the plays belonging to the groups of high goals for funding.

### What are some limitations of this dataset?

One limitation is that the dataset does not give us more information to do a robust correlation analysis. Also we do not have any background about how the data was collected. The source of data is missing.

### What are some other possible tables and/or graphs that we could create

One can create pivot tables and graphs based on the Pledges for funding and see if there is any relationship with outcomes. Also one can do some regression analysis of Successful (and Failed Outcomes) with a ratio of pledges and goals.
